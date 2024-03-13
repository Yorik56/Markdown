---
title: Installation et Utilisation de base de Git
---

WORK IN PROGRESS

## Installer l'outil Git CLI

Git CLI est un outil en ligne de commande qui permet de gérer les dépôts Git locaux et distants. Il est disponible pour les systèmes d'exploitation les plus courants, notamment Linux, Mac et Windows.

!!! exemple "Installation sur le poste"

    === "Mac M1"
        
        Pour installer Git sur un Mac M1, vous pouvez utiliser Homebrew :
        
        ```bash
        brew install git
        ```

    === "Chromebook"
        
        Sur un Chromebook, vous pouvez installer Git via Linux (Beta) :
        
        ```bash
        sudo apt install git
        ```

    === "Windows 10"
        
        Sur Windows 10, vous pouvez télécharger l'installeur depuis le site officiel de Git : [https://git-scm.com/](https://git-scm.com/)
        
        Une fois téléchargé, lancez l'installeur et suivez les instructions.


## Utilisation de base de Git

```bash title="Cloner un dépôt"
git clone <url_du_depot>
```

```bash title="Synchroniser depuis un dépôt distant"
git pull origin nom_branche
```

```bash title="Synchroniser vers un dépôt distant"
git push origin nom_branche
```

- **Push d'un commit :** `git push origin nom_de_la_branche`

- **Création et utilisation de branches :**
    - Créer une branche : `git branch nom_de_la_branche`
    - Changer de branche : `git checkout nom_de_la_branche`

- **Définition du répertoire d'origine :** `git remote add origin URL_du_projet`

- **Fusion de branches :** `git merge nom_de_la_branche`




-------------------------

Git est un système de contrôle de version qui simplifie la collaboration et le suivi des modifications lors du développement de logiciels.

Nous allons découvrir les concepts fondamentaux à travers la création d'un projet.

### Création d'un répertoire

Pour commencer, nous allons créer un nouveau répertoire. 

Le système de contrôle de version Git, n'a pas encore enregistré l'existence de ce dossier ni commencé à le suivre.

A ce stade il est impossible d'interagir avec Git, car il n'est pas encore configuré pour suivre les modifications de ce répertoire.

=== "Création d'un répertoire avec la CLI"

    ```bash title="Créer un dossier"
    mkdir new_project # Créer un nouveau dossier
    cd new_project # Accéder au dossier
    ```

=== "Affichage du répertoire dans un explorateur de fichiers"

	![mkdir](./assets/utilisation-de-base-de-git/1710279613055.png)


### Initialisation du dépôt Git

Maintenant, nous allons configurer un dépôt Git. 

`git init` est une commande qui initialise un nouveau dépôt Git dans un répertoire existant.

```bash title="Initialiser le suivi avec Git"
git init # Initialiser le suivi avec Git
```

Cette commande créée un sous-dossier `.git` contenant les informations nécessaires pour suivre les modifications des fichiers du projet.

=== "La création du dépôt GIT est possible grâce à la création du dossier caché .git"

	![git-init](./assets/utilisation-de-base-de-git/1710274976233.png)

=== "Affichage du dépôt via une interface graphique"	

	Ci-dessous, on peut constater que le répertoire est maintenant suivi par Git, car il contient la mention "master / Ø". 

	![git-init](./assets/utilisation-de-base-de-git/1710276743540.png)

### Vérification de l'état du dépôt

A tout moment, après avoir effectué des modifications dans votre projet (création/modification/suppression de fichiers), vous pouvez vérifier l'état des fichiers en utilisant la commande `git status`. 

Cela vous permettra de voir quels fichiers ont été modifiés, ajoutés à la zone de staging ou encore ceux qui sont déjà prêts à être commités.

```bash title="Vérifier l'état des fichiers"
git status
```

Dans l'exemple ci-dessous, nous pouvons voir que le dépôt est vide et ne contient aucune modification.

=== "Vérification de l'état du dépôt en CLI"

	![git-status-just-after-init](./assets/utilisation-de-base-de-git/1710275366020.png)

=== "Affichage du dépôt via une interface graphique"

    ![repo-state](./assets/utilisation-de-base-de-git/1710276945911.png)

### Staging

Maintenant non allons créer un fichier `README.md` et re-effectuer une vérification de l'état du dépôt, pour constater l'intérêt de la commande `git status`.

```bash title="Créer un fichier README.md"
touch README.md
```

Nous pouvons voir que le fichier `README.md` a été créé avec succès...

=== "Vérification de l'existance du fichier README.md"
    ![ls](./assets/utilisation-de-base-de-git/1710277299802.png)    
=== "Affichage du répertoire dans un explorateur de fichiers"
    On peut voir que le fichier `README.md` a été créé avec succès. Et qu'il n'est pas encore suivi par Git, car il apparaît en rouge. 
    ![unstaged-file](./assets/utilisation-de-base-de-git/1710277174562.png)

Si on vérifie à nouveau l'état du dépôt

```bash title="Vérifier l'état des fichiers"
git status
```
on peut voir que le fichier `README.md` est listé comme un nouveau fichier non suivi par Git.

![git-status-new-file](./assets/utilisation-de-base-de-git/1710275630000.png)

À présent, il est temps d'introduire la notion de staging avec `git add`. Cette commande permet d'ajouter des fichiers à la zone de staging, préparant ainsi leur inclusion dans le prochain commit.

Le "staging" est une étape intermédiaire dans Git où vous sélectionnez les modifications que vous souhaitez inclure dans votre prochain commit en utilisant la commande git add. Cela vous permet de contrôler précisément les changements que vous enregistrez dans l'historique de version de votre projet.

=== "Staging du fichier README.md en CLI"
    
    ```bash title="Staging du fichier README.md en CLI"
     # Ajouter tous les fichiers à la zone de staging 
     # "." signifie tous les fichiers à partir du répertoire courant
    git add README.md
    ```
=== "Affichage du répertoire dans un explorateur de fichiers"
    Voici comment effectuer la même action en utilisant l'interface graphique dans le logiciel PHP Storm de la suite Jetbrains.
    ![staging-using-interface](./assets/utilisation-de-base-de-git/1710277645593.png)


Vérifiez à nouveau l'état du dépôt pour voir que le fichier `README.md` a été ajouté à la zone de staging.

```bash title="Vérifier l'état des fichiers"
git status
```

Ci-dessous, nous pouvons voir que le fichier `README.md` est maintenant listé comme un fichier suivi par Git et prêt à être commité.

=== "Vérification de l'état du dépôt après le staging via la CLI"

    ![git-status-file-staged](./assets/utilisation-de-base-de-git/1710275822006.png)

=== "Affichage du répertoire après le staging dans un explorateur de fichiers"

    On peut voir que le fichier `README.md` a été ajouté à la zone de staging, car il apparaît en vert.
    ![after-staging](./assets/utilisation-de-base-de-git/1710277773031.png)


### Création d'un commit

Maintenant que nous avons ajouté le fichier `README.md` à la zone de staging, nous pouvons créer un commit. 

Un commit est une capture instantanée des modifications apportées à un projet à un moment donné.

=== "Création d'un commit en CLI"

    ```bash title="Créer un commit"
    git commit -m "Initial commit" # Créer un commit avec un message descriptif
    ```

=== "Création d'un commit via l'interface graphique"

    ![commit](./assets/utilisation-de-base-de-git/1710277932293.png)


Cela crée un commit avec le message "Initial commit" qui capture l'état actuel du projet. On peut voir que le commit a été créé avec succès.

L'indication « 1 file changed, 0 insertions(+), 0 deletions(-) » est un résumé des changements apportés à un fichier dans un commit Git. Voici ce que chaque partie signifie :

![first-commit](./assets/utilisation-de-base-de-git/1710276012322.png)

----------------- 

## Bonnes pratiques

- **Messages de commit significatifs :** Écrire des messages descriptifs pour chaque commit.

- **Fréquence des commits :** Effectuer des commits atomiques et réguliers pour faciliter la gestion des versions.

- **Utilisation de branches temporaires :** Créer des branches temporaires pour expérimenter sans risquer le code principal.

- **Documentation du projet :** Tenir à jour la documentation du projet pour faciliter la collaboration.

## Fonctionnalités avancées

- **Révision de l'historique :** `git log`

- **Gestion des conflits :** À résoudre manuellement après une fusion de branches.

- **Réinitialisation des modifications :** `git reset nom_du_fichier`

- **Rétablissement des modifications :** `git checkout -- nom_du_fichier`

- **Étiquetage des versions :** `git tag nom_de_la_version`


## Ressources supplémentaires

- Documentation officielle : [Git](https://git-scm.com/doc)

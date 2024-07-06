---
title: Installation
---

# Documentation MkDocs Material - Installation et Configuration

Il existe plusieurs façons d'installer mkdocs-material. Ici nous allons voir comment l'installer en utilisant pip.

La documentation officielle de mkdocs-material est disponible à l'adresse suivante : [https://squidfunk.github.io/mkdocs-material/](https://squidfunk.github.io/mkdocs-material/getting-started/)

## Télécharger le répertoire MkDocs Material depuis GitHub

Pour obtenir la version la plus récente du thème MkDocs Material, commencez par cloner le dépôt GitHub :

```bash
git clone https://github.com/squidfunk/mkdocs-material
```

## Se déplacer dans le répertoire téléchargé

Changez le répertoire courant pour entrer dans le dossier cloné :

```bash
cd mkdocs-material
```

## Installation de MkDocs en mode éditable

L'installation en mode éditable permet de refléter instantanément les modifications apportées au code source sans réinstallation :

```bash
pip install -e .
```

### Si `pip` n'est pas reconnu

Il se peut que l'exécutable `pip` ne soit pas accessible si le chemin n'est pas inclus dans votre `PATH`. Pour corriger cela :

```bash
export PATH=$HOME/.local/bin:$PATH
```

#### Charger les modifications dans le shell actuel

Après la mise à jour du `PATH`, utilisez `source` pour recharger les configurations de votre shell :

```bash
source ~/.zshrc (ou  '~/.bashrc' en fonction de votre shell)
```

Cette étape rend le chemin mis à jour immédiatement actif, permettant à votre terminal de reconnaître `pip` sans nécessiter un redémarrage.

#### Vérification de l'installation de `pip`

Pour confirmer que `pip` est correctement installé et configuré :

```bash
pip --version
```

## Construction du projet avec MkDocs

Après l'installation, générer le site pour s'assurer que tout est configuré correctement :

```bash
mkdocs build
```

## Installation de plugins nécessaires

MkDocs peut être étendu avec des plugins pour améliorer ses fonctionnalités. Par exemple, pour minifier le HTML, CSS et JavaScript :

```bash
pip install htmlmin
pip install jsmin
pip install mkdocs-minify-plugin
```

## Démarrage du serveur MkDocs

Pour visualiser et tester localement votre site :

```bash
mkdocs serve
```

Cela lancera un serveur de développement local accessible via `http://localhost:8000`, où vous pouvez voir vos modifications en temps réel.

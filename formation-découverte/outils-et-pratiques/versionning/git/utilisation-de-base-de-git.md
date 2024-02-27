---
title: Installation et Utilisation de base de Git
---

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

```bash title="Cloner un dépôt"
git clone <url_du_depot>
```

```bash title="Ajouter et valider des modifications"
git add nom_fichier
git commit -m "Message de validation"
```

```bash title="Synchroniser depuis un dépôt distant"
git pull origin nom_branche
```

```bash title="Synchroniser vers un dépôt distant"
git push origin nom_branche
```
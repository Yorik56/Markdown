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

!!! exemple "Cloner un dépôt"
    
    ```bash
    git clone <url_du_depot>
    ```

!!! exemple "Ajouter et valider des modifications"

    ```bash
    git add nom_fichier
    git commit -m "Message de validation"
    ```

!!! exemple "Synchroniser depuis un dépôt distant"

    ```bash
    git pull origin nom_branche
    ```

!!! exemple "Synchroniser vers un dépôt distant"

    ```bash
    git push origin nom_branche
    ```
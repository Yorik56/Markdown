---
title: Installation et Utilisation de base de Git
---

Rôle: Explique comment installer Git sur différents systèmes d'exploitation et fournit les commandes de base pour l'utilisation de Git.

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

    === "Code source"
        
        ```bash
        git clone <url_du_depot>
        ```

    === "Résultat"
        
        Clône le dépôt dans le répertoire local.

!!! exemple "Ajouter et valider des modifications"

    === "Code source"
        
        ```bash
        git add nom_fichier
        git commit -m "Message de validation"
        ```

    === "Résultat"
        
        Ajoute les modifications au dépôt local et les valide avec un message spécifié.

!!! exemple "Synchroniser avec un dépôt distant"

    === "Code source"
        
        ```bash
        git pull origin nom_branche
        git push origin nom_branche
        ```

    === "Résultat"
        
        Récupère les modifications depuis le dépôt distant et les envoie vers le dépôt distant spécifié.

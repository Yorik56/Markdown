---
title: Authentification à GitHub avec openssl
---

## Générer une clé SSH

```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

## Ajouter la clé SSH à l'agent SSH de GitHub

- Rendez-vous à [la page de gestion des clés SSH](https://github.com/settings/keys) de GitHub. 

- Cliquer sur "New SSH key" ou "Ajouter une clé SSH"

- Renseigner un titre pour la clé dans le champ "Title"

- Sélectionner le type de clé authentification SSH dans le champ "Key type"

- Copier le contenu de la clé publique générée précédemment dans le champ "Key"

- Cliquer sur "Add SSH key" ou "Ajouter une clé SSH" 

```

## Ressources supplémentaires

- Documentation officielle : [docs.github.com](https://docs.github.com/fr/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

---
title: Installation du projet TodoLeaf
order: 1
---

# TodoLeaf Procédure d'installation du projet

## Configuration de l'environnement de développement

```bash title="Naviguez dans le dossier de vos projets de développement"
cd "DossierDeVosProjetDev"
```

```bash title="Téléchargez le projet _TodoLeaf_ dans un nouveau dossier **todoleaf_laravue**"
git clone https://github.com/GeoffreyOlivier/todoleaf_laravue.git
```

Copiez-collez le `.env` fournis dans discord, et placez le à la racine du projet  _TodoLeaf_ (_Bien faire attention à qu'il y ai le point devant env_)

```bash title="Déplacez-vous dans le répertoire racine du projet _TodoLeaf_"
cd todoleaf_laravue
```

```bash	title="Lancez la construction des images pour les services définis dans votre fichier docker-compose.yml"
docker-compose build
```

```bash title="Démarrez les conteneurs en arrière-plan, incluant Laravel, Nginx, et MySQL"
docker-compose up -d
```

```bash title="Définissez les permissions des fichiers inclus dans le conteneur _todoleaf-app_"
docker-compose exec -u root todoleaf-app chown -R www-data:www-data /var/www
```

```bash title="Installez les dépendances PHP nécessaires pour Laravel"
docker-compose exec todoleaf-app composer install
```

```bash title="Créez les tables nécessaires dans le conteneur MySQL pour votre application Laravel"
docker-compose exec todoleaf-app php artisan migrate
```

```bash title="Création de données de test"
docker-compose exec todoleaf-app php artisan db:seed
```

## Utilisateurs de test

| Email        | Password  |
|--------------|-----------|
| adam@doe.com | adminleaf |
| jhon@doe.com | adminleaf |


login :

http://127.0.0.1:8000/login

register :

http://127.0.0.1:8000/register

add Place :

http://127.0.0.1:8000/addPlant
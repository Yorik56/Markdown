Naviguez dans le dossier de vos projets de développement

```bash
cd "DossierDeVosProjetDev"
```

Téléchargez le projet _TodoLeaf_ dans un nouveau dossier **todoleaf_laravue**

```bash
git clone https://github.com/GeoffreyOlivier/todoleaf_laravue.git
```

Copiez-collez le `.env` fournis dans discord, et placez le à la racine du projet  _TodoLeaf_ (_Bien faire attention à qu'il y ai le point devant env_)

Déplacez-vous dans le répertoire racine du projet _TodoLeaf_

```bash
cd todoleaf_laravue
```

Lancez la construction des images pour les services définis dans votre fichier docker-compose.yml

```bash
docker-compose build
```

Démarrez les conteneurs en arrière-plan, incluant Laravel, Nginx, et MySQL

```bash
docker-compose up -d
```

Définissez les permissions des fichiers inclus dans le conteneur _todoleaf-app_

```bash
docker-compose exec todoleaf-app chown -R www-data:www-data /var/www
```

Installez les dépendances PHP nécessaires pour Laravel

```bash
docker-compose exec todoleaf-app composer install
```

Créez les tables nécessaires dans le conteneur MySQL pour votre application Laravel

```bash 
docker-compose exec todoleaf-app php artisan migrate
```

login :
http://127.0.0.1:8000/login

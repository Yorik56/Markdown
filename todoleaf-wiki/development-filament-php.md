# Développer avec Filament PHP

## Resources


> https://laracasts.com/series/rapid-laravel-development-with-filament/episodes/2

> https://filamentphp.com/docs/3.x/panels/installation

## Créer un CRUD pour un modèle existant

Pour créer une ressource pour le modèle `User`, vous pouvez exécuter la commande suivante dans votre terminal :

```
php artisan make:filament-resource User
```

Cela va créer plusieurs fichiers dans le répertoire `app/Filament/Resources` :

```
.
+-- UserResource.php
+-- UserResource
|   +-- Pages
|   |   +-- Create.php
|   |   +-- Edit.php
|   |   +-- List.php
```

Pour générer automatiquement les formulaires et les tables basés sur les colonnes de la base de données de votre modèle `User`, vous pouvez utiliser l'option `--generate` :

```
php artisan make:filament-resource User --generate
```

Cela ajoutera automatiquement les champs de formulaire et les colonnes de table en fonction des colonnes de votre modèle `User`.

Pour activer la gestion des utilisateurs avec des actions comme la création, la modification et la suppression, vous pouvez utiliser l'option `--soft-deletes` si vous souhaitez également prendre en charge la suppression douce :

```
php artisan make:filament-resource User --soft-deletes
```

Cela ajoutera également la prise en charge de la suppression douce pour les enregistrements utilisateurs.

Une fois ces étapes terminées, vous devriez avoir une ressource utilisateur fonctionnelle avec FilamentPHP dans votre application Laravel. Vous pourrez accéder à cette ressource à l'URL `/admin/users`. Vous pouvez également personnaliser davantage la ressource utilisateur en fonction de vos besoins en modifiant les fichiers générés dans le répertoire `app/Filament/Resources/UserResource`.
---
title: Découverte de linux
---

# Roadmap et Exercices pour Apprendre Linux

## 1. Installation de Linux
- **Exercice**: Téléchargez et installez Ubuntu sur une machine virtuelle.
	- Utilisez VirtualBox pour créer une nouvelle machine virtuelle.
	- Téléchargez l'image ISO d'Ubuntu et installez-la sur la machine virtuelle.

## 2. Commandes de base du terminal
- **Exercice**: Naviguez dans votre système de fichiers en utilisant les commandes `ls`, `cd`, `pwd`, `mkdir`, `rm`.
	- Créez un nouveau répertoire, naviguez dedans, puis supprimez-le.
	- Affichez le contenu de répertoires différents et déterminez votre position dans l'arborescence avec `pwd`.

## 3. Gestion des paquets
- **Exercice**: Installez, mettez à jour et supprimez un logiciel.
	- Installez le navigateur Firefox avec `sudo apt install firefox`.
	- Mettez à jour tous les paquets installés avec `sudo apt update && sudo apt upgrade`.
	- Supprimez un paquet installé avec `sudo apt remove <nom_du_paquet>`.

## 4. Permissions des fichiers
- **Exercice**: Modifiez les permissions d'un fichier ou d'un répertoire.
	- Créez un fichier, changez ses permissions pour que seul l'utilisateur puisse le lire et écrire.
	- Changez le propriétaire d'un fichier à un autre utilisateur avec `sudo chown <utilisateur> <fichier>`.

## 5. Scripts shell
- **Exercice**: Écrivez un script qui archive automatiquement les fichiers d'un répertoire.
	- Utilisez `bash` pour écrire un script qui utilise `tar` pour archiver un répertoire spécifié.

## 6. Réseau et sécurité
- **Exercice**: Configurez un pare-feu simple et testez votre configuration réseau.
	- Installez `ufw` et configurez des règles pour autoriser le trafic HTTP.
	- Utilisez `ping` pour vérifier la connectivité avec un site web externe.

## 7. Serveurs et services
- **Exercice**: Installez et configurez un serveur web Apache.
	- Installez Apache avec `sudo apt install apache2`.
	- Modifiez la page d'accueil par défaut en éditant le fichier dans `/var/www/html/index.html`.

## 8. Environnements de bureau
- **Exercice**: Installez et explorez différents environnements de bureau.
	- Installez KDE avec `sudo apt install kde-standard`.
	- Comparez-le avec l'environnement GNOME en termes d'utilisation et de personnalisation.

## 9. Projets pratiques
- **Exercice**: Mettez en place un serveur de fichiers avec Samba.
	- Installez Samba et configurez-le pour partager un répertoire entre plusieurs machines.

## 10. Communauté et ressources
- **Exercice**: Contribuez à un projet open source sur GitHub.
	- Trouvez un bug à corriger ou une fonctionnalité à ajouter dans un logiciel que vous utilisez.
	- Clonez le dépôt, apportez vos modifications et soumettez une pull request.

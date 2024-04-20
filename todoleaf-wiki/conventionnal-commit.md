---
title: Convention des Commits
---

# Guide des Commits Conventionnels avec Gitmoji

Ce document fournit les lignes directrices pour la création de messages de commit utilisant le format "conventional commit" enrichi par les gitmojis et les références aux issues de GitHub.

## Format du Commit

Chaque commit doit suivre ce format général :

```
:gitmoji: <message> #<ID_ISSUE>
```

### Composantes

1. **Gitmoji :** Un emoji qui représente visuellement le type de changement effectué.
2. **Message :** Une courte description qui explique la nature du changement. Ce message commence par une majuscule et ne se termine pas par un point.
3. **ID_ISSUE :** Le numéro de l'issue GitHub concernée, précédé du symbole `#`.

## Règles pour le Message de Commit

- Le message doit être concis et explicite.
- Il doit clairement indiquer le but du commit.
- Utilisez l'impératif présent (par exemple, "Ajoute" plutôt que "Ajouté" ou "Ajoutant").

## Gitmojis Utilisés

Voici un tableau récapitulant certains gitmojis fréquemment utilisés et leur signification (https://gitmoji.dev/)  :

| Gitmoji            | Code                 | Signification                                           |
|--------------------|----------------------|---------------------------------------------------------|
| :art:              | `:art:`              | Améliorer la structure/format du code.                  |
| :zap:              | `:zap:`              | Améliorer les performances.                             |
| :fire:             | `:fire:`             | Supprimer du code ou des fichiers.                      |
| :bug:              | `:bug:`              | Corriger un bug.                                        |
| :ambulance:        | `:ambulance:`        | Correction urgente d'un bug critique.                   |
| :sparkles:         | `:sparkles:`         | Introduire de nouvelles fonctionnalités.                |
| :memo:             | `:memo:`             | Ajouter ou mettre à jour la documentation.              |
| :rocket:           | `:rocket:`           | Déployer de nouvelles fonctionnalités.                  |
| :lipstick:         | `:lipstick:`         | Mettre à jour l'interface utilisateur et les styles.    |
| :tada:             | `:tada:`             | Commencer un projet.                                    |
| :white_check_mark: | `:white_check_mark:` | Ajouter, mettre à jour, ou passer des tests.            |
| :lock:             | `:lock:`             | Corriger des problèmes de sécurité.                     |
| :construction:     | `:construction:`     | Travail en cours.                                       |
| :green_heart:      | `:green_heart:`      | Corriger des problèmes de CI (Continuous Integration).  |
| :arrow_up:         | `:arrow_up:`         | Mettre à jour des dépendances.                          |
| :hammer:           | `:hammer:`           | Faire des changements de configuration de build.        |
| :recycle:          | `:recycle:`          | Réorganiser ou refondre le code.                        |
| :heavy_plus_sign:  | `:heavy_plus_sign:`  | Ajouter une dépendance.                                 |
| :heavy_minus_sign: | `:heavy_minus_sign:` | Supprimer une dépendance.                               |
| :wrench:           | `:wrench:`           | Ajouter ou mettre à jour des fichiers de configuration. |
| :globe_with_meridians: | `:globe_with_meridians:` | Internationaliser ou localiser le projet.         |

Ce tableau permet de voir rapidement le gitmoji, le code à utiliser pour l'ajouter dans les messages de commit, et la signification associée à chaque gitmoji.

## Exemples

Voici quelques exemples de messages de commit conformes :

- **:pushpin: Maj des dépendances node #6**
- **:recycle: Réorganisation des templates #6**
- **:card_file_box: Migration de la table plants #6**
- **:see_no_evil: Ignore ziggy #6**
- **:bug: Fix down() Drop foreingkey #6**

## Bonnes Pratiques

- **Atomicité :** Chaque commit doit être minimal mais complet, c’est-à-dire qu'un commit doit inclure des changements qui ensemble réalisent une unique fonctionnalité ou correction sans dépendre de futurs commits.
- **Testez avant de commiter :** Assurez-vous que le code commité est fonctionnel et que tous les tests sont passés.
- **Revue de Code :** Les messages de commit doivent être suffisamment descriptifs pour que les autres développeurs comprennent le contexte lors des revues de code.

En suivant ces lignes directrices, les contributions au projet seront plus claires, traçables et faciles à gérer pour tous les membres de l'équipe.

---
Ce document peut être adapté et étendu en fonction des besoins spécifiques du projet ou de l'équipe.
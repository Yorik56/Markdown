---
title: Convention des Branches
---

# Guide des Règles de Branches pour le Développement

## Introduction
Ce document définit les conventions de nommage et les règles à suivre pour la création et la gestion des branches dans nos projets de développement. L'objectif est de maintenir une base de code organisée et de faciliter la collaboration entre les développeurs.

## Règles Générales
1. **Protection de la branche master :** La branche `master` est protégée. Aucun commit direct n'est autorisé sur cette branche. Toutes les modifications doivent être introduites par le biais de Pull Requests (PR) qui nécessitent une revue de code.
2. **Création de branches de travail :** Chaque développeur doit créer des branches de travail suivant un format spécifique pour toutes les nouvelles fonctionnalités, corrections ou autres tâches.

## Format des Branches de Travail
Le format pour les branches de travail est le suivant :
```
<type>/main/<issue-message>
```

### Alternatives pour `<type>` et Leurs Sens
- **feature :** Utilisé pour le développement de nouvelles fonctionnalités. Exemple : `feature/main/add-login-functionality`.
- **bugfix :** Utilisé pour les corrections de bugs. Exemple : `bugfix/main/fix-login-error`.
- **enhance :** Utilisé pour les améliorations de fonctionnalités existantes. Exemple : `enhance/main/update-login-ui`.
- **hotfix :** Utilisé pour les corrections urgentes directement sur la branche principale de production. Exemple : `hotfix/main/resolve-security-issue`.
- **refactor :** Utilisé pour le refactorisation de code qui n'affecte pas directement les fonctionnalités existantes. Exemple : `refactor/main/improve-code-efficiency`.
- **docs :** Utilisé pour les mises à jour de la documentation. Exemple : `docs/main/update-readme`.

## Conclusion
Respecter ces conventions de nommage permet non seulement de garder notre base de code propre, mais facilite également la compréhension des branches pour tous les membres de l'équipe. Les branches doivent être régulièrement synchronisées avec `master` pour éviter les conflits majeurs lors des fusions.

---

Ce document fournit un cadre clair pour la gestion des branches, en s'assurant que chaque type de tâche a un préfixe dédié qui aide à clarifier le but de la branche. Cela simplifie également le processus de revue et de gestion des versions.
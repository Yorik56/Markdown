---
title: Balises de structuration du texte
---

## Abréviations

Les balises `<abbr>` sont utilisées pour indiquer une abréviation ou un acronyme et fournir une explication complète au survol de la souris.

!!! exemple "Abréviations"

    === "Code source"
        
        ```html
        <p><abbr title="World Health Organization">WHO</abbr> est une organisation mondiale de la santé.</p>
        ```

    === "Rendu navigateur"
        
        <p><abbr title="World Health Organization">WHO</abbr> est une organisation mondiale de la santé.</p>


## Citations

- `<blockquote>` est utilisé pour représenter une citation longue qui est généralement affichée avec une indentation.
- `<q>` est utilisé pour représenter une citation courte et est souvent entouré de guillemets doubles.

!!! exemple "Citations"

    === "Code source"
        
        ```html
        <blockquote>
            <p>Ceci est une citation longue.</p>
        </blockquote>
        <p>
            <q>Ceci est une citation courte.</q>
        </p>
        ```

    === "Rendu navigateur"
        
        <blockquote>
            <p>Ceci est une citation longue.</p>
        </blockquote>
        <p>
            <q>Ceci est une citation courte.</q>
        </p>


## Citations du titre

La balise `<cite>` est utilisée pour représenter le titre d'une œuvre ou d'un événement.

!!! exemple "Citations du titre"

    === "Code source"
        
        ```html
        <cite>Le Seigneur des Anneaux</cite> est un roman de J.R.R. Tolkien.
        ```

    === "Rendu navigateur"
        
        <cite>Le Seigneur des Anneaux</cite> est un roman de J.R.R. Tolkien.


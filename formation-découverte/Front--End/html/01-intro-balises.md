---
title: Introduction aux balises
---

## Les balises ouvrantes et fermantes

Les balises ouvrantes sont utilisées pour définir le début d'un élément HTML, 

tandis que les balises fermantes marquent la fin de cet élément. 

Elles sont encadrées par des chevrons ("<" et ">") et contiennent le nom de l'élément.

!!! exemple "Les balises ouvrantes et fermantes"

    === "Balises ouvrante et fermante"
    
        ```html
        - Balise ouvrante : `<div>`
        - Balise fermante : `</div>`
        - Utilisées pour délimiter une division dans le <HTML class=""></HTML>
        ```
    
    === "Code source"
    
        ``` html
        <div>
            <p>Contenu dans une division.</p>
        </div>
        ```
    
    === "Rendu interprété par le navigateur"
    
        <div>
            <p>Contenu dans une division.</p>
        </div>

## Les balises auto-fermantes

Les balises auto-fermantes sont utilisées lorsque l'élément n'a pas de contenu. Elles se ferment automatiquement avec un "/>" à la fin de la balise ouvrante.

!!! exemple "Les balises auto-fermantes"

    === "Balise auto-fermante"
    
        ```html
        <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Description" />
        ```
    
    === "Code source"
    
        ``` html
        <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Description" />
        ```
    
    === "Rendu interprété par le navigateur"
    
        <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Description" style="display:block;margin:auto;width:250px;"/>
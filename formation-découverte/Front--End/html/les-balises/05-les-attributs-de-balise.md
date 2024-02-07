---
title: Attributs des Balises HTML
---

Les attributs HTML permettent de définir des propriétés pour les éléments HTML, influençant leur comportement et leur présentation. Voici une exploration de certains attributs globaux et spécifiques, illustrés par des exemples de code et leur rendu attendu.

## Attribut `class`

L'attribut `class` sert à définir une ou plusieurs classes CSS pour un élément, facilitant la gestion du style.

=== "Code source"

    ```html
    <div class="alerte alerte-erreur">Erreur détectée</div>
    ```

=== "Rendu navigateur"

    <div class="alerte alerte-erreur">Erreur détectée</div>

## Attribut `id`

L'`id` est un identifiant unique qui permet de cibler un élément spécifique avec CSS ou JavaScript.

=== "Code source"

    ```html
    <section id="introduction">Introduction</section>
    ```

=== "Rendu navigateur"

    <section id="introduction">Introduction</section>

## Attribut `style`

Permet d'incorporer des styles CSS directement sur un élément, bien qu'une approche externe soit préférable pour la clarté.

=== "Code source"

    ```html
    <span style="font-weight: bold;">Texte en gras</span>
    ```

=== "Rendu navigateur"

    <span style="font-weight: bold;">Texte en gras</span>

## Attribut `title`

Fournit une information supplémentaire visible au survol de l'élément.

=== "Code source"

    ```html
    <abbr title="Cascading Style Sheets">CSS</abbr>
    ```

=== "Rendu navigateur"

    <abbr title="Cascading Style Sheets">CSS</abbr>

L'attribut `title` peut également être utilisé pour fournir des informations contextuelles supplémentaires lorsqu'il est appliqué à des éléments autres que les liens (`<a>`) et les abréviations (`<abbr>`). Cela inclut des éléments tels que les images, les paragraphes, les divs, etc.

=== "Code source"

    ```html
    <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Information" title="Ceci est une info utile"  width="250px">
    ```

=== "Rendu navigateur"

    <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Information" title="Ceci est une info utile"  width="250px">

## Attribut `href` (spécifique à `<a>`)

Définit l'URL cible du lien hypertexte.

=== "Code source"

    ```html
    <a href="https://www.example.com">Visitez Example.com</a>
    ```

=== "Rendu navigateur"

    <a href="https://www.example.com">Visitez Example.com</a>

## Attribut `target` (spécifique à `<a>`)

L'attribut `target` définit où ouvrir le lien hypertexte. Il peut prendre des valeurs telles que `_blank` pour ouvrir le lien dans une nouvelle fenêtre ou un nouvel onglet.

=== "Code source"

    ```html
    <a href="https://www.example.com" target="_blank">Visitez Example.com dans une nouvelle fenêtre</a>
    ```

=== "Rendu navigateur"

    ```html
    <a href="https://www.example.com" target="_blank">Visitez Example.com dans une nouvelle fenêtre</a>
    ```

## Attribut `rel` (spécifique à `<a>`)

L'attribut `rel` spécifie la relation entre le document courant et la ressource liée. Cela est souvent utilisé pour indiquer si le lien est une référence, un lien vers une version imprimable, une préférence de langage, etc.

=== "Code source"

    ```html
    <a href="https://www.example.com" rel="nofollow">Visitez Example.com (nofollow)</a>
    ```

=== "Rendu navigateur"

    ```html
    <a href="https://www.example.com" rel="nofollow">Visitez Example.com (nofollow)</a>
    ```


## Attribut `src` (spécifique à `<img>`)

Spécifie le chemin d'accès de l'image à afficher.

=== "Code source"

    ```html
    <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Logo de l'entreprise"  width="250px">
    ```

=== "Rendu navigateur"

    <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Logo de l'entreprise"  width="250px">

## Attribut `alt` (spécifique à `<img>`)

Fournit une description textuelle de l'image pour l'accessibilité et dans le cas où l'image ne peut être chargée.

=== "Code source"

    ```html
    <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Description" width="250px"/>
    ```

=== "Rendu navigateur"

    <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Description"  width="250px"/>

## Attribut `width` et `height` (spécifiques à `<img>`)

Ces attributs permettent de définir respectivement la largeur et la hauteur de l'image en pixels, ce qui peut être utile pour optimiser l'affichage et les performances.

=== "Code source"

    ```html
    <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Photographie" width="500" height="300">
    ```

=== "Rendu navigateur"

    ```html
    <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Photographie" width="500" height="300">
    ```

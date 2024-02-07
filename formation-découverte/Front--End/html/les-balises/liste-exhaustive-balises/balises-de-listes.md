---
title: Balises de listes
---

## Liste à puces, non numérotée

- `<ul>` : Utilisée pour créer une liste à puces, non numérotée.

!!! exemple "Liste à puces"

    === "Code source"
        
        ```html
        <ul>
            <li>Élément 1</li>
            <li>Élément 2</li>
            <li>Élément 3</li>
        </ul>
        ```

    === "Rendu navigateur"
        
        <ul>
            <li>Élément 1</li>
            <li>Élément 2</li>
            <li>Élément 3</li>
        </ul>

## Liste numérotée

- `<ol>` : Utilisée pour créer une liste numérotée.

!!! exemple "Liste numérotée"

    === "Code source"
        
        ```html
        <ol>
            <li>Élément 1</li>
            <li>Élément 2</li>
            <li>Élément 3</li>
        </ol>
        ```

    === "Rendu navigateur"
        
        <ol>
            <li>Élément 1</li>
            <li>Élément 2</li>
            <li>Élément 3</li>
        </ol>

## Élément de la liste à puces ou numérotée

- `<li>` : Utilisée pour définir un élément de la liste à puces ou numérotée. Cette balise est généralement utilisée à l'intérieur des balises `<ul>` ou `<ol>`.

!!! exemple "Élément de la liste"

    === "Code source"
        
        ```html
        <ul>
            <li>Élément 1</li>
            <li>Élément 2</li>
            <li>Élément 3</li>
        </ul>
        
        <ol>
            <li>Élément 1</li>
            <li>Élément 2</li>
            <li>Élément 3</li>
        </ol>
        ```

    === "Rendu navigateur"
        
        <ul>
            <li>Élément 1</li>
            <li>Élément 2</li>
            <li>Élément 3</li>
        </ul>
        
        <ol>
            <li>Élément 1</li>
            <li>Élément 2</li>
            <li>Élément 3</li>
        </ol>

## Liste de définitions

- `<dl>` : Utilisée pour créer une liste de définitions, généralement constituée de paires de termes et de leurs définitions correspondantes.

!!! exemple "Liste de définitions"

    === "Code source"
        
        ```html
        <dl>
            <dt>Terme 1</dt>
            <dd>Définition du terme 1</dd>
            <dt>Terme 2</dt>
            <dd>Définition du terme 2</dd>
            <dt>Terme 3</dt>
            <dd>Définition du terme 3</dd>
        </dl>
        ```

    === "Rendu navigateur"
        
        <dl>
            <dt>Terme 1</dt>
            <dd>Définition du terme 1</dd>
            <dt>Terme 2</dt>
            <dd>Définition du terme 2</dd>
            <dt>Terme 3</dt>
            <dd>Définition du terme 3</dd>
        </dl>
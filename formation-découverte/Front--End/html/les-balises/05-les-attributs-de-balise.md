---
title: Attributs des Balises HTML
---

# Attributs des Balises HTML

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

## Attribut `href` (spécifique à `<a>`)

Définit l'URL cible du lien hypertexte.

=== "Code source"
```html
<a href="https://www.example.com">Visitez Example.com</a>
```

=== "Rendu navigateur"
<a href="https://www.example.com">Visitez Example.com</a>

## Attribut `src` (spécifique à `<img>`)

Spécifie le chemin d'accès de l'image à afficher.

=== "Code source"
```html
<img src="logo.png" alt="Logo de l'entreprise">
```

=== "Rendu navigateur"
<img src="logo.png" alt="Logo de l'entreprise">

## Attribut `alt` (spécifique à `<img>`)

Fournit une description textuelle de l'image pour l'accessibilité et dans le cas où l'image ne peut être chargée.

=== "Code source"
```html
<img src="avatar.png" alt="Avatar de l'utilisateur">
```

=== "Rendu navigateur"
<img src="avatar.png" alt="Avatar de l'utilisateur">

Cet aperçu couvre certains des attributs HTML les plus utilisés. Pour une liste exhaustive, la consultation de la documentation HTML officielle est recommandée, car elle fournira des détails complets sur chaque attribut, y compris ceux moins couramment utilisés ou nouveaux dans HTML5.
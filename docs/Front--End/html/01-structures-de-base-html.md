---
title: Structure de base d'un document HTML
---

# Les balises HTML

## Les balises ouvrantes et fermantes

### Présentation des balises ouvrantes et fermantes

Les balises ouvrantes sont utilisées pour définir le début d'un élément HTML, tandis que les balises fermantes marquent la fin de cet élément. Elles sont encadrées par des chevrons ("<" et ">") et contiennent le nom de l'élément.

### Exemples pratiques


=== "Balises ouvrante et fermante"

  ```html
  - Balise ouvrante : `<div>`
  - Balise fermante : `</div>`
  - Utilisées pour délimiter une division dans le HTML.
  ```
=== "Code source"

  ```html
  <div>
  <p>Contenu dans une division.</p>
  </div>
  ```
=== "Rendu interprété par le navigateur"

<div>
<p>Contenu dans une division.</p>
</div>

## Les balises auto-fermantes

### Présentation des balises auto-fermantes

Les balises auto-fermantes sont utilisées lorsque l'élément n'a pas de contenu. Elles se ferment automatiquement avec un "/>" à la fin de la balise ouvrante.

### Exemples pratiques

- Balise auto-fermante : `<img src="image.jpg" alt="Description" />`
- Utilisée pour insérer une image dans la page sans nécessiter de balise fermante distincte.

## Présentation des balises HTML

### La balise `<p>`

#### Présentation

La balise `<p>` est utilisée pour définir un paragraphe de texte dans le HTML.

#### Exemple

```html
<p>Ceci est un exemple de paragraphe.</p>
```

### La balise `<a>`

#### Présentation

La balise `<a>` est utilisée pour créer des liens hypertextes dans le HTML.

#### Exemple

```html
<a href="https://exemple.com">Lien vers un site</a>
```

### La balise `<img>`

#### Présentation

La balise `<img>` est utilisée pour insérer des images dans une page web.

#### Exemple

```html
<img src="image.jpg" alt="Description de l'image" />
```

### La balise `<ul>`

#### Présentation

La balise `<ul>` est utilisée pour créer une liste non ordonnée dans le HTML.

#### Exemple

```html
<ul>
    <li>Élément de liste 1</li>
    <li>Élément de liste 2</li>
</ul>
```

### La balise `<form>`

#### Présentation

La balise `<form>` est utilisée pour créer un formulaire interactif dans une page web.

#### Exemple

```html
<form action="traitement.php" method="post">
    <label for="nom">Nom :</label>
    <input type="text" id="nom" name="nom" />
    <input type="submit" value="Envoyer" />
</form>
```

### La balise `<div>`

#### Présentation

La balise `<div>` est utilisée pour diviser et structurer le contenu d'une page web.

#### Exemple

```html
<div>
    <p>Contenu dans une division.</p>
</div>
```

## Les balises HTML (Liste exhaustive)

### Balises de premier niveau

- `<html>` : Balise principale de toutes les pages web.
- `<head>` : En-tête de la page.
- `<body>` : Corps de la page.

### Balises d'en-tête

- `<link />` : Liaison avec une feuille de style.
- `<meta />` : Métadonnées de la page web.
- `<script>` : Code JavaScript.
- `<style>` : Code CSS.
- `<title>` : Titre de la page.

### Balises de structuration du texte

- `<abbr>` : Abréviation.
- `<blockquote>` : Citation longue.
- `<q>` : Citation courte.
- `<cite>` : Citation du titre d'une œuvre ou d'un événement.
- `<sub>` : Mise en indice.
- `<sup>` : Mise en exposant.
- `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` : Titres de différents niveaux.
- `<img />` : Image.
- `<mark>` : Mise en valeur visuelle (surlignage).
- `<strong>` : Mise en valeur forte (texte en gras).
- `<em>` : Mise en valeur faible (texte en italique).
- `<figure>` : Figure (image, code...).
- `<figcaption>` : Description de la figure.
- `<audio>` : Son.
- `<video>` : Vidéo.
- `<source>` : Format possible pour les balises `<audio>` et `<video>`.
- `<a>` : Lien hypertexte.
- `<br />` : Retour à la ligne.
- `<p>` : Paragraphe.
- `<hr />` : Ligne de séparation horizontale.
- `<address>` : Adresse de contact.
- `<del>` : Texte supprimé.
- `<ins>` : Texte inséré.
- `<dfn>` : Définition.
- `<kbd>` : Indiquer un code que doit taper le visiteur.
- `<progress>` : Barre de progression.
- `<time>` : Date ou heure.
- `<pre>` : Texte à l'intérieur de la balise sera sous forme de code.

### Balises de listes

- `<ul>` : Liste à puces, non numérotée.
- `<ol>` : Liste numérotée.
- `<li>` : Élément de la liste à puces.
- `<dl>` : Liste de définitions.
- `<dt>` : Définition du terme.

### Balises de tableau

- `<table>` : Tableau.
- `<caption>` : Titre du tableau.
- `<tr>` : Ligne de tableau.
- `<th>` : Cellule d'en-tête.
- `<td>` : Cellule.
- `<thead>` : Section de l'en-tête du tableau.
- `<tbody>` : Section du corps du tableau.
- `<tfoot>` : Section du pied du tableau.

### Balises de formulaire

- `<form>` : Formulaire.
- `<fieldset>` : Regroupement d'éléments d'un formulaire.
- `<legend>` : Titre d'un groupe dans un formulaire.
- `<label>` : Titre d'un élément de formulaire.
- `<input />` : Champ de formulaire.
- `<textarea>` : Zone de saisie multiligne.
- `<select>` : Liste déroulante.
- `<option>` : Élément d'une liste déroulante.
- `<optgroup>` : Groupe d'éléments d'une liste déroulante.

### Balises sectionnantes

- `<header>` : En-tête.
- `<nav>` : Liens principaux de navigation.
- `<footer>` : Pied de page.
- `<section>`

  : Section de page.
  - `<article>` : Article (contenu autonome).
  - `<aside>` : Informations complémentaires.

### Balises génériques

- `<span>` : Balise générique de type inline.
- `<div>` : Balise générique de type block.

---
title: Liste exhaustive des balises
---

## Balises de premier niveau

Les balises de premier niveau sont essentielles pour la structuration de votre document HTML. Elles définissent les éléments fondamentaux de votre page web.

`<html>` : La balise `<html>` est la balise principale de toutes les pages web. Elle englobe l'ensemble du contenu de votre page et indique au navigateur qu'il s'agit d'un document HTML.

!!! exemple "balise `<html>`"

    ```html
    <html>
        <!-- Contenu de la page -->
    </html>
    ```

`<head>` : La balise `<head>` est utilisée pour définir l'en-tête de la page. Elle contient des informations importantes sur la page, telles que les métadonnées, les liens vers des feuilles de style CSS et des scripts JavaScript.
  
!!! exemple "balise `<head>`"

    ```html
    <head>
        <!-- Éléments d'en-tête -->
    </head>
    ```

`<body>` : La balise `<body>` enveloppe le contenu principal de votre page. Tout ce qui doit être affiché à l'écran, comme le texte, les images et les liens, doit être placé à l'intérieur de la balise `<body>`.

!!! exemple "balise `<body>`"

    ```html
    <body>
        <!-- Contenu principal de la page -->
    </body>
    ```

Ces balises de premier niveau définissent la structure de base de votre document HTML, ce qui permet au navigateur de l'interpréter correctement et d'afficher son contenu de manière cohérente pour les utilisateurs.

## Balises d'en-tête

Les balises d'en-tête sont utilisées pour inclure divers éléments essentiels dans une page HTML, elles sont à placer dans la section `<head>`.

### Liaison avec une feuille de style

- `<link />` : Utilisée pour lier une feuille de style externe à la page HTML.

!!! exemple "Liaison avec une feuille de style"

    ```html
    <link rel="stylesheet" href="styles.css" />
    ```

### Métadonnées de la page web

- `<meta />` : Utilisée pour spécifier diverses métadonnées de la page web, telles que l'encodage des caractères, les mots-clés et la description.

!!! exemple "Métadonnées de la page web"

    ```html
    <meta charset="UTF-8" />
    <meta name="keywords" content="HTML, CSS, JavaScript" />
    <meta name="description" content="Une description de la page web." />
    ```

### Code JavaScript

- `<script>` : Utilisée pour inclure du code JavaScript dans la page HTML.

!!! exemple "Code JavaScript"

    ```html
    <script src="script.js"></script>
    ```

### Code CSS

- `<style>` : Utilisée pour inclure du code CSS directement dans la page HTML.

!!! exemple "Code CSS"

    ```html
    <style>
    /* Votre code CSS ici */
    </style>
    ```

### Titre de la page

- `<title>` : Utilisée pour définir le titre de la page, qui s'affiche dans la barre de titre du navigateur.

!!! exemple "Titre de la page"

    ```html
    <title>Titre de la page</title>
    ```

## Balises de structuration du texte

### Abréviations

Les balises `<abbr>` sont utilisées pour indiquer une abréviation ou un acronyme et fournir une explication complète au survol de la souris.

!!! exemple "Abréviations"

    === "Code source"
        
        ```html
        <p><abbr title="World Health Organization">WHO</abbr> est une organisation mondiale de la santé.</p>
        ```

    === "Rendu navigateur"
        
        <p><abbr title="World Health Organization">WHO</abbr> est une organisation mondiale de la santé.</p>


### Citations

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


### Citations du titre

La balise `<cite>` est utilisée pour représenter le titre d'une œuvre ou d'un événement.

!!! exemple "Citations du titre"

    === "Code source"
        
        ```html
        <cite>Le Seigneur des Anneaux</cite> est un roman de J.R.R. Tolkien.
        ```

    === "Rendu navigateur"
        
        <cite>Le Seigneur des Anneaux</cite> est un roman de J.R.R. Tolkien.


### Indices et Exposants

- `<sub>` est utilisé pour mettre en indice.
- `<sup>` est utilisé pour mettre en exposant.

!!! exemple "Indices et Exposants"

    === "Code source"
        
        ```html
        H<sub>2</sub>O est de l'eau.
        2<sup>3</sup> est égal à 8.
        ```

    === "Rendu navigateur"
        
        H<sub>2</sub>O est de l'eau.
        2<sup>3</sup> est égal à 8.

### Titres de différents niveaux

Les balises `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` sont utilisées pour définir les niveaux de titre dans une page HTML.

!!! exemple "Titres de différents niveaux"

    === "Code source"
        
        ```html
        <h1>Titre de niveau 1</h1>
        <h2>Titre de niveau 2</h2>
        <h3>Titre de niveau 3</h3>
        <h4>Titre de niveau 4</h4>
        <h5>Titre de niveau 5</h5>
        <h6>Titre de niveau 6</h6>
        ```

    === "Rendu navigateur"
        
        <h1>Titre de niveau 1</h1>
        <h2>Titre de niveau 2</h2>
        <h3>Titre de niveau 3</h3>
        <h4>Titre de niveau 4</h4>
        <h5>Titre de niveau 5</h5>
        <h6>Titre de niveau 6</h6>

### Images

La balise `<img>` est utilisée pour afficher une image sur une page web.

!!! exemple "Image"

    === "Code source"
        
        ```html
        <img src="image.jpg" alt="Description de l'image" />
        ```

    === "Rendu navigateur"
        
        <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Description" style="display:block;margin:auto;width:250px;"/>


### Mise en valeur visuelle

La balise `<mark>` est utilisée pour mettre en valeur visuellement un texte, généralement en le surlignant.

!!! exemple "Mise en valeur visuelle"

    === "Code source"
        
        ```html
        <p>Le mot <mark>important</mark> est surligné.</p>
        ```

    === "Rendu navigateur"
        
        <p>Le mot <mark>important</mark> est surligné.</p>

### Mise en valeur forte et faible

- `<strong>` est utilisé pour mettre en valeur un texte en gras, indiquant une importance.
- `<em>` est utilisé pour mettre en valeur un texte en italique, indiquant une emphase.

!!! exemple "Mise en valeur forte et faible"

    === "Code source"
        
        ```html
        <p>
            <strong>Ceci est en gras.</strong>
        </p>
        <p>
            <em>Ceci est en italique.</em>
        </p>
        ```

    === "Rendu navigateur"
        
        <p>
            <strong>Ceci est en gras.</strong>
        </p>
        <p>
            <em>Ceci est en italique.</em>
        </p>

### Figures et Descriptions

- `<figure>` est utilisé pour encapsuler une figure, comme une image ou du code.
- `<figcaption>` est utilisé pour fournir une description de la figure.

!!! exemple "Figures et Descriptions"

    === "Code source"
        
        ```html
        <figure>
            <img src="asset/mkdocs.jpg" alt="Description" style="display:block;margin:auto;width:250px;"/>
            <figcaption>Description de la figure</figcaption>
        </figure>
        ```

    === "Rendu navigateur"
        
        <figure>
            <img src="figure.jpg" alt="Description de la figure" />
            <figcaption>Description de la figure</figcaption>
        </figure>

### Médias

- `<audio>` est utilisé pour intégrer des fichiers audio.
- `<video>` est utilisé pour intégrer des fichiers vidéo.
- `<source>` est utilisé pour spécifier les formats possibles pour les balises `<audio>` et `<video>`.

!!! exemple "Médias"

    === "Code source"
        
        ```html
        <audio controls>
            <source src="audio.mp3" type="audio/mpeg" />
        </audio>
        
        <video controls>
            <source src="video.mp4" type="video/mp4" />
        </video>
        ```

    === "Rendu navigateur"
        
        <audio controls>
            <source src="audio.mp3" type="audio/mpeg" />
        </audio>
        
        <video controls>
            <source src="video.mp4" type="video/mp4" />
        </video>

### Liens hypertexte

La balise `<a>` est utilisée pour créer des liens hypertexte vers d'autres pages web ou ressources.

!!! exemple "Liens hypertexte"

    === "Code source"
        
        ```html
        <a href="https://www.example.com">Lien hypertexte</a>
        ```

    === "Rendu navigateur"
        
        <a href="https://www.example.com">Lien hypertexte</a>

### Retour à la ligne, Paragraphe et Ligne de séparation

- `<br />` est utilisé pour insérer un retour à la ligne.
- `<p>` est utilisé pour définir un paragraphe.
- `<hr />` est utilisé pour insérer une ligne de séparation horizontale.

!!! exemple "Retour à la ligne, Paragraphe et Ligne de séparation"

    === "Code source"
        
        ```html
        <p>Ceci est un paragraphe.</p>
        <p>Un autre paragraphe.</p>
        <hr />
        ```

    === "Rendu navigateur"
        
        <p>Ceci est un paragraphe.</p>
        <p>Un autre paragraphe.</p>
        <hr />

### Adresse de contact

La balise `<address>` est utilisée pour afficher des informations de contact.

!!! exemple "Adresse de contact"

    === "Code source"
        
        ```html
        <address>
            John Doe<br />
            john@example.com<br />
            +1 (123) 456-7890
        </address>
        ```

    === "Rendu navigateur"
        
        <address>
            John Doe<br />
            john@example.com<br />
            +1 (123) 456-7890
        </address>

### Texte supprimé et inséré

- `<del>` est utilisé pour indiquer un texte supprimé.
- `<ins>` est utilisé pour indiquer un texte inséré.

!!! exemple "Texte supprimé et inséré"

    === "Code source"
        
        ```html
        <p>
            <del>Texte supprimé</del>
        </p>
        <p>
            <ins>Texte inséré</ins>
        </p>
        ```

    === "Rendu navigateur"
        
        <p>
            <del>Texte supprimé</del>
        </p>
        <p>
            <ins>Texte inséré</ins>
        </p>

### Définition

La balise `<dfn>` est utilisée pour définir un terme ou une expression.

!!! exemple "Définition"

    === "Code source"
        
        ```html
        <p>
            <dfn>HTML</dfn> signifie HyperText Markup Language.
        </p>
        ```

    === "Rendu navigateur"
        
        <p>
            <dfn>HTML</dfn> signifie HyperText Markup Language.
        </p>

### Code clavier et Barre de progression

- `<kbd>` est utilisé pour indiquer un code que le visiteur doit taper.
- `<progress>` est utilisé pour afficher une barre de progression.

!!! exemple "Code clavier et Barre de progression"

    === "Code source"
        
        ```html
        <p>Tapez <kbd>Ctrl+C</kbd> pour copier le texte.</p>
        <progress value="50" max="100">50%</progress>
        ```

    === "Rendu navigateur"
        
        <p>Tapez <kbd>Ctrl+C</kbd> pour copier le texte.</p>
        <progress value="50" max="100">50%</progress>

### Date ou heure

La balise `<time>` est utilisée pour afficher une date ou une heure.

!!! exemple "Date ou heure"

    === "Code source"
        
        ```html
        <p>La réunion aura lieu à <time datetime="2024-02-05T09:00">9:00 AM</time>.</p>
        ```

    === "Rendu navigateur"
        
        <p>La réunion aura lieu à <time datetime="2024-02-05T09:00">9:00 AM</time>.</p>

### Texte sous forme de code

La balise `<pre>` est utilisée pour afficher du texte comme du code, en conservant la mise en forme et l'espacement.

!!! exemple "Texte sous forme de code"

    === "Code source"
        
        ```html
        <pre>
            function helloWorld() {
                console.log("Hello, world!");
            }
        </pre>
        ```

    === "Rendu navigateur"
        
        <pre>
            function helloWorld() {
                console.log("Hello, world!");
            }
        </pre>

Compris, je vais continuer en conservant la syntaxe que vous avez fournie. Voici la suite de la structure pour les balises de listes avec des exemples sous forme de code :

## Balises de listes

### Liste à puces, non numérotée

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

### Liste numérotée

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

### Élément de la liste à puces ou numérotée

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

### Liste de définitions

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

### Définition du terme

- `<dt>` : Utilisée pour définir le terme dans une liste de définitions. Cette balise est généralement utilisée à l'intérieur de la balise `<dl>`.

!!! exemple "Définition du terme"

    === "Code source"
        
        ```html
        <dl>
            <dt>HTML</dt>
            <dd>HyperText Markup Language</dd>
            <dt>CSS</dt>
            <dd>Cascading Style Sheets</dd>
        </dl>
        ```

    === "Rendu navigateur"
        
        <dl>
            <dt>HTML</dt>
            <dd>HyperText Markup Language</dd>
            <dt>CSS</dt>
            <dd>Cascading Style Sheets</dd>
        </dl>

## Balises de tableau

### Tableau

- `<table>` : Utilisée pour créer un tableau.

!!! exemple "Tableau"

    ```html
    <table>
        <!-- Contenu du tableau -->
    </table>
    ```

### Titre du tableau

- `<caption>` : Utilisée pour définir le titre du tableau.

!!! exemple "Titre du tableau"

    === "Code source"
        
        ```html
        <table>
            <caption>Tableau des ventes mensuelles</caption>
            <!-- Contenu du tableau -->
        </table>
        ```

    === "Rendu navigateur"
        
        <table>
            <caption>Tableau des ventes mensuelles</caption>
            <!-- Contenu du tableau -->
        </table>

### Ligne de tableau

- `<tr>` : Utilisée pour définir une ligne de tableau.

!!! exemple "Ligne de tableau"

    ```html
    <table>
        <tr>
            <!-- Contenu de la ligne -->
        </tr>
    </table>
    ```

### Cellule d'en-tête

- `<th>` : Utilisée pour définir une cellule d'en-tête dans une ligne de tableau. Cette balise est généralement utilisée dans la section de l'en-tête du tableau (`<thead>`).

!!! exemple "Cellule d'en-tête"

    === "Code source"
        
        ```html
        <table>
            <thead>
                <tr>
                    <th>Nom</th>
                    <th>Âge</th>
                </tr>
            </thead>
            <!-- Contenu du tableau -->
        </table>
        ```

    === "Rendu navigateur"
        
        <table>
            <thead>
                <tr>
                    <th>Nom</th>
                    <th>Âge</th>
                </tr>
            </thead>
            <!-- Contenu du tableau -->
        </table>

### Cellule

- `<td>` : Utilisée pour définir une cellule dans une ligne de tableau. Cette balise est généralement utilisée dans la section du corps du tableau (`<tbody>`) ou dans la section du pied du tableau (`<tfoot>`).

!!! exemple "Cellule"

    === "Code source"
        
        ```html
        <table>
            <tbody>
                <tr>
                    <td>John</td>
                    <td>30</td>
                </tr>
            </tbody>
            <!-- Contenu du tableau -->
        </table>
        ```

    === "Rendu navigateur"
        
        <table>
            <tbody>
                <tr>
                    <td>John</td>
                    <td>30</td>
                </tr>
            </tbody>
            <!-- Contenu du tableau -->
        </table>

### Section de l'en-tête du tableau

- `<thead>` : Utilisée pour définir la section de l'en-tête du tableau. Cette section contient généralement des cellules d'en-tête (`<th>`).

!!! exemple "Section de l'en-tête du tableau"

    === "Code source"
        
        ```html
        <table>
            <thead>
                <tr>
                    <th>Nom</th>
                    <th>Âge</th>
                </tr>
            </thead>
            <!-- Contenu du tableau -->
        </table>
        ```

    === "Rendu navigateur"
        
        <table>
            <thead>
                <tr>
                    <th>Nom</th>
                    <th>Âge</th>
                </tr>
            </thead>
            <!-- Contenu du tableau -->
        </table>

### Section du corps du tableau

- `<tbody>` : Utilisée pour définir la section du corps du tableau. Cette section contient généralement des cellules de données (`<td>`).

!!! exemple "Section du corps du tableau"

    === "Code source"
        
        ```html
        <table>
            <tbody>
                <tr>
                    <td>John</td>
                    <td>30</td>
                </tr>
                <tr>
                    <td>Alice</td>
                    <td>25</td>
                </tr>
            </tbody>
            <!-- Contenu du tableau -->
        </table>
        ```

    === "Rendu navigateur"
        
        <table>
            <tbody>
                <tr>
                    <td>John</td>
                    <td>30</td>
                </tr>
                <tr>
                    <td>Alice</td>
                    <td>25</td>
                </tr>
            </tbody>
            <!-- Contenu du tableau -->
        </table>

### Section du pied du tableau

- `<tfoot>` : Utilisée pour définir la section du pied du tableau. Cette section contient généralement des informations de résumé ou des totaux.

!!! exemple "Section du pied du tableau"

    === "Code source"
        
        ```html
        <table>
            <tfoot>
                <tr>
                    <td>Total</td>
                    <td>55</td>
                </tr>
            </tfoot>
            <!-- Contenu du tableau -->
        </table>
        ```

    === "Rendu navigateur"
        
        <table>
            <tfoot>
                <tr>
                    <td>Total</td>
                    <td>55</td>
                </tr>
            </tfoot>
            <!-- Contenu du tableau -->
        </table>

## Balises de formulaire

### Formulaire

- `<form>` : Utilisée pour créer un formulaire.

!!! exemple "Formulaire"

    ```html
    <form action="/traitement" method="post">
        <!-- Contenu du formulaire -->
    </form>
    ```

### Regroupement d'éléments d'un formulaire

- `<fieldset>` : Utilisée pour regrouper des éléments d'un formulaire.

!!! exemple "Regroupement d'éléments"

    ```html
    <form action="/traitement" method="post">
        <fieldset>
            <!-- Éléments du groupe -->
        </fieldset>
    </form>
    ```

### Titre d'un groupe dans un formulaire

- `<legend>` : Utilisée pour définir un titre pour un groupe de champs dans un formulaire. Cette balise est généralement utilisée à l'intérieur de la balise `<fieldset>`.

!!! exemple "Titre d'un groupe"

    === "Code source"
        
        ```html
        <form action="/traitement" method="post">
            <fieldset>
                <legend>Informations personnelles</legend>
                <!-- Éléments du groupe -->
            </fieldset>
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="/traitement" method="post">
            <fieldset>
                <legend>Informations personnelles</legend>
                <!-- Éléments du groupe -->
            </fieldset>
        </form>

### Titre d'un élément de formulaire

- `<label>` : Utilisée pour définir un titre explicatif pour un élément de formulaire, généralement associée à un champ de saisie.

!!! exemple "Titre d'un élément"

    === "Code source"
        
        ```html
        <form action="/traitement" method="post">
            <label for="nom">Nom :</label>
            <input type="text" id="nom" name="nom" />
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="/traitement" method="post">
            <label for="nom">Nom :</label>
            <input type="text" id="nom" name="nom" />
        </form>

### Champ de formulaire

- `<input />` : Utilisée pour créer un champ de formulaire, tel que champ de texte, case à cocher, bouton radio, etc.

!!! exemple "Champ de formulaire"

    === "Code source"
        
        ```html
        <form action="/traitement" method="post">
            <input type="text" id="nom" name="nom" />
            <input type="checkbox" id="souvenir" name="souvenir" />
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="/traitement" method="post">
            <input type="text" id="nom" name="nom" />
            <input type="checkbox" id="souvenir" name="souvenir" />
        </form>

### Zone de saisie multiligne

- `<textarea>` : Utilisée pour créer une zone de saisie de texte multiligne dans un formulaire.

!!! exemple "Zone de saisie multiligne"

    === "Code source"
        
        ```html
        <form action="/traitement" method="post">
            <textarea id="commentaire" name="commentaire" rows="4" cols="50"></textarea>
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="/traitement" method="post">
            <textarea id="commentaire" name="commentaire" rows="4" cols="50"></textarea>
        </form>

### Liste déroulante

- `<select>` : Utilisée pour créer une liste déroulante dans un formulaire.

!!! exemple "Liste déroulante"

    === "Code source"
        
        ```html
        <form action="/traitement" method="post">
            <select id="pays" name="pays">
                <option value="france">France</option>
                <option value="espagne">Espagne</option>
                <option value="italie">Italie</option>
            </select>
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="/traitement" method="post">
            <select id="pays" name="pays">
                <option value="france">France</option>
                <option value="espagne">Espagne</option>
                <option value="italie">Italie</option>
            </select>
        </form>

### Élément d'une liste déroulante

- `<option>` : Utilisée pour définir chaque élément de la liste déroulante. Cette balise est généralement utilisée à l'intérieur de la balise `<select>`.

!!! exemple "Élément d'une liste déroulante"

    === "Code source"
        
        ```html
        <form action="/traitement" method="post">
            <select id="pays" name="pays">
                <option value="france">France</option>
                <option value="espagne">Espagne</option>
                <option value="italie">Italie</option>
            </select>
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="/traitement" method="post">
            <select id="pays" name="pays">
                <option value="france">France</option>
                <option value="espagne">Espagne</option>
                <option value="italie">Italie</option>
            </select>
        </form>

### Groupe d'éléments d'une liste déroulante

- `<optgroup>` : Utilisée pour regrouper des éléments d'une liste déroulante. Cette balise est généralement utilisée à l'intérieur de la balise `<select>`.

!!! exemple "Groupe d'éléments d'une liste déroulante"

    === "Code source"
        
        ```html
        <form action="/traitement" method="post">
            <select id="pays" name="pays">
                <optgroup label="Europe">
                    <option value="france">France</option>
                    <option value="espagne">Espagne</option>
                    <option value="italie">Italie</option>
                </optgroup>
                <optgroup label="Asie">
                    <option value="chine">Chine</option>
                    <option value="japon">Japon</option>
                </optgroup>
            </select>
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="/traitement" method="post">
            <select id="pays" name="pays">
                <optgroup label="Europe">
                    <option value="france">France</option>
                    <option value="espagne">Espagne</option>
                    <option value="italie">Italie</option>
                </optgroup>
                <optgroup label="Asie">
                    <option value="chine">Chine</option>
                    <option value="japon">Japon</option>
                </optgroup>
            </select>
        </form>

## Balises sectionnantes

### En-tête

- `<header>` : Utilisée pour définir l'en-tête d'une section ou d'une page.

!!! exemple "En-tête"

    === "Code source"
        
        ```html
        <header>
            <h1>Titre de l'en-tête</h1>
            <p>Description de l'en-tête</p>
        </header>
        ```

    === "Rendu navigateur"
        
        <header>
            <h1>Titre de l'en-tête</h1>
            <p>Description de l'en-tête</p>
        </header>

### Liens principaux de navigation

- `<nav>` : Utilisée pour définir une section contenant les liens principaux de navigation d'une page.

!!! exemple "Liens principaux de navigation"

    === "Code source"
        
        ```html
        <nav>
            <ul>
                <li><a href="/">Accueil</a></li>
                <li><a href="/services">Services</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>
        ```

    === "Rendu navigateur"
        
        <nav>
            <ul>
                <li><a href="/">Accueil</a></li>
                <li><a href="/services">Services</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>

### Pied de page

- `<footer>` : Utilisée pour définir le pied de page d'une section ou d'une page.

!!! exemple "Pied de page"

    === "Code source"
        
        ```html
        <footer>
            <p>Copyright © 2024 MonSiteWeb</p>
        </footer>
        ```

    === "Rendu navigateur"
        
        <footer>
            <p>Copyright © 2024 MonSiteWeb</p>
        </footer>

### Section de page

- `<section>` : Utilisée pour définir une section générique d'une page, telle qu'un chapitre, un contenu distinct ou une zone thématique.

!!! exemple "Section de page"

    === "Code source"
        
        ```html
        <section>
            <h2>Section principale</h2>
            <p>Contenu de la section principale.</p>
        </section>
        ```

    === "Rendu navigateur"
        
        <section>
            <h2>Section principale</h2>
            <p>Contenu de la section principale.</p>
        </section>

### Article (contenu autonome)

- `<article>` : Utilisée pour définir un contenu autonome et auto-suffisant, tel qu'un article de blog ou une publication.

!!! exemple "Article"

    === "Code source"
        
        ```html
        <article>
            <h2>Titre de l'article</h2>
            <p>Contenu de l'article.</p>
        </article>
        ```

    === "Rendu navigateur"
        
        <article>
            <h2>Titre de l'article</h2>
            <p>Contenu de l'article.</p>
        </article>

### Informations complémentaires

- `<aside>` : Utilisée pour définir des informations complémentaires qui sont généralement en dehors du flux principal de contenu.

!!! exemple "Informations complémentaires"

    === "Code source"
        
        ```html
        <aside>
            <h3>À ne pas manquer</h3>
            <ul>
                <li>Actualités</li>
                <li>Événements à venir</li>
            </ul>
        </aside>
        ```

    === "Rendu navigateur"
        
        <aside>
            <h3>À ne pas manquer</h3>
            <ul>
                <li>Actualités</li>
                <li>Événements à venir</li>
            </ul>
        </aside>

Bien sûr, voici la continuation de la structure pour les balises génériques, en conservant la syntaxe que vous avez fournie :

## Balises génériques

### Balise générique de type inline

- `<span>` : Utilisée pour définir une balise générique de type inline, souvent utilisée pour appliquer des styles ou des scripts à une portion de texte ou de contenu.

!!! exemple "Balise générique de type inline"

    === "Code source"
        
        ```html
        <p>Ceci est un <span style="color: blue;">texte en bleu</span>.</p>
        ```

    === "Rendu navigateur"
        
        <p>Ceci est un <span style="color: blue;">texte en bleu</span>.</p>

### Balise générique de type block

- `<div>` : Utilisée pour définir une balise générique de type block, souvent utilisée pour créer des conteneurs ou des sections de contenu qui occupent toute la largeur disponible.

!!! exemple "Balise générique de type block"

    === "Code source"
        
        ```html
        <div>
            <h2>Section importante</h2>
            <p>Contenu de la section importante.</p>
        </div>
        ```

    === "Rendu navigateur"
        
        <div>
            <h2>Section importante</h2>
            <p>Contenu de la section importante.</p>
        </div>

Ces balises génériques `<span>` et `<div>` sont polyvalentes et peuvent être utilisées pour envelopper du contenu de manière à appliquer des styles, des scripts ou pour structurer le contenu de la page en utilisant des CSS.

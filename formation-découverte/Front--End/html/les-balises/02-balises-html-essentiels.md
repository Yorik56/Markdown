---
title: Les balises essentielles
---

## Balises de titre (Hn)

Les balises `<h1>` à `<h6>` sont utilisées pour définir les niveaux de titre dans une page HTML.

!!! exemple "Titres"
    
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
        
## Paragraphe

La balise `<p>` est utilisée pour définir un paragraphe de texte dans le HTML.

!!! exemple "Paragraphe"

    === "Code source"
        
        ```html
        <p>Ceci est un exemple de paragraphe.</p>
        ```

    === "Rendu navigateur"
        
        <p>Ceci est un exemple de paragraphe.</p>


## Liens hypertextes

La balise `<a>` est utilisée pour créer des liens hypertextes dans le HTML.

!!! exemple "Liens hypertextes"

    === "Code source"
        
        ```html
        <a href="https://exemple.com">Lien vers un site</a>
        ```

    === "Rendu navigateur"
        
        <a href="https://exemple.com">Lien vers un site</a>

## Image

La balise `<img>` est utilisée pour insérer des images dans une page web.

!!! exemple "Image"

    === "Code source"
        
        ```html
        <img src="image.jpg" alt="Description de l'image" />
        ```

    === "Rendu navigateur"
        
        <img src="https://raw.githubusercontent.com/squidfunk/mkdocs-material/master/.github/assets/logo.svg" alt="Description" style="display:block;margin:auto;width:250px;"/>


## Liste non ordonnée

La balise `<ul>` est utilisée pour créer une liste non ordonnée dans le HTML.

!!! exemple "Liste non ordonnée"

    === "Code source"
        
        ```html
        <ul>
            <li>Élément de liste 1</li>
            <li>Élément de liste 2</li>
        </ul>
        ```

    === "Rendu navigateur"
        
        <ul>
            <li>Élément de liste 1</li>
            <li>Élément de liste 2</li>
        </ul>


## Formulaire interactif

La balise `<form>` est utilisée pour créer un formulaire interactif dans une page web.

!!! exemple "Formulaire interactif"

    === "Code source"
        
        ```html
        <form action="traitement.php" method="post">
            <label for="nom">Nom :</label>
            <input type="text" id="nom" name="nom" />
            <input type="submit" value="Envoyer" />
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="traitement.php" method="post">
            <label for="nom">Nom :</label>
            <input type="text" id="nom" name="nom" />
            <input type="submit" value="Envoyer" />
        </form>


## Division

La balise `<div>` est utilisée pour diviser et structurer le contenu d'une page web.

!!! exemple "Division"

    === "Code source"
        
        ```html
        <div>
            <p>Contenu dans une division.</p>
        </div>
        ```

    === "Rendu navigateur"
        
        <div>
            <p>Contenu dans une division.</p>
        </div>
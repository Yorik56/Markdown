---
title: Les attributs HTML
---

## href

Rôle: Spécifie l'URL de destination pour un lien hypertexte.
Utilisé dans: Balise `<a>`.

!!! exemple "Lien hypertexte"

    === "Code source"
        
        ```html
        <a href="https://example.com">Lien vers un site</a>
        ```

    === "Rendu navigateur"
        
        <a href="https://example.com">Lien vers un site</a>

## src

Rôle: Spécifie l'emplacement de la source (URL) d'un élément, comme une image.
Utilisé dans: Balise `<img>`, `<script>`, `<iframe>`, etc.

!!! exemple "Image"

    === "Code source"
        
        ```html
        <img src="image.jpg" alt="Description de l'image" />
        ```

    === "Rendu navigateur"
        
        <img src="image.jpg" alt="Description de l'image" />

## alt

Rôle: Fournit un texte alternatif décrivant l'image lorsque celle-ci ne peut pas être affichée.
Utilisé dans: Balise `<img>`.

!!! exemple "Image"

    === "Code source"
        
        ```html
        <img src="image.jpg" alt="Description de l'image" />
        ```

    === "Rendu navigateur"
        
        <img src="image.jpg" alt="Description de l'image" />

## id

Rôle: Spécifie un identifiant unique pour un élément HTML.
Utilisé dans: Toutes les balises HTML.

!!! exemple "Paragraphe"

    === "Code source"
        
        ```html
        <p id="paragraphe1">Ceci est un paragraphe.</p>
        ```

    === "Rendu navigateur"
        
        <p id="paragraphe1">Ceci est un paragraphe.</p>

## name

Rôle: Spécifie le nom d'un élément HTML, utilisé dans les formulaires et pour la sélection côté serveur.
Utilisé dans: Balises `<input>`, `<select>`, `<textarea>`, etc.

!!! exemple "Formulaire"

    === "Code source"
        
        ```html
        <input type="text" name="username" />
        ```

    === "Rendu navigateur"
        
        <input type="text" name="username" />

## method

Rôle: Spécifie la méthode de requête HTTP utilisée lors de l'envoi d'un formulaire.
Utilisé dans: Balise `<form>`.

!!! exemple "Formulaire"

    === "Code source"
        
        ```html
        <form action="submit.php" method="post">
            <!-- Contenu du formulaire -->
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="submit.php" method="post">
            <!-- Contenu du formulaire -->
        </form>

## action

Rôle: Spécifie l'URL où les données du formulaire seront envoyées lors de la soumission.
Utilisé dans: Balise `<form>`.

!!! exemple "Formulaire"

    === "Code source"
        
        ```html
        <form action="submit.php" method="post">
            <!-- Contenu du formulaire -->
        </form>
        ```

    === "Rendu navigateur"
        
        <form action="submit.php" method="post">
            <!-- Contenu du formulaire -->
        </form>

## for

Rôle: Spécifie quel champ de formulaire est associé à une étiquette.
Utilisé dans: Balise `<label>`.

!!! exemple "Formulaire"

    === "Code source"
        
        ```html
        <label for="nom">Nom :</label>
        <input type="text" id="nom" name="nom" />
        ```

    === "Rendu navigateur"
        
        <label for="nom">Nom :</label>
        <input type="text" id="nom" name="nom" />

## type

Rôle: Spécifie le type de champ d'un élément `<input>`.
Utilisé dans: Balise `<input>`.

!!! exemple "Formulaire"

    === "Code source"
        
        ```html
        <input type="text" />
        ```

    === "Rendu navigateur"
        
        <input type="text" />

## value

Rôle: Spécifie la valeur initiale d'un champ de formulaire.
Utilisé dans: Balise `<input>`, `<button>`.
    
!!! exemple "Formulaire"

    === "Code source"
        
        ```html
        <input type="submit" value="Envoyer" />
        ```

    === "Rendu navigateur"
        
        <input type="submit" value="Envoyer" />

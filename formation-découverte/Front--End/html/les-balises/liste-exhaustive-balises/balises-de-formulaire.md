---
title: Balises de formulaire
---

## Formulaire

- `<form>` : Utilisée pour créer un formulaire.

!!! exemple "Formulaire"

    ```html
    <form action="/traitement" method="post">
        <!-- Contenu du formulaire -->
    </form>
    ```

## Regroupement d'éléments d'un formulaire

- `<fieldset>` : Utilisée pour regrouper des éléments d'un formulaire.

!!! exemple "Regroupement d'éléments"

    ```html
    <form action="/traitement" method="post">
        <fieldset>
            <!-- Éléments du groupe -->
        </fieldset>
    </form>
    ```

## Titre d'un groupe dans un formulaire

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

## Titre d'un élément de formulaire

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

## Champ de formulaire

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

## Zone de saisie multiligne

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

## Liste déroulante

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

## Élément d'une liste déroulante

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

## Groupe d'éléments d'une liste déroulante

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
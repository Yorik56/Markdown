---
title: Balises sectionnantes
---

## En-tête

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

## Liens principaux de navigation

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

## Pied de page

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

## Section de page

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

## Article (contenu autonome)

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

## Informations complémentaires

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

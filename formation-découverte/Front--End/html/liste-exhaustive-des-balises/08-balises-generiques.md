---
title: Balises génériques
---

## Balise générique de type inline

- `<span>` : Utilisée pour définir une balise générique de type inline, souvent utilisée pour appliquer des styles ou des scripts à une portion de texte ou de contenu.

!!! exemple "Balise générique de type inline"

    === "Code source"
        
        ```html
        <p>Ceci est un <span style="color: blue;">texte en bleu</span>.</p>
        ```

    === "Rendu navigateur"
        
        <p>Ceci est un <span style="color: blue;">texte en bleu</span>.</p>

## Balise générique de type block

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
# Documentation sur les Unités CSS

Les unités CSS permettent de définir les dimensions et les longueurs dans les feuilles de style. Voici quelques-unes des unités couramment utilisées :

- `px` : Pixels, unité de mesure fixe.
- `em` : Relatif à la taille de la police de l'élément parent.
- `rem` : Relatif à la taille de la police de la racine (élément `html`).
- `%` : Pourcentage, relatif à la taille de l'élément parent.
- `vw` : Largeur de la fenêtre visible (viewport) en pourcentage.
- `vh` : Hauteur de la fenêtre visible (viewport) en pourcentage.
- `vmin` : Le plus petit entre vw et vh.
- `vmax` : Le plus grand entre vw et vh.
- `cm`, `mm`, `in`, `pt`, `pc` : Unités de mesure absolues pour l'impression.
- `ex` : Hauteur de la lettre "x" de la police courante.
- `ch` : Largeur d'un caractère "0" de la police courante.

Exemple d'utilisation :
```css
div {
  width: 200px;
  font-size: 1.2em;
  margin: 2rem;
  padding: 10%;
}

Exercice 1 : Calcul de distance pour 3 colonnes
Observez le code CSS ci-dessous :

```css
.col1 {
    border: 2px solid blue;
    float: left;
    width: 200px;
}

.col2 {
    border: 2px solid black;
    float: left;
    margin-left: 10px;
    width: 200px;
}

.col3 {
    border: 2px solid black;
    margin-left: 428px;
}
```

Pourquoi un margin-left de 428 px donne une distance de 10 px entre la colonne 2 et 3 ?

Cela donne cette distance, car le margin-left est calculé à partir du bord gauche de la fenêtre.
Il faut donc y ajouter les 2 * 200 px de largeur des blocs, ainsi que les 4 * 2 px des bordures des blocs.

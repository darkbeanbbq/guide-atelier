# Colorier des planches de bande dessinée sur ordinateur

[retour à la liste des tutos](faire.md)

![--état de l'écriture--](../img/balise_orange.png) *en construction*

![--image titre--]

Donner vie et une touche personnel à des planches de bande dessinées déjà scannées.

```
durée : 30 minutes à 1 heure
```

## [préparation de l'atelier] scanner et nettoyage des planches :
C'est une partie qui prend un peu de temps mais l'idée c'est de constituer une bibliothèque de planches pour de futurs ateliers.

Pour avoir une bon résultat de scan il faut des bandes dessinées en couleur au trait noir ou carrément en noir et blanc.
[--photo bd trait noir scannée puis seuil--] [--photo bd traits colorés scannée puis seuil--]

- Scanner à 300ppi ou plus
- extraire le tracé de la bande dessinée
  - filtre > ajuster > seuil
  - si image à couleurs, besoin de de faire deux couche (une pour retirer les couleurs clairs et une pour les sombres)
  - nettoyage à la main si besoin
- filtre > couleurs > couleur vers alpha (pour passer le blanc en transparent et n'avoir que le tracé)
- créer un calque en dessous et le peindre en blanc (pour faire l'arrière plan)
- créer un calque vide entre les deux (celui où nous allons ajouter la couleur)

[--image du setup des calques--]


## ajouter de la couleur :
(voir [tuto colorisation sur krita](../faire/colorisation.md)...)
peindre (pinceau)
remplir (pot de peinture)

## techniques
utilisation de plusieurs calques (pour séparer des éléments de plans différents)
opacité réduite pour effet de pinceau
type de pinceaux différents pour style et texture
calque séparer pour ajouter ombres et éclats de lumiere
changer la couleur des traits de la BD

## conseils et contraintes intéressantes
n'utiliser qu'une palette réduite de couleur et faire comme contrainte (ex: jaune seulement)

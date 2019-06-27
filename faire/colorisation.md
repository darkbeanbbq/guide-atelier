# Colorisation de dessins sur ordinateur

[retour à la liste des tutos](faire.md)

![--état de l'écriture--](/imgplaceholder/balise etat vert rond.png) *à jour*

![--image titre--](/faire/img/colorisation/krita colorisation pot de peinture.gif)

Colorier son dessin sur ordinateur c'est super simple.

```
durée : 30 minutes à 1 heure
```



**Les étapes :**

[TOC]

Nous allons voir **deux techniques différentes pour ajouter de la couleur** à nos dessins sur Krita. **Une méthode simple et rapide et une méthode qui permet plus de précision**.

N'importe quel autre logiciel de dessin devrait pouvoir faire la même chose. La méthode reste la même.



## Avoir une idée et la dessiner

Il  suffit d'une idée simple et de faire un dessin. Pour la méthode de  colorisation simple et rapide avoir un dessin avec des formes fermées.

**Pour avoir un meilleur résultat lors de la numérisation avoir un trait propre et au feutre noir.**

## Numériser son dessin

Utiliser le scanner pour numériser son dessin ([voir tuto](faire/colorisation.md)).



## Régler le contraste

Ouvrir l'image dans Krita.

Si elle n'est pas dans le bon sens, aller dans `Image` puis `Tourner`.

![--tourner image--](faire/img/colorisation/krita image tourner.png)



Pour  que ce soit plus facile de travailler notre dessin sur ordinateur nous  allons régler le contraste pour bien faire ressortir les traits.

![--seuil menu--](faire/img/colorisation/krita colorisation seuil entoure.png)



Puisque  le dessin était au feutre bleu (et pas noir comme recommandé plus haut)  il est plus difficile pour l'ordinateur de bien faire le contraste.

On pourrait baisser le seuil pour avoir moins de traces autour du dessin, mais le dessin ne serait pas aussi net.

![--fenetre seuil--](faire/img/colorisation/krita colorisation seuil fenetre entoure.png)



On va donc devoir un peu nottoyer le dessin.

![--correction post seuil--](faire/img/colorisation/krita colorisation seuil imperfections.png)



Utiliser l'outil pinceau et sélectionner un réglage de pinceau dans le menu de préréglage de brosses.

Les  couleurs du pinceau sont celles dans les deux petits carrés dans la  barre de menu. Celle de gauche (ici le noir) est la principale,  c'est-à-dire celle avec laquelle on va dessiner. L'autre est la  secondaire pour avoir une autre couleur facile d'accès. Pour les échanger cliquer sur la petite fléche ou la touche `X`.

![--pinceau blanc pour effacer imperfection--](faire/img/colorisation/krita colorisation pinceau noir blanc entoure.png)



Après  avoir colorier les imperfections du dessin en blanc voici à quoi  ressemble le résultat. Il ne reste plus qu'à ajouter la couleur !

![--dessin nettoyé--](faire/img/colorisation/krita colorisation dessin propre.png)



## Ajouter de la couleurs à son dessin

Comme dit tout en haut ici nous allons voir deux technique pour colorier nos dessin.

La première méthode (simple et rapide) utilise l'outil *pot de peinture* et la deuxième utilise le principe des *calques* ainsi que d'autres petites astuces qui demandent plus de temps.



#### Simple et rapide : le pot de peinture

L'outil  pot de peinture fonctionne de la manière suivante : quand on clique  quelque part, la couleur part dans tout les sens et va partout tant que  quelque chose ne l'arrête pas. C'est pour ça que pour cette méthode il est nécessaire d'avoir des  formes fermées.



Sélectionner l'outil *pot de peinture* dans la barre d'outils.

![--outil pot de peinture--](faire/img/colorisation/krita colorisation pot de peinture entoure.png)



Pour choisir un couleur utiliser le *sélecteur de couleur* ou cliquer sur les petits carrés des couleurs primaire et secondaire mentionnés plus haut.

Dans le *sélecteur de couleur* : choisir la couleur en cliquant dans le cercle et cliquer dans le triangle pour la rendre plus intense, foncée ou claire.

![--selecteur de couleur--](faire/img/colorisation/krita colorisation selecteur couleur.png)



Ensuite il suffit juste de cliquer dans les formes à remplir de couleur.

![--utilisation du pot de peinture--](faire/img/colorisation/krita colorisation pot de peinture.gif)



On utilise la même technique pour coloriser le reste du dessin.

![--colorisation terminée--](faire/img/colorisation/krita colorisation pot de peinture couleur 2.png)



#### Précision : l'utilisation des calques

Ici nous allons utiliser les *calques* pour séparer notre dessin, la couleur et le fond sur plusieurs couches.



On  prend un qutre dessin et on utilise le filtre seuil pour avoir une  image en noir et blanc comme plus haut. Comme nous allons pas utiliser  l'outil *pot de peinture* on peut utiliser un dessin avec des formes ouvertes.

![--dessin propre--](faire/img/colorisation/krita colorisation dessin propre 2.png)



On veut isoler notre tracé (en noir) sur un calque. Il faut remplacer le blanc par du transparent, pour faire cela aller dans `Filtre` puis `Couleurs` et `Couleur vers alpha`.

![--couleur vers alpha--](faire/img/colorisation/krita colorisation couleur vers alpha.png)



On voit un aperçu du résultat. Cliquer sur OK.

![--fenetre couleur vers alpha--](faire/img/colorisation/krita colorisation couleur vers alpha fenetre.png)



Créer d'autres *calques* pour la couleur et le fond. Pour ajouter un calque utiliser le bouton `+` et pour les déplacer utiliser les boutons fléches. Double clic ou clic droit pour les renommer.

![--mise en place des calques--](faire/img/colorisation/krita colorisation creation calque.gif)

L'ordre des calques est important. Celui qui est en haut est au dessus, c'est pour ça qu'on met le fond en dessous du reste.



Bien  s'assurer d'avoir le calque "couleur" de sélectionné avant de colorier,  sinon ça colorie sur les autres calques (notre dessin ou le fond).

![--calque couleur--](faire/img/colorisation/krita colorisation calque couleur.png)



Sélectionner l'outil pinceau et choisir le préréglage qui vous convient.

![--peindre sur le calque couleur--](faire/img/colorisation/krita colorisation calque couleur 1.gif)



Pour voir à quoi ressemble le calque couleur il on peut cacher le calque où se trouve notre dessin en cliquant sur l'oeil.

![--calque couleur--](faire/img/colorisation/krita colorisation calque couleur 2.gif)



Si on déborde ou fait des erreurs il suffit de les gommer. Il suffit d'activier le *mode gomme* dans la barre de menu ou en appuyant sur la touche `E`. Pour retourner en *mode dessin* il faut re-cliquer sur l'icone dans la barre de menu ou réappuyer sur `E`.

![--calque couleur gomme--](faire/img/colorisation/krita colorisation calque couleur gomme.gif)



On continue en restant sur le calque couleur et on ajouter toutes les couleurs qu'il nous faut pour donner vie à notre dessin.

*Astuce : savoir d'où arrive la lumière pour savoir où colorier l'ombre.*

![--calque couleur terminé--](faire/img/colorisation/krita colorisation calque couleur 3.gif)



Un peu de couleur en fond et **voilà le dessin terminé**.

![--dessin terminé--](faire/img/colorisation/krita colorisation 2.png)

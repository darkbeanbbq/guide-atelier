# Vectoriser une image dans Inkscape

[retour au guide des outils](outils.md)

![--état de l'écriture--](imgplaceholder/balise etat vert rond.png) *à jour*

 

Si besoin voir le [tuto inkscape officiel de vectorisation](https://inkscape.org/fr/doc/tutorials/tracing/tutorial-tracing.html)

 

## Importer l'image

Glisser-déposer l'image sur la plan de travail ou l'importer via `ficher > importer...`

Une fenêtre apparait, cliquer sur valider.

![--importation image--](outils/img/inkscape/inkscape importation.png)

![--importation--](outils/img/inkscape/inkscape importation2.png)

 

## Vectorisation

Sélectionner l'image à vectoriser et aller dans `Chemin` puis `Vectoriser un objet matriciel...` (qui se traduit en "transformer une image faite de pixels en courbes").

![--vectorisation fenêtre--](outils/img/inkscape/inkscape vectorisation 1.png)

 

Une fenêtre apparait. Il se peut qu'on ne voit rien comme ci-dessus.

![--vectorisation fenêtre--](outils/img/inkscape/inkscape vectorisation 2.png)

 

Cocher `Aperçu en direct` ou cliquer sur `Mettre à jour` pour voir un aperçu du résultat de la vectorisation. (Si besoin mettre la fenêtre en plein écran)

![--vectorisation seuil de luminosité--](outils/img/inkscape/inkscape vectorisation 3.png)

 

Pour  que l'ordinateur puisse bien déterminer où traduire les pixels en  courbes , il faut l'aider à voir notre dessin clairement afin d'obtenir  un résultat qui nous convient le plus.

**Il y a plusieurs  manières de vectoriser un dessin (voir les différentes options dans  l'onglet Mode) mais nous allons nous concentrer sur la suivante :**

 

### Seuil de luminosité

La  vectorisation par seuil de luminosité consiste à transformer en plein  (noir) ce qui est au dessus du seuil, et en vide ce qui est en dessous.  Si il est trop bas on ne voit pas assez l'image, si il est trop haut on  commence à apercevoir des traces un peu partout.

Le faire varier jusqu'à avoir un résultat qui convient. (souvent entre 0,700 et 0,900)

**Remarque**  : un dessin bien contrasté (feutre noir sur feuille blanche) donnera de  meilleurs résultats lors de la vectorisation qu'un dessin trop clair  (feutre jaune sur feuille blanche).

![--vectorisation seuil de luminosité--](outils/img/inkscape/inkscape vectorisation 4.png)

 

Quand le résulat est satisfaisant cliquer sur `valider` et fermer la fenêtre de vectorisation.

On  se retrouve avec le tracé vectorisé de notre image et elle en dessous.  Il va falloir la sélectionner et la supprimer pour n'avoir plus que son  tracé vectorisé.

Prendre le tracé (en noir) et le déplacer légerement avec l'outil de sélection (touche `F1`) pour pouvoir voir et supprimer l'image d'origine.

![--image vectorisée--](outils/img/inkscape/inkscape vectorisation 5.png)

![--image vectoriée--](outils/img/inkscape/inkscape vectorisation 6.png)

 

## Nettoyage

La vectorisation n'est pas toujours parfaite, c'est pour ça que l'on doit souvent passer par une étape de nettoyage du tracé.

 

### Suppression de noeuds

Sélectionner le tracé et utiliser l'outil d'`édition de noeuds` (touche `F2`) pour supprimer les imperfections et éléments vectorisés que nous ne voulons pas.

![--outil edition de noeuds--](outils/img/inkscape/inkscape nettoyage 1.png)

Sélectionner une zone de points et les supprimer avec la touche `suppr` ou `retour arrière`.

![--sélection de zone noeuds à supprimer--](outils/img/inkscape/inkscape nettoyage 2.png)

 

Des  'formes étranges' peuvent apparaitre. Ce n'est que le tracé qui tente  de s'adapter à la nouvelle forme qu'on lui donne. Ne pas s'inquiéter et  continuer à supprimer les noeuds que l'on ne veut pas.

Si besoin, pour réajuster le tracé, utiliser les petits cercles au bout des lignes pour 'tendre' ou 'détendre' les courbes.

![--suppression noeuds explosion forme--](outils/img/inkscape/inkscape nettoyage 23.png)

 

### Retravailler / corriger le tracé

Au  delà du simple nettoyage du tracé issue d'une image scanné on peut la  retravailler : réaligner des éléments, modifier leurs tailles, séparer  des formes qui ne devrait pas être collées.

À savoir aussi que moins il y a de points, plus une courbe est lisse.

 

## Préparation pour la découpe

Pour que la découpe se passe bien il faut un tracé net et des courbes lisses.

Il  faut aussi s'assurer qu'il n'y ai bien qu'un seul tracé (et pas deux  tracés superposés) sinon la machine risque de passer plusieurs fois au  même endroit.

 

## Sauvegarder et exportation

Pour sauvegarder ou exporter son travail pour la découpe il suffit d'aller dans `fichier` puis `enregistrer sous...` . Bien sélectionner le format `.svg`, choisir un nom pour sa création et se souvenir de son emplacement.

 

Pour savoir comment découper sa création voir le [guide de la découpeuse](outils/decoupeuse.md).

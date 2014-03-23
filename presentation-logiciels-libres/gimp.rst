========================================
Retouche et montage de photos avec Gimp
========================================

----

GIMP c'est quoi ?
=================

* logiciel libre de manipulation d'**images bitmap**

`http://www.gimp.org/ <http://www.gimp.org/>`__

----

Interface
==========

* Menu
* Outils et autres fenêtres
* Zone de travail

----

Image Bitmap
============

= ensemble de points de couleurs différentes

Exemple : image 600x480

* **définition** : 600*480 = 288 000 pixels
* pour imprimer, on indique la **résolution** : 100pixels par pouce (*24cm)

TP-1a : zoom
------------

* ouvrir une image (birth ... .jpg)
* zoomer sur l'image

Ces points sont des **pixels**

----

Taille de l'image ?
===================

-  définition : 2048 x 1356
-  taille du fichier : **26,9Mo**

Un peu trop pour envoyer par mail !

TP-1b : redimensionner pour le web
----------------------------------

* *image > échelle* et taille de l'image
* choisir **800px** et valider
* exporter l'image en .jpg (et renommer le fichier)

Enregistrer le fichier (format natif : .xcf)

----

Sélectionner
============

On peut sélectionner des éléments :
par taille, par couleur, en découpant

TP-2a : Sélectionner une planète
--------------------------------

* sur Wikimedia Commons, télécharger une image de planète
   http://commons.wikimedia.org/wiki/File:The_Blue_Marble.jpg
* sélectionner une planète :
   - outil sélection cercle sur la planète
   - outil sélection par couleur, puis cliquer sur le fond noir
* la copier dans une nouvelle image :
   *Édition > copier comme > nouvelle image*

----

Les calques
===========

GIMP permet d'empiler des images dans un même fichier : **les calques**

TP-2b : Un clair de Terre
-------------------------

* Ouvrir une des images du dossier **tp-2** en tant que calque
   *fichier > ouvrir en tant que calque*
* Mettre le calque choisi sous la planète
   *Fenêtre des calques, sélectionner le calque, déplacer*
* Ajuster le cadre
   *Image > Ajuster le canevas aux calques*

Pour faire un essai avec d'autres images, on peut insérer d'autres
calques d'image, les cacher ou les rendre visibles

----

Ajouter du texte
================

Gimp peut être utile pour faire des cartes de voeux ou des tracts / flyers.

TP-2c : ajouter du texte
------------------------

* Outil texte : *couleur = blanc, taille de police = 48px*
* cliquer dans l'image
* écrire du texte "Joyeux Noël !"

C'est un nouveau calque, dont on peut modifier le contenu et les 
propriétés des caractères

----

Créer un "polaroid"
===================

En ajoutant un calque blanc supplémentaire sur le fond, on peut obtenir
un effet "polaroid"

* Augmenter la taille du canevas (1280px), puis centrer l'image sur le canevas
* Ajouter un nouveau calque rempli avec la couleur d'Arrière plan (AP)
* Mettre ce calque sous les autres images

"Voilà"

----

Jouer sur la couleur
====================

Gimp permet de retoucher la couleur des images

TP-2d : Le mont St Michel "From Mars"
-------------------------------------

* Ouvrir les réglages "Teinte-saturation

|  *Couleurs > Luminosité et Contraste*

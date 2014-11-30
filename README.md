Présentations sur le Logiciel Libre
====================================

Les présentations proposées par Toulibre.

* [L'association Toulibre](http://toulibre.github.io/slides-logiciels-libres/toulibre.html "Toulibre")
* [Le Logiciel Libre](http://toulibre.github.io/slides-logiciels-libres/logiciels-libres-et-plus-2014-1205-mediatheque-blagnac.html "Présentations sur le Logiciel Libre")
* [Découverte de Wordpress](http://toulibre.github.io/slides-logiciels-libres/wordpress.html "Découverte de Wordpress")
* [Découverte de Gimp](http://toulibre.github.io/slides-logiciels-libres/gimp-2014-0327-mediatheque-tournefeuille.html "Découverte de Gimp")

## [Forkez](https://github.com/toulibre/slides-logiciels-libres/) !! 

N'hésitez pas à reprendre pour vous ces présentations, à réutiliser le thème Toulibre.

----

## Comment ça marche

Ces présentations utilisent Landslide. Créez un virtualenv, puis installer landslide :

    mkvirtualenv landslide
    clone https://github.com/toulibre/slides-logiciels-libres.git
    cd slides-logiciels-libres
    pip install requirements.txt

Modifiez les fichiers rst (vous pouvez également utiliser md ou textile). Configurer les ``.cfg`` pour exporter la présentation dans le dossier ``www/``.
Puis lancez la commande ``landslide``:

    cd <dossier de travail> # si besoin
    landslide gimp.cfg

## Pour ce dépôt

Les présentations sont visibles sur [Github pages de ce dépôt](http://toulibre.github.io/slides-logiciels-libres/. Utilisez la commande ``ghp-import``

    ghp-import -p www/

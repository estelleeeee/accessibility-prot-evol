# Accessibilité relative des résidus et évolution protéique

## Status 
En cours d'élaboration

## Sommaire

* [Sujet](#sujet)
* [Pour démarrer](#pour-démarrer)
  * [Prérequis](#prérequis)
  * [Environnement](#environnement)
* [Contact](#contact) 

## Sujet
La structure tridimensionnelle (3D) des protéines porte leurs fonctions biologiques. Avoir accès à leur structure est un outil intéressant pour appréhender cette fonction. De la structure protéique, on regarde souvent l'accessibilité relative des résidus pour dire qu'ils sont enfouis ou accessibles (pour le drug design par exemple). Toutefois, il n'est pas simple de savoir si cette information est bien simplement conservée (ou observée) au cours de l'évolution. Ainsi, une glycine accessible ne peut pas être simplement comparée à un tryptophane accessible.  

Le principe ici est donc en partant d'un jeu de données de structures protéiques de bonne qualité, de chercher les séquences homologues (de plus en plus lointaine), de modifier ces protéines et de quantifier les potentiels changements locaux en terme d'accessibilité relative.

## Pour démarrer

### Prérequis
Ce projet nécessite l'installation de SCWRL4.0 (disponible [ici](http://dunbrack.fccc.edu/SCWRL3.php/)).

### Environnement
Création de l'environnement conda à partir du fichier *.yml* disponible.  
`conda env create -f accessibility.yml`

## Contact
Tuteur : **Alexande De Brevern** (alexandre.debrevern@univ-paris-diderot.fr)  
Tutoré : **Estelle Mariaux** (estelle.mariaux@hotmail.fr)

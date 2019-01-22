# Matrice de formes
Créer une matrice (voir [matrice.jpg](matrice.jpg)) de formes à rendre cliquable.

# Objectifs Pédagogiques
* Maitriser les fonctions _class_ sur jQuery (.addClass, .removeClass, .toggleClass, .hasClass)

# Instructions
* Reproduire la matrice de l'image. Chaque élément (rond, carré, losange) peut avoir deux états : vide (pas de fond) et plein (un fond de la couleur de votre choix)
* Ajouter un bouton permettant de passer tous les éléments de l'état vide à l'état plein
* Ajouter un bouton permettant de passer tous les éléments de l'état plein à l'état vide
* Lors du clic sur un élément _rond_, changer son état (plein vers vide ou vide vers plein)

# Améliorations
* Lors du clic sur un élément _carré_, changer son état (plein vers vide ou vide vers plein) ainsi que tous les éléments sur la même ligne (horizontalement). Attention, les éléments de la même ligne doivent avoir le même état que l'élément _carré_. Exemple : Si le _carré_ devient plein, tous les autres éléments doivent aussi devenir pleins.
* Lors du clic sur un élément _losange_, changer son état (plein vers vide ou vide vers plein) ainsi que tous les éléments situés sur la même ligne (horizontalement et sur la même colonne (verticalement). Attention, les éléments de la même ligne et de la même colonne doivent avoir le même état que l'élément _losange_. Exemple : Si le _losange_ devient plein, tous les autres éléments doivent aussi devenir pleins.

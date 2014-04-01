# Sélectionner et détourer

Les sélections sont des zones effectuées à l'aide d'outils particuliers. Les zones extérieures à la sélection ne pourront pas être modifiées. L'objectif d'une sélection ou d'un détourage est de restreindre la zone d'action des outils à une partie définie manuellement au préalable et ainsi éviter tout risque d'erreur par la suite. En quelque sorte, les sélections nous aident à ne pas déborder.

## Procédure

Les sélections sont affichées par des pointillés blancs et noirs clignotants. Cette zone ne produit rien en elle-même&nbsp;: il s'agit d'une préparation pour des actions à venir. Ainsi la procédure de base d'une sélection est composée d'une suite d'étapes régulières&nbsp;:

1.  Effectuer la sélection avec un outil de base
2.  Améliorer la sélection avec d'autres outils
3.  Agir sur le contenu de la sélection&nbsp;: dessiner, changer les couleurs, supprimer...
4.  Désélectionner à l'aide du menu _Sélection &gt; Aucune_.

# Principaux outils de sélections

Il existe plusieurs outils de sélection et il vous appartient de choisir celui qui correspond à vos objectifs et à l'image. Parmi ces outils certains sont plus régulièrement utilisés que d'autres, souvent parce que plus simples.

## Outil rectangle

L'outil _Rectangle_ est un outil très simple qui dessine des zones rectangulaires dans l'image. Tant que l'outil _Rectangle_ n'a pas été quitté, il est possible de modifier la forme et la taille du rectangle en s'approchant des angles et des côtés du rectangle et en enfonçant la souris.

## Outil Ellipse

L'outil _Ellipse_ dessine quant à lui des sélections elliptiques ou circulaires. Comme l'outil _Rectangle_, il est possible de remodifier sa forme juste après sa création.

## Outils basés sur les couleurs

L'outil _Baguette magique_ et l'outil de _Sélection par couleur_ agissent tous deux sur le même principe&nbsp;: créer une zone de sélection à partir d'une couleur choisie en cliquant sur l'image. La différence entre les deux est assez simple&nbsp;: la _Baguette_ sélectionne seulement autour de la zone où le clic a été effectué alors que l'autre va chercher la couleur dans toute l'image même si celle-ci est entrecoupée par d'autres couleurs.

Dans les deux cas, l'utilisation de l'option _Seuil_ des outils permet de définir si l'outil doit sélectionner les zones dont la couleur est très proche à la couleur choisie (seuil faible) ou très large et différente (seuil élevé, moins précis donc).

# Améliorer des sélections

L'utilisation des outils ne suffit en général pas pour arriver à un résultat satisfaisant. Il faudra alors avoir recours à quelques options ou fonctions particulières qui sont transversales à tous les outils de sélections.

## Ajouter de nouvelles zones ou en enlever

Presque tous les outils de sélection possèdent en haut de leur liste d'options, une catégorie mode dans laquelle on retrouve quelques boutons en forme de carrés qui se superposent. Les trois premiers sont les plus importants&nbsp;:

- _Mode Normal_&nbsp;: Toute nouvelle sélection faite dans ce mode viendra en remplacement de la précédente.
- _Mode Ajout_&nbsp;: Les nouvelles zones effectuées dans ce mode viendront s'ajouter aux zones déjà sélectionnées, sans les faire disparaître&nbsp;; un appui sur la touche Maj produit le même résultat.
- _Mode soustraction_&nbsp;: Les nouvelles zones effectuées dans ce mode viendront réduire les zones déjà sélectionnées, sans les faire disparaître&nbsp;; vous pouvez aussi utiliser Ctrl.

## Inverser une sélection

Il n'est pas rare que la zone à sélectionner soit complexe, alors que l'extérieur est simple (exemple&nbsp;: une fleur sur un fond de ciel bleu). Dans ce cas, il sera plus simple de sélectionner le ciel et d'inverser la sélection pour pouvoir agir sur la fleur. Pour cela&nbsp;:&nbsp;

1.  Effectuez la sélection du ciel avec l'outil de votre choix (dans notre exemple, la baguette magique devrait faire l'affaire)
2.  Utilisez le menu _Sélection&gt;Inverser_. Les pointillés restent évidemment au même endroit, mais si vous faites des changements vous verrez que c'est bien la fleur qui est maintenant affectée.


# Sélection libre au lasso

Le _Lasso_ est le formidable outil des cow-boys (et girls) de l'image. C'est un outil qui n'a rien d'automatique du tout mais qui a l'avantage de s'adapter parfaitement à vos besoins et coups de souris, ni plus ni moins. Avec l'outil _Lasso_, vous pourrez dessiner toute forme géométrique librement.

## Procédure pour dessiner un polygone

1.  Activez l'outil _Lasso_ et placez-vous sur l'image.
2.  Cliquez une première fois, déplacez la souris et cliquez ailleurs. L'outil rejoint chaque point cliqué par un segment droit.
3.  Pour retoucher à la position de certains points, placez juste votre souris dessus et bougez-les en enfonçant le bouton gauche (attention, il faut être précis !)
4.  Pour fermer votre polygone, vous pouvez soit double-cliquer, soit cliquer sur le premier point réaliser.

En général, cette méthode sera utilisée pour faire une première zone rapide qui sera ensuite améliorée avec d'autres outils de sélections.

## Procédure pour dessiner une forme libre

1.  Activez l'outil _Lasso_ et placez-vous sur l'image.
2.  Enfoncez le bouton gauche et glissez la souris sur l'image.
3.  Pour fermer la zone, revenez au premier point réalisé.

En général, cette seconde méthode sera utilisée pour suivre le contour d'un objet dans la photo.

L'utilisation de ce genre d'outil est fortement facilitée par l'utilisation d'une tablette graphique, même de premier prix.

# Suivre les contours d'un objet

Cependant lorsque les outils de détection pas couleur ne fonctionnent pas et quand les contours sont complexes et que la manipulation de la souris est trop compliquée, il est nécessaire de changer de stratégie. Le _Ciseau Intelligent_ est un outil qui va s'accrocher aux contours qu'il détecte pour nous aider à détourer une forme.

Pratiquement parlant, l'utilisateur prend en main le _Ciseau Intelligent_ un peu comme le lasso, le reste du travail est fait par l'outil.

## Procédure

1.  Activez l'outil _Ciseau Intelligent_ et dans ses options cochez la case Contour interactif.
2.  Repérez un endroit bien net sur le contour de la forme à détourer et cliquez une première fois.
3.  Déplacez la souris un peu plus loin en suivant le contour de l'objet et vous voyez apparaître le trait de sélection de l'outil.
4.  Continuez à vous déplacer tant que le contour détecté semble correct et cliquez à l'emplacement de la souris au moment où la détection est moins bonne.
5.  En cas d'oubli, vous pouvez revenir cliquer sur un trait pour créer un point et le déplacer pour améliorer le contour.
6.  Enfin, continuez de faire le tour de l'objet en cliquant par endroits (en particulier aux changements de direction du contour&nbsp;: angles...).
7.  Cliquez sur le premier point réaliser pour fermer le contour.
8.  Retouchez aux points qui sont mal positionnés.
9.  Cliquez à l'intérieur de la zone pour valider la sélection. À partir de ce moment, le contour n'est plus modifiable avec cet outil.

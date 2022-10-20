# ML_9

Construire un algorithme qui, à partir des caractéristiques géométriques d’un billet, serait capable de définir si ce dernier est un vrai ou un faux billet.

Nous avons à notre disposition six données géométriques pour chaque billet. L’algorithme devra donc être capable de prendre en entrée un fichier contenant les dimensions de plusieurs billets, et de déterminer le type de chacun d’entre eux, à partir des seules dimensions.

Nous allons mettre en concurrence deux méthodes de prédiction :

● une régression logistique classique

● un k-means, duquel seront utilisés les centroïdes pour réaliser la prédiction

Cet algorithme se devra d’être naturellement le plus performant possible pour identifier un maximum de faux billets au sein de la masse de billets analysés chaque jour.

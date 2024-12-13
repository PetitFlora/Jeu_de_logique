# Jeu_de_logique

## Règle du Jeu

Deux joueurs s’affrontent sur un plateau carré comportant n lignes et n colonnes, où n est un entier pair. Par défaut n = 8.

Chaque joueur dispose de deux types de pièces :

- Une reine qui se déplace orthogonalement ou en diagonale vers une case vide non nécessairement adjacente, mais à la condition que toutes les cases alignées entre sa position de départ et sa position d'arrivée soient vides (à l'instar d'une reine aux échecs mais sans la possibilité de prendre une éventuelle pièce adverse se situant sur la case d'arrivée).
- Une tour qui se déplace orthogonalement vers une case vide non nécessairement adjacente, mais à la condition que toutes les cases alignées entre sa position de départ et sa position d'arrivée soient vides (à l'instar d'une tour aux échecs mais sans la possibilité de prendre une éventuelle pièce adverse se situant sur la case d'arrivée).

Chaque joueur possède initialement une reine et n2//4−1 tours.


Après qu'un joueur ait déplacé l'une de ses tours selon les règles ci-dessus, des captures sont possibles. Si la position finale de la tour en question n'est ni sur la même ligne ni sur la même colonne que la reine du même joueur, ces deux pièces forment alors deux sommets d'une même diagonale d'un rectangle virtuel. Si une ou deux tours du joueur adverse sont alors situées sur un ou deux des autres sommets de ce rectangle elles sont capturées.

Cette règle de capture ne s'applique qu'après le déplacement d'une tour et non d'une reine, et seules les tours adverses peuvent être capturées et non la reine adverse.

Dès qu'un joueur n'a plus que deux pièces ou moins (au cumul de sa reine et de ses tours) il a perdu la partie.

This is a TTU university project completed by me - a battle ship game using only HTML, CSS and Javascript.

Please play the game here: http://dijkstra.cs.ttu.ee/~Kaspar.Metsa/prax3/index.html

Requirements for the game from the client(ie the teacher)
==============
- The ships only take 2 places horizontally and can't be next to each other. Diagonal touching is ok.
- If you bomb some place and it misses there will appear a picture that you missed.

* There are two different versions of this game: regular and mobile:
* Both versions use the same source code
* The mobile version has these features:
  *	Does not allow zooming in and only allows scrolling up and down, but not to right and left.
  * In mobile, the board is almost from left edge to right edge.
  * In regular version boards are next to each other, in mobile the boards are on top of each other
* There has to be a button to start the game. You must be able to press that button also while the game is lasting. In this case the game stops and starts again from being able to choose number of ships and size of board.
* At the beginning of the game, player can choose between 1-10 ships and any size of the board matrix between 3x3,4x4.. etc until..10x10. The number of ships may not be larger than the side of the matrix - 1. (For example 4x4 board may have a maximum of 3 boats). Human may choose with a button whether to place his ships randomly or by placing them manually on the board.
* The ships must be displayed with an image.
* The HTML table tags may only be used for the matrix and for nothing else.
* Ships may not touch each other by their side. Ships may touch each other by their corner.
* When human or computer miss a shot or hit a shot, that box must change somehow.
* If human or computer successfully hit a shot, then a new shot is granted until winning or until missing a shot(then it’s the other player’s turn).
* Computer may shoot the board randomly, but it may not shoot a place where it has already hit before. Same for human.
* The first move is done by human.


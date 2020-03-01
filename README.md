# myRunner
Runner game

The game is played on a board of squares, where each square is a floor or
a wall. Some floor squares contain boxes, and some floor squares are marked as
storage locations. The player is confined to the board, and may move
horizontally or vertically onto empty squares (never through walls or boxes).
The player can also move into a box, which pushes it into the square beyond.
Boxes may not be pushed into other boxes or walls, and they cannot be pulled.
The puzzle is solved when all boxes are at storage locations.

///////////////////////////RULES///////////////////////////////

If all boxes are on storage locations, the player wins and the program must return 0.
Otherwise, if none of the boxes can be moved anymore, he loses and the program must return 1.
The game must be reset by pressing the space bar.
Redimensioning the terminal must be handled. As long as the terminal is too small to display the whole
map, a centered message, asking the user to enlarge the terminal, must be displayed.
The game must be able to be played with the arrow keys (LEFT, RIGHT, UP and DOWN).
A valid map can only contains the characters SPACE, ‘\n’, ‘#’, ‘X’, ‘O’ and ‘P’.
If an invalid map is supplied, the program must exit with an error.
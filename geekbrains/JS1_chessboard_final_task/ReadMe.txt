Chessboard task

1) Create a function that generates a chessboard. Any HTML tags can be used.
Rows must be marked with numbers from 1 to 8, columns - with letters A, B, C, D, E, F, G, H.
All chess pieces must be placed according to the Chess game rules.

2) Provide a space to display cell's address when it's clicked (i.e. div). Address must be displayed 
as in the game: A1, G6 and so on. A clicked cell must be visibly different from other cells 
(have a border or a different color). When another cell is clicked the previous one must return to 
its default state.

3) Implement the option of changing the active (clicked) cell with keyboard key so that the player 
could move the active cell around the board in vertical and horisontal directions. If the active cell 
goes beyond the board border it must appear on the opposite side of the board. While moving the active 
cell update its address continuously on the display (div).

4) Implement removal of chess pieces from the board and their return on their last cell by click.
For that purpose add spaces above and under the board where removed pieces will be stored. Any piece on 
the board when clicked must move to the appropriate space for removed peices according to its color.
When the removed piece is clicked it must return to its last position.

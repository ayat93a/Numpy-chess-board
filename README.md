# Numpy-chess-board
## render out chess boards with red and blue queens on them.
Each board will have one red and one blue queen at different coordinates. In addition to displaying the board you’ll need to identify if the queens are “under attack” based on their coordinates.

## Implementation Notes
- Define a ChessBoard class
-  contain an 8x8 grid 
   - Each cell in grid  have a color represented in RGB format.
        - black = (0,0,0)
        - white = (1,1,1)
        - blue = (0,1,1)
        - red = (1,.2,0)
- `add_red`  method that accepts a row and column as input which colors corresponding cell.
- `add_blue` method that accepts a row and column as input which colors corresponding cell.
- `render` method that displays the chess board on screen with red and blue shown in correct locations.
- `is_under_attack` method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally.
    - Diagonal attacks can come from four directions. 

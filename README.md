### 15-puzzle
##Sliding puzzle that consists of a frame of numbered square tiles in random order with one tile missing.

The 15-puzzle is also called Gem Puzzle, Boss Puzzle, Game of Fifteen, Mystic Square and many others. The puzzle also exists in other sizes, particularly the smaller 8-puzzle. If the size is 3×3 tiles, the puzzle is called the 8-puzzle or 9-puzzle, and if 4×4 tiles, the puzzle is called the 15-puzzle or 16-puzzle named, respectively, for the number of tiles and the number of spaces. The object of the puzzle is to place the tiles in order by making sliding moves that use the empty space.

More details can be found in [wikipedia](https://en.wikipedia.org/wiki/15_puzzle)


## Rules

* Display the numbers as above and draw the boxes using ASCII characters.
* Allow the user to hit any of the arrow keys (up, down, left, or right).
  * If user hits say, right arrow key then the piece with a number 5 should move to the right and blank should replace the original position of 5.
  * Similarly, if down arrow key is hit, then 13 should move down and blank should replace the original position of 13.
  * If left arrow key or up arrow key is hit then no action should be taken.
* The user would continue hitting the arrow keys till the numbers aren’t arranged in ascending order.
* Keep track of the number of moves in which the user manages to arrange the numbers in ascending order.
* The user who manages it in minimum number of moves is the one who wins. 

## Notes
The program **main.c** requires **windows.h** so please run it in an environment where it is available.

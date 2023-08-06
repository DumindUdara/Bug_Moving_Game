# Bug_Moving_Game
I implement Bug Moving Game using my C knowledge with data structures and algorithms.  

In this C code, a simple bug-moving game is implemented on an 8x8 grid. The game consists of a bug represented by the character '2' and a piece of food represented by the character '4'. The bug moves in a straight line until it reaches an obstacle ('x') or the boundary of the grid. The bug can turn 90 degrees clockwise and continue moving until it reaches the food. Once the bug reaches the food, the game is won.

Here's a brief overview of the code:

The main menu is displayed, showing the initial positions of the bug and the food on the grid.

    The sense() function checks if the bug can move to the next cell in its current direction. If there is no obstacle ('x') and the cell is   within the grid boundaries, next is set to 1.
    The turn() function is called when the bug encounters an obstacle or reaches the grid's boundary. It rotates the bug's direction 90 degrees clockwise.
    The step() function moves the bug one step forward in its current direction.
    The start() function initializes the bug and food positions. The user is prompted to enter the bug's initial position (x, y) and the food's position (x, y). The positions are checked for validity, and if they are within the grid boundaries and not occupied by an obstacle, the bug and food are placed on the grid.
    The won() function checks if the bug has reached the food's position, indicating a win.
    The main loop runs until the bug reaches the food. In each iteration, the sense() function is called to check the next possible move. If the bug cannot move forward, it turns using the turn() function and tries to move again.
    After every move, the updated grid is displayed using the display_bord() function. The loop continues until the bug reaches the food.

When the bug reaches the food, the game ends, and a "Game Over" message is displayed along with "Bug ate food."

# Demostration 
![image](https://github.com/DumindUdara/Bug_Moving_Game/assets/98957798/e9a95099-1e45-4e51-b978-005c02e36b7a)


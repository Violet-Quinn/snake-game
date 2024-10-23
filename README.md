### Description:
This Snake game is a simple and fun project built using Python's `turtle` graphics library. Here’s a breakdown of how the game works:

### Objective:
The goal of the game is to control a snake that moves around the screen, "eating" food to grow longer. The game continues until the snake either collides with the wall or its own body.

### Components:
1. **Snake**: The snake starts as a small creature that you control with the arrow keys (Up, Down, Left, Right). Each time it eats food, it grows longer by adding segments to its body.
  
2. **Food**: A small object (represented by a turtle) randomly appears on the screen. When the snake's head gets close to the food, the food disappears and reappears somewhere else on the screen, and the snake grows.

3. **Scoreboard**: The scoreboard keeps track of how many pieces of food the snake has eaten. Each time the snake eats food, the score increases. If the game ends, it will display "Game Over" on the screen.

### How the Game Works:
1. The game window is set up with a size of 600x600 pixels, and the background is black.
2. The snake moves continuously in the direction you press using the arrow keys. You can control the snake's direction, but it will keep moving in that direction until you change it.
3. When the snake's head is close to the food (less than 15 units away), it eats the food, grows longer, and the score increases.
4. The game ends if:
   - The snake runs into the wall (the edges of the screen).
   - The snake runs into its own body (any of its segments).
5. If the game ends, the screen will display "Game Over," and you will need to restart the program to play again.

### Key Concepts:
- **Collision detection**: The game checks if the snake’s head is close enough to the food or if it collides with the walls or its own body.
- **Score tracking**: Each time the snake eats food, the score increases.
- **Game loop**: The game runs in a loop, continually updating the screen, moving the snake, and checking for collisions.

This is a fun project to practice basic game mechanics like movement, collision detection, and score tracking while using Python and the `turtle` module.

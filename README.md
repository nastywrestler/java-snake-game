# Java Snake Game

## Overview
This project is a classic Snake game built using Java and Swing. The game features a graphical user interface (GUI) where players control a snake to eat apples, grow in size, and avoid collisions to achieve a high score.

![Gameplay](https://github.com/gold-roger33/java-snake-game/assets/140147156/89cc52d1-b349-432c-b788-f726aebb0e41)

## Features
- **Gameplay Mechanics**: 
  - Control the snake's direction using arrow keys.
  - Randomly generated apples appear on the screen for the snake to eat.
  - The snake grows in size and the score increases with each apple eaten.
  - The speed of the snake increases for every apple eaten
  - Game-over conditions include collisions with the game boundaries or the snake's own body.
- **Score Display**: 
  - Real-time display of the current score.

  
## Technologies Used
- **Programming Language**: Java
- **GUI Framework**: Swing, AWT



### Installation
1. Clone the repository:
   
   ```bash
   git clone https://github.com/gold-roger33/java-snake-game.git

## Additional Information

You can uncomment the following lines in the code to draw grid lines for better visualization of snake movement:
[View Code Segment](https://github.com/gold-roger33/java-snake-game/blob/f4b0366b3e92af1e12674ae2bddc854fa83902cc/frame.java#L42)

```java
// uncomment the following lines
for (int i = 0; i < 600 / UNIT_SIZE; i++) {
    g.drawLine(i * UNIT_SIZE, 0, i * UNIT_SIZE, 600);  
    g.drawLine(0, i * UNIT_SIZE, 600, i * UNIT_SIZE);  
}

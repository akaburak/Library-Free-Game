# Library-Free-Game
This code contains a shooting game and the snake game. It is completely library free and operates on the matlab app-designer figure window.
Instructions: Arrow keys to move, spacebar to shoot.
There are two games available in the code which are "tanks" and "Snake".
### Tanks
- There is a simple moving mechanism that works for the main body of the tank and the bullets. Their coordinates are stored in a list, and their movement is determined by the body speed that they have. The tank have a 1/2 body speed, whereas the bullets have a 2 body speed.
- There is a list containing the enemies and a list containing the bullets. When a bullet intersects with an enemy, the enemy is destroyed.
- When the tank intersects with an enemy, it is game over.

### Snake
- The snake has a head and the tail pieces that follow it. The only coordinate that stored is the head coordinate, the tails are only the head's recent coordinates.
- When the snake's head intersects with the tails, it is game over.

### Glitches
- After choosing the game, user may have to press another location to be able to use the arrow keys.
- The KeyPress registry takes up to 100 inputs per run, so it may stop responding after some time in the game.

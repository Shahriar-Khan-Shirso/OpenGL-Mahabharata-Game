**Project Intro:**

The story of Mahabharata is one of the oldest and refined mythology to exist.This project shows a simplified version of day 1 in mahabharata.This is a very simple OpenGL project completed for the completion of Computer Graphics course(CSE 423\) in Brac.This project involves creating a 3D game in which the player plays as Arjuna, who controls a bow that can move and cast special “Divine Astras” (spells) at enemies. The game environment includes a grid, moving enemies and features such as day night modes and camera controls. The game also contains visual feedback on the player's actions and the status of the game.

**Gaming Setup:**  
 At the start of the game the player spawns at the center of the grid.

**Drawing Components:**

 The game has three crucial drawing elements.

i) The player **(1 player)**

**ii)** Enemies **(500 enemies all the time)** 

**iii)** The grid floor

**Game Features:**

1. **Player Movement**  
   * The player can cast a number of special spells that affects the enemies in various ways.  
   * The player can move forward and backward using the **W (forward)** and  **S (backward)** keys respectively.  
   * The player can move left or right using the **A (left)** and **D (right)** keys.  
      

2\.               **Camera Control**:

* The camera can be moved up and down using the **UP** and **DOWN** arrow keys.  
  * The camera can rotate(around the whole game floor) left and right using the **LEFT** and **RIGHT** arrow keys.

4\.               **Game Over and Restart**:

* The game ends when the player's (Arjuna) life is 25% left, as Arjuna makes a tactical retreat.   
   **Life reduces by 1** if an enemy arrow touches the player and enemy arrow hits the player.  
  * The **R** key is used to restart the game after it ends.  
     **Reset to Life remaining 5000, Game Score 0**

5\.               **Enemies**:

* After the enemies spawn, they will start firing at the player while moving forward slowly.  
  * New enemies keep spawning till the enemy count on the grid is 100.5 enemies spawn in  1s.  
  * The game checks for interactions between **the spells and the enemies** and the **player and the enemies**.  

 

 

6\.        **Divine Astras: 3 categories of spells depending on cooldowns.**  

1\) Brahmastra\[B in keyboard \]: Kills all enemies present on the grid.High cooldown

2\) Maya Astra\[M in keyboard\]: This spell would make the enemies kill each other for 15 seconds. High Cooldown

4\) Agni astra\[F in keyboard\]:This spell will kill 100 enemies . Low Cooldown

5\) Vajrastra\[V in keyboard\]: This spell will throw thunderbolts from the sky and kill 300 enemies. Medium Cooldown.

6\) Pawanastra\[P in keyboard\]: This spell creates a wind vortex, kills all enemies in a single line. No Cooldown.

8\) Basic shield \[H in keyboard\]:Being the skilled warrior Arjuna is,he gains immortality some time.Low cooldown.

 

7\.     	Environment: day and night toggle by pressing “T” .

 

8\. Right mouse click for pausing the game, Left mouse click for resuming the game.

9.Restart with R button.

 

To enjoy with music,install pygame in your environment after downloading from this repository.Music is taken from [https\://youtube.com/playlist?list=PL4ZwbzPaxjSnB75NU9cuvC46naZCUqyFp\&si=XUpKgH5iXOeiVy6z](https://youtube.com/playlist?list=PL4ZwbzPaxjSnB75NU9cuvC46naZCUqyFp&si=XUpKgH5iXOeiVy6z)    

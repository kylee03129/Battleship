# Battleship
This project will help you get more familiar with arrays. You will be recreating the game of battleships. A player will place 5 of their ships on a 10 by 10 grid. The computer player will deploy five ships on the same grid. Once the game starts the player and computer take turns, trying to sink each other’s ships by guessing the coordinates to “attack”. The game ends when either the player or computer has no ships left. 
Step 1: Create the ocean map
The ocean map is represented by a 10 by 10 grid of different characters. The grid is managed by a two-dimensional array. You will use this 2D array to save where the user and computerdecide to place their ships, as well as when someone tries to attack a location and misses. At the start of the game, the array will be empty and as the game is played  you willchange what is stored at each index of the array accordingly. 

Once you create your 2D array you need a way to display it to the user so they can choose coordinates. 

Step2: Deploy player's ships
Once you have your ocean map, you'll need to ask the user where they would like to place their ships. The player should deploy 5 ships. A ship will be stored in a single index of the array as a special character. To place the user's ships they need to t ell you the coordinates of where the ship should be placed and you need to update the ocean map to reflect their choices.

Step3: Deploy computer's ships
THe computer will deploy 5 ships by randomly picking X and Y coordinates. Your code is responsible for generating these locations. 

Step 4: Battle
Step 5: Game over

# Learning-journal
this documents my adventure in programming

## 2024-10-15

Today I created a learning journal.

## 2024-10-21

Planning the concept of the game and the tutorials I could make that would be useful in the future projects.

## 2024-10-22

I figured I wanted to make a game similiar to Pong game, since it contains all the fundamental scripts to make any game. To make this game more interesting, I made it a 3D project. This will later enable me to play with the theme, animations and shaders later on. I have made a script for the player and ball movement. No errors occured, a solid start.

## 2024-10-29

I have tried to make a code for the Cube moved by the computer. I want the other player to follow the ball on the x axis (move left and right). The code did not want to work at first, since I have mixed up the axis and written the computer to move on z axis instead. After figuring this out, the code went smoothly. Since I have already made the code for the player, ball , and AI movement, the next step is to write the tutorials on this and start writing the code for the restart of the game. I want the game to restart when the ball exits the platform.

## 2024-11-05 

Today I am going to work on the Game Controller, so the program knows when the player scores a goal and restarts the game.I managed to write an event that is triggered when the ball scores the goal, so that the game knows when one of the players score the goal. After having this done, I realised that my AI player is flawless and manages to get every ball, so my player is never able to score the goal. To make it more flawed, I decreased the speed of the AI, so when the ball comes from a sharp angle, it might not be able to reach the ball before it scores the goal. Started working on the UI (score count).

## 2024-11-12

Finished the UI for the score count (left and right). Also added a code that destroys the ball after reaching the goal. Had issues afterwards, because after the game restarts, the ball did not spawn back, and because there was no ball, neither of the players were able to move.
To fix this issue, I added  the ball spawn in Game Controller , so after every score, the ball spawns after 0.5f in the same position of the terrain (and it goes in a different direction).



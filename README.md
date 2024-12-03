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
To fix this issue, I added  the ball spawn in Game Controller , so after every score, the ball spawns after 0.5f in the same position of the terrain (and it goes in a different direction). There was a NullReferenceException error when the ball wasn't in the game, so in the player script I wrote some code to try to find the ball, and if it didn't exist, then the code would not run because I returned out of the function.

## 2024-11-18

Today I will continue working on my tutorial for player-movement. I have collected all the screenshots and edited them in Procreate so they seem more interesting and easier to follow.

## 2024-11-19

Today I have learned how to upload my Unity project to a GitHub repository.

## 2024-11-26

During our stand up meeting, I have realised that the tutorials are supposed to be independent from our prototype game. I initially planned to make the tutorials connected in order to build my protoype gmae. That is why I have reorganised my tutorials and tried to separate them from my project. I started writing my tutorial for Player movement from scratch so it does not have any information linked to my prototype (as it used to have). other than that, I have divided my tutorials into Player movement, Ai movement (following another object), Score goal system and UI system. Although explaining the tutorials without my game to rely on might be a bit daunting, it seems like it will be easier to understand the tutorials without having to follow another.

## 2024-12-03
Today I am going to finish my first tutorial on Player Movement. I was planning on finishing it last week, but I realised how thorough the tuorial has to be. It took me a long time to take the screenshots, edit the text, and find an aproppriate way to explain the code and the process of setting up the project. I am trying to finish this tutorial today, because I still have three tutorials to do which will be as much time consuming the first one.




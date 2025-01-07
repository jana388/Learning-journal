# Learning-journal
this documents my adventure in programming

## 2024-10-15

Today I created a learning journal.

## 2024-10-21

Planning the concept of the game and the tutorials I could make that would be useful in the future projects. I wanted to start with something simple but also fundamental to any game.

## 2024-10-22

I figured I wanted to make a game similiar to Pong, since it contains all the fundamental scripts to make a game. I found a useful tutorail on Youtube which has all most of the scripts I need for my prototype. I chose this tutorial because i wanted to practice some simple codes but I wanted to challenge myself in a 3D environment. This is a link to the tutorial (https://www.youtube.com/watch?v=b3xgCUlst88&t=2789s). I have managed to make a script for the player movement. I enabled a cube to move left and right on the Z axis by pressing *A* and *D*. I have used an input system which was new to me, but I don't encounter any difficulties so far. 

After that I worked on the ball movement. It took me a while to learn how to manipulate the ball's movement. I ran into a problem when trying to change the direction of the ball when it hits the wall or the racket (cube). Instead of switching to the opposite direction like it would pick a different direction. The only mistake I made was picking the right axis when rerouting the ball. After figuring out which one I needed to use, the problem was solved.

## 2024-10-29

I have tried to make a code for the Cube moved by the computer (Ai-movement). I want the other player to follow the ball (move left and right). Since I was following the youtube tutorial for the Ai movement as well, I have not realised that they positioned the whole platform and the player facing a different direction. So I ran into a problem when writing the script for the Ai. The code did not want to work at first, because I picked a z axis (like in the tutorial) so the cube was not able to follow the cube. After fixing the axis to x, the code went smoothly. 

## 2024-11-05 

Today I am going to work on the Goal Controller, which will enable the ball to be destroyed when touching the goal.
I used an Event system so that it the goal could connect with the ball. This will let the game know when one of the players has scored a goal. 

After testing the prototype for a bit, I realised that my AI player is flawless and manages to track the ball's movement without missing it, making it impossible for me to score a goal. That is why I decreased the speed of the AI, so when the ball comes from a sharp angle, it will not be able to reach the ball quickly enough, giving me a shot to score a goal. 

I also started working on the UI (score count). I wanted to have a display so that the game could count the number of goals we have scored.

## 2024-11-12

Finished the UI for the score count. Although it was simple to set it up in Unity, I also needed to make some code, so the score actually goes up when we score a goal. 
That is why I made a Game Controller script that will operate the game. In this script, I have written a script for the score count: When a player scores a goal, it will get a point, and when the Ai scores a goal, it will get a point. 
Had issues afterwards, because after one scores a goal, the ball did not spawn back. And because there was no ball, none of the players were able to move.
To fix this issue, I added the ball spawn in Game Controller, so after every score, the ball spawns back to its initial position after 0.5f and it randomises the direction of the movement. There was a NullReferenceException error when the ball wasn't in the game, so in the player script I wrote some code to try to find the ball, and if it didn't exist, then the code would not run because I returned out of the function.

## 2024-11-18

Today I will continue working on my tutorial for player-movement. I have collected all the screenshots and edited them in Procreate so they seem more interesting and easier to follow.

## 2024-11-19

Today I have learned how to upload my Unity project to a GitHub repository.

## 2024-11-26

During our stand up meeting, I have realised that the tutorials are supposed to be independent from our prototype game. I initially planned to make the tutorials connected in order to build my protoype gmae. That is why I have reorganised my tutorials and tried to separate them from my project. I started writing my tutorial for Player movement from scratch so it does not have any information linked to my prototype (as it used to have). other than that, I have divided my tutorials into Player movement, Ai movement (following another object), Score goal system and UI system. Although explaining the tutorials without my game to rely on might be a bit daunting, it seems like it will be easier to understand the tutorials without having to follow another.

## 2024-12-03
Today I am going to finish my first tutorial on Player Movement. I was planning on finishing it last week, but I realised how thorough the tuorial has to be. It took me a long time to take the screenshots, edit the text, and find an aproppriate way to explain the code and the process of setting up the project. I am trying to finish this tutorial today, because I still have three tutorials to do which will be as much time consuming the first one.

## 2024-12-10
I have made another repository for my Ai-movement tutorial. It is going to be about how to make another object follow the movement of the player. I started planning on how to make it. With the help of my prototype, I already had some code and an idea of how to construct the tutorial. Nevertheless, since the tutorials have to be independent and not extend  on the previous tutorials, I still needed some time to organise how the tutorial will look.

## 2024-12-20
I continued working on Ai-movement tutorial. I added a prerequisite on Player movement script for this tutorial so I do not have to explain thoroughly again on how to make it. I wanted this tutorial to be solely based on Ai-movement script. By setting this prerequisite, the focus will be only on Ai script. Although I had this script in my prototype game, I made a new Unity project specifically for this code so I can start explaining from scratch. Not only has it helped me to focus on this code, but it has also helped me practice this code a bit more. On the other hand, there are a lot of extra objects and scripts in my prototype game which I did not want to include in the tutorial, because it would confuse the reader. What is more, it will help me practice coding a bit more.


## 2024-12-25
I started working on my UI tutorial. My goal is to make a tutorial on how to show a text on screen when playing a game. For now I was planning to work on a tutorial on how to make a Ui in Unity. But if I manage to finish my fourth tutorial, I would like to add some code, for example, increase a score with an if statement. For now I gathered all the information on editing the UI in Unity.

## 2025-01-05
Today I finished my final tutorial about the Goal manager. By explaining the events it helped me gather all the information to make it more clear for me to understand too


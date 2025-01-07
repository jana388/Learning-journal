# Learning-journal
this documents my adventure in programming

## 2024-10-15

Today I created a learning journal.

## 2024-10-21

Planning the concept of the game and the tutorials I could make that would be useful in the future projects. I wanted to start with something simple but also fundamental for any game.

## 2024-10-22

I figured I wanted to make a game similiar to Pong, since it contains all the basic scripts to make a game. I found a useful tutorail on Youtube which has all most of the scripts I need for my prototype. I chose this tutorial because I wanted to practice some simple codes but I also wanted to challenge myself in a 3D environment. This is a link to the tutorial (https://www.youtube.com/watch?v=b3xgCUlst88&t=2789s). I have managed to make a script for the player movement. I enabled a cube to move left and right by pressing *A* and *D*. I have used an input system which was new to me, but I don't encounter any difficulties so far. 

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

Since my prototype is done, I started working on my tutorial for Player-movement. I have collected all the screenshots and edited them in Procreate so they seem more interesting and easier to follow.

## 2024-11-19

Today I have learned how to upload my Unity project to a GitHub repository.

## 2024-11-26

I initially planned to make the tutorials connected, so I wanted it to be like a step-by-step guide to a Pong game. However, during our stand up meeting, I have realised that the tutorials are supposed to be independent from our prototype game. That is why I have reorganised them and tried to separate them from my prototype.

I started writing my tutorial for Player movement from scratch so it does not have any information linked to my prototype (as it used to have). I used the same code from the prototype, but have made a separate Unity project.

Other than that, I did some more brainstorming on what my tutorials will be. For now I have Player movement, and Ai movement *(an object following another object)* planned, but I was thinking of making a tutorial for Score manager and UI system.

## 2024-12-03
Today I am finishing up my tutorial for Player Movement. I was planning on finishing it last week, but I realised how thorough the tutorial was. Since I planned it to be a beginner friendly tutorial, it took me a long time to organise it and explain thoroughly. It took me a while to take the screenshots, explain the steps and the functions.

## 2024-12-10
I have made new repository for my Ai-movement tutorial. This tutorial will explain how to make a script for an object to follow another object. I started organising the text and the script. With the help of my prototype, I already had some code and an idea of how to construct the tutorial. Nevertheless, I made a new Unity project so I could start making it from scratch.

## 2024-12-20

I continued working on Ai-movement tutorial. I added some prerequisites so I would not get stuck with explaining the basics again. 

For example, I gave a prerequisite for knowing how to use Unity's basic and to have a script for the Players' movement script. I wanted this tutorial to be solely based on Ai-movement script. By setting these prerequisites, the focus will be only on Ai script. Having to make a script from scratch has helped me focus on this code, but it has also helped me practice this code a bit more. I had a chance to alter the code a bit.
On the other hand, there are a lot of extra objects and scripts in my prototype game which I did not want to include in the tutorial because it would confuse the person who is following it. 

## 2024-12-25

I started working on my UI-arrangement tutorial. My goal is to make a tutorial on how to show a text on screen when playing a game. For now I was planning to work on a tutorial on how to make a UI in Unity. But if I manage to finish my fourth tutorial, I would like to add some code, for example, increase a score with an if statement. 
While writing the tutorial, I spotted a little detail in the Hierarchy. I have not realised that when making a UI panel, it also comes with a Canvas and an Event System. After doing some research and trying to give an explanation in the tutorails, it helped me understand it better.
I spent a couple of days working on this tutorial, and trying to organise the layout.

## 2025-01-05
Today I started working on my final tutorial, Goal-Manager. I managed to finish the draft in a day, but I still need some time to polish it. It was a bit more demanding than the Ui tutorial, since it was more programming based. By gathering all the information about how the events work, I had a better vision of how they operate, and why we use them when making games.


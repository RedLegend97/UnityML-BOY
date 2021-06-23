# UnityML-BOY
 My graduate project where an agent is trained using reinforcement learning to learn to play a game. There is user version and agent version of the game.

1. Introduction

In this project, the main goal is to create a video game using the Unity game engine
and putting an agent to the video game that can learn how to play that video game
using machine learning.

2. Problem Definition

Goal in the game is to collect the presents (Fig1) while avoiding the obstacles (Fig2)
and traps (Fig3) by controlling the character called the “boy” (Fig4) in the game area
(Fig5). If the boy can collect all the presents without failing, the area turns green and
the game resets (Fig6), and if the boy fails to collect all the gifts and hit into a trap, then
the game will fail, and the game area will blink in red (Fig7).

So the goal is to train the boy (agent) without any data (reinforcement learning) and
make it learn how to play the game properly.

![image](https://user-images.githubusercontent.com/61790422/123057130-4826ce00-d410-11eb-93ba-ea8e54740876.png)

Figure 1: A Present (They should be collected to earn points)

![image](https://user-images.githubusercontent.com/61790422/123057065-38a78500-d410-11eb-8f18-536e54fcdb18.png)

Figure 2 : Obstacle (they block the view and stand in the way of agent.)

![image](https://user-images.githubusercontent.com/61790422/123057274-68568d00-d410-11eb-8eb8-9a1c5c24bd9e.png)

Figure 3: Traps (They reduce the score and fails the current game restarting the game table)

![image](https://user-images.githubusercontent.com/61790422/123057338-760c1280-d410-11eb-93ab-b69e83c1eeb8.png)

Figure 4: Meet with our agent the “BOY.” (Boy has 4 inputs which are moving forward move backward rotate clockwise and rotate counterclockwise.)

![image](https://user-images.githubusercontent.com/61790422/123057376-7efce400-d410-11eb-8ad0-784cdb4000d2.png)

Figure 5: Game Arena consisting of traps obstacle and presents. This is the overall look of the the area where the game is played.

![image](https://user-images.githubusercontent.com/61790422/123057425-88864c00-d410-11eb-895c-d1a8e5c25400.png)

Figure 6: Arena blinking in green Figure 7: Arena Blinking in red.

3. Methodology

I will be using Unity ML-Agent for training and testing, which is based on Tensorflow.
This was a project that I started to learn to create agents and artificial
intelligence to use in the video games I develop. So I’ve even trained it before too. But
with this course now I have an better understanding and grasp on the machine
learning topic. So I want to try on different learning algorithms Tensorflow provides, and I also want to test on curriculums to see how they affect. As of the
date, I am writing this report, and I did not finish the training part; once I finish and test, I
will share my results.

4. Experiments and Results

Since this is not a project that can be evaluated numerically, to understand the “boy’s performance, I will also be creating a human version of
the game that human players can play. We will see the world from
the boy's eyes, and we will be playing the game with the same rules. Where we will


Fail if we touch the traps and earn points if we collect gifts. So, to evaluate
how well the boy is playing, we can compare the boy’s score with our score.




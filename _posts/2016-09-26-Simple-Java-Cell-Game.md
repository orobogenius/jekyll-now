---
layout: post
title: Simple Cell Game (Java) - Beginner
---

We'll be designing a simple game in Java (using Swing), nothing too complicated or fancy. Of course, at the end of this post you could tweak the game and add new features or even change the entire layout, as a matter of fact, it's what I would expect.

## The Game
---
The game is : Creating a 9 cells box 3x3 (Grid), each box should light up randomly at intervals (preferably with different colours), if the user is able to click on the lightened box before another box lights up he gets +1 points otherwise he loses a life and he has total of 3 lives.

Here is a peak of the outcome we'll be designing (of course, you should use an alternate design in yours).

![alt text](https://github.com/orobogenius/orobogenius.github.io/blob/master/images/Game1.png "In Action")
![alt text](https://github.com/orobogenius/orobogenius.github.io/blob/master/images/Game2.png "Game Over")

## Setup
---
* IDE - Netbeans
* Layout - Mixed (GridBagLayout, GridLayout)

## Requirement
---
* Basic Java Knowledge
* Basic Java Swing Knowledge

## Action
---
Now to the fun part, before building, we should always have a plan, an algorithm we'll follow to accomplish the task.

This design uses a `JButton` that controls the flow of the game (start and stop). First, when the game is started, there ar a few thing we should do:
* We create and start a timer task. If you'r not familiar with timer tasks

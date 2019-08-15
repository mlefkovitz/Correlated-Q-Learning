# Recreating Correlated-Q Learning

## Introduction

In this project, I replicate Figure 3 from “Correlated-Q Learning” by Amy Greenwald and Keith Hall.
Figure 3 includes 4 charts (a, b, c, and d) each demonstrating the Q-value error at each iteration of a
soccer simulation.

#### The game 

In a "soccer" environment with 2 players, one ball, and 8 grid spaces, each player's objective is to force the ball to enter the other player's goal.

[Greenwald and Hall Paper](/Correlated-Q%20Learning.pdf)

[Full Report](/Project3-gth836x.pdf)

## The Project
Python Files:
- soccerpdvelez.py
- testbenchpdvelez.py
- Q Learning.py
- Friend Q.py
- Foe Q.py
- Correlated Q.py

### soccerpdvelez.py
- Soccer Simulation Environment developed by Pedro Velez

### testbenchpdvelez.py
- Contains some output methods used in the soccer simulation. Also developed by Pedro Velez

### Q Learning.py
![Q Learning](Figure3d%20Q-Learning.png)
- Implemented a straightforward Q learner for 1,000,000 steps against the soccer environment

### Friend Q.py
![Friend Q](Figure3c%20Friend-Q.png)
- Implemented a Friend-Q learner for 1,000,000 steps against the soccer environment

### Foe Q.py
![Foe Q](Figure3b%20Foe-Q.png)
- Implemented a Foe-Q learner for 1,000,000 steps against the soccer environment

### Correlated Q.py
- Implemented a Correlated-Q learner for 1,000,000 steps against the soccer environment
Automated Snake Game Solver
Via AI Search Algorithms

Overview:-
Automated Snake game solver using AI search algorithm where computer automatically control the snake to move and collect food in a map. Our implementation was done in JavaScript, using canvas to draw the UI. The algorithms used to search for the food are DFS, BFS, and A\* using some heuristics.

Approach:-
We use Javascript to implement the game using  three search algorithms : BFS, DFS and A* search algorithm .The heuristics  A* search allow us what direction the food is closest to, so we search in that direction instead of randomly wandering around the board. Sort of like if the snake had a sense of smell.
Snake will follow some basic rules :

- the snake tries to collect food by avoiding obstacles.
- the length of the snake will remain constant.

So, we use  various search algorithm to help the snake in finding its food, and calculate the time and search complexity for each algorithm.

Goal:-

This project was an assignment for a university course in Artificial Intelligence.

The goal of this assignment was to measure the usefulness of various search algorithms. In this example, we are using Breadth First Search, Depth First Search, and A\* search with two heuristics (and combined) to allow the snake to find the food by avoiding obstacles.

Here you can see the basic design of the game UI:

![AI](https://user-images.githubusercontent.com/31498029/57656952-83caf900-75f7-11e9-9b17-642c39c1b97a.png)

View this on the link given below:
https://yjangir49.github.io/AI_Snake_Game/

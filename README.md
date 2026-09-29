SLE-2: Empirical Performance Analysis

1. Project

Topic: BFS vs DFS Maze Pathfinding



This project compares two AI search algorithms:



Breadth-First Search (BFS)

Depth-First Search (DFS)



Both algorithms solve the same 6×6 maze.

2. Problem Statement

The task is to find a path from:



Start: (0, 0)

Goal: (5, 5)



The maze contains:



0 → Open path

1 → Wall



The performance of BFS and DFS is compared using:



Execution time

Nodes expanded

Path length

3. Algorithms

BFS – Breadth-First Search

Uses a queue.

Searches level by level.

Finds the shortest path in this maze.

Can use more memory.

DFS – Depth-First Search

Uses a stack.

Goes deeper before trying another path.

Can be faster for some maze layouts.

Does not guarantee the shortest path.

4. Profiling Method

Python's time.perf_counter() was used.

Process

Run BFS on the maze.

Run DFS on the same maze.

Repeat each algorithm 20,000 times.

Calculate average execution time.

Count the expanded nodes.

Compare the path lengths.

Repeat the experiment for 3 runs.

5. Results

Metric

BFS

DFS

Run 1

0.021834 ms

0.017401 ms

Run 2

0.020059 ms

0.015957 ms

Run 3

0.019603 ms

0.015723 ms

Nodes Expanded

21

17

Path Length

10 steps

16 steps

Simple Observation

DFS was faster in all 3 runs.

DFS expanded fewer nodes.

BFS found the shorter path.

BFS path = 10 steps

DFS path = 16 steps

6. Analysis

What the results show

Speed: DFS performed better.

Nodes: DFS expanded fewer nodes.

Path quality: BFS performed better because it found the shorter path.

The time difference was very small.

Execution time alone is not enough to compare the algorithms.



For this maze, DFS reached the goal quickly because of its search order. BFS searched level by level and found the shortest route.

7. AI Contribution

AI Tool: Claude (Anthropic)

AI helped with

BFS and DFS code

Profiling code

Report structure

Explanation

My work

Ran the program

Collected the actual results

Checked the node counts

Reviewed and understood the results

8. Conclusion

Profiling helps measure actual algorithm performance.

DFS was faster for this maze.

BFS found the shorter path.

Different metrics can give different results.

Multiple runs give a more reliable comparison.

9. Files

.
├── maze_profiler.py
└── README.md


maze_profiler.py

Contains:



Maze

BFS

DFS

Node counting

Path visualization

Performance measurement

README.md

Contains the project explanation, results, analysis, and conclusion.

10. How to Run

Make sure Python is installed.

python maze_profiler.py


The program displays:



BFS path

DFS path

Execution time

Nodes expanded

Path steps

11. Student Details

Name: Samarth Sanjay Yamgar

PRN: 25UAM122

Division: B

Course: 02AML204 – Introduction to Artificial Intelligence

SLE: SLE-2 – Profiling Report

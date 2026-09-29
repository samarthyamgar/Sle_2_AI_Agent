# AI Contribution Log

## SLE-2: Empirical Performance Analysis

**Name:** Samarth Sanjay Yamgar
**PRN:** 25UAM122
**Course:** 02AML204 – Introduction to Artificial Intelligence
**Topic:** BFS vs DFS Maze Pathfinding

---

## 1. AI Tool Used

**AI Tool:** Claude (Anthropic)

---

## 2. How AI Helped

AI was used during the development of this project for:

* Understanding the BFS and DFS approach.
* Writing the initial BFS and DFS maze-solving code.
* Creating the profiling and timing code.
* Adding node-counting functionality.
* Structuring the SLE-2 report.
* Helping explain the experimental results in simple words.
* Creating the README documentation.

---

## 3. My Contribution

I personally:

* Selected **BFS vs DFS** as the algorithms to compare.
* Used the **6×6 maze** for the experiment.
* Ran the Python program.
* Ran the algorithms multiple times for profiling.
* Collected the actual execution-time results.
* Checked the number of nodes expanded.
* Checked the path length produced by BFS and DFS.
* Compared the results.
* Reviewed and understood the final analysis.
* Prepared the final project files for submission.

---

## 4. Profiling Work

The profiling was performed using Python's:

```python
time.perf_counter()
```

Each algorithm was executed **20,000 times** during a profiling run.

The experiment was repeated for **3 runs**.

The measured results were:

| Metric         |      BFS |      DFS |
| -------------- | -------: | -------: |
| Nodes Expanded |       21 |       17 |
| Path Length    | 10 steps | 16 steps |

DFS was faster in the three measured runs, while BFS found the shorter path.

---

## 5. AI vs My Work

| Work                         | Contribution |
| ---------------------------- | ------------ |
| BFS/DFS implementation       | AI assisted  |
| Profiling code               | AI assisted  |
| Node-counting logic          | AI assisted  |
| Running experiments          | **My work**  |
| Collecting actual results    | **My work**  |
| Checking results             | **My work**  |
| Understanding the comparison | **My work**  |
| Final submission             | **My work**  |

---

## 6. Declaration

AI was used as a supporting tool during this project. The performance values shown in the report were obtained by running the program and checking the results myself.

I reviewed the generated code and explanations and used the results from my own experiment for the final analysis.

# Lab1
LAB 1 PART A and B

**Lab 1: Search Algorithms for Drone Pathfinding**

**Student:** Ramatou AMIDOU

**Course:** Intro to Artificial Intelligence


 **About the lab**
 
This lab implements search algorithms for a drone navigating through terrain while avoiding obstacles.

**Repository Contents**

Ramatou_AMIDOU_Lab_1A.ipynb - Uninformed Search (BFS, DFS, DLS, IDS)

Ramatou_AMIDOU_Lab_1B.ipynb - Informed Search (Greedy, A, Weighted A, UCS)

AI_USE_DECLARATION.md - AI use declaration

**Part A:** Uninformed Search

Algorithm	What it does

BFS	Shortest path in unweighted grids

DFS	Fast but not always shortest

DLS	DFS with depth limit

IDS	Combines BFS completeness with DFS memory

**Part B:** Informed Search
Algorithm	What it does

Greedy	Fast but can be suboptimal

A*	Optimal and efficient

Weighted A*	Trade speed for optimality

UCS	Optimal but blind

**Heuristics used**: Manhattan, Euclidean, Zero

**Key Findings**

BFS finds shortest path in unweighted grids

A* finds cheapest path when heuristic is admissible

Greedy is fast but can choose expensive paths

Weighted A* gives a good speed/quality balance

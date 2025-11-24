# Autonomous Delivery Agent

## Problem Statement

Efficient and reliable delivery is a critical challenge in urban environments. Traditional delivery methods often face delays due to traffic, obstacles, or inefficient routing. This project aims to develop an AI-powered autonomous delivery agent capable of navigating a 2D grid city environment using advanced pathfinding algorithms. The agent can plan optimal routes, handle varying terrain costs, and dynamically replan paths when unexpected obstacles appear.

## Scope of the Project

The project focuses on:

* Implementing multiple pathfinding algorithms including Breadth-First Search (BFS), Uniform-Cost Search (UCS), and A* search.
* Supporting dynamic replanning to handle obstacles that appear during execution.
* Modeling a 2D grid city with terrain costs and static obstacles.
* Evaluating agent performance through metrics such as path cost, path length, nodes expanded, and execution time.
* Providing a command-line interface (CLI) to run simulations on different map scenarios.

## Target Users

* AI and robotics enthusiasts interested in autonomous navigation.
* Students and researchers studying pathfinding, search algorithms, or AI planning.
* Developers building simulation environments for autonomous delivery systems.

## High-Level Features

* **Multiple Pathfinding Algorithms:** BFS, UCS, A* for different planning needs.
* **Dynamic Replanning:** Adjusts the path when new obstacles appear.
* **Terrain Cost Support:** Handles standard and difficult terrain with varying movement costs.
* **Obstacle Handling:** Supports static and dynamic obstacles.
* **Path Reconstruction:** Provides the complete path from start to goal.
* **Performance Metrics:** Reports path cost, path length, nodes expanded, and execution time.
* **Flexible Map Support:** Can run on maps of varying sizes with different terrain and obstacles.
* **Error Handling:** Robust handling for invalid maps or inputs.

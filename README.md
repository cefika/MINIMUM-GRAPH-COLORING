# Minimum Graph Coloring

This project focuses on solving the Minimum Graph Coloring problem using various optimization algorithms. The algorithms implemented in this project include:

1. Genetic Algorithm (GA)
2. Ant Colony Optimization (ACO)
3. Brute Force
4. Particle Swarm Optimization (PSO)
5. Simulated Annealing (SA)

## Table of Contents

- [Introduction](#introduction)
- [Algorithms](#algorithms)
  - [Genetic Algorithm](#genetic-algorithm)
  - [Ant Colony Optimization](#ant-colony-optimization)
  - [Brute Force](#brute-force)
  - [Particle Swarm Optimization](#particle-swarm-optimization)
  - [Simulated Annealing](#simulated-annealing)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributors](#contributors)

## Introduction

The Minimum Graph Coloring problem is an NP-hard problem where the goal is to color the vertices of a graph using the minimum number of colors such that no two adjacent vertices share the same color. This project implements several algorithms to solve this problem and compares their performance.

## Algorithms

### Genetic Algorithm

The Genetic Algorithm (GA) is a metaheuristic inspired by the process of natural selection. It uses techniques such as selection, crossover, and mutation to evolve solutions to optimization problems.

### Ant Colony Optimization

Ant Colony Optimization (ACO) is a probabilistic technique inspired by the behavior of ants searching for food. It uses a colony of artificial ants to explore the solution space and find optimal or near-optimal solutions.

### Brute Force

The Brute Force algorithm exhaustively searches all possible colorings to find the optimal solution. It guarantees finding the minimum coloring but is computationally expensive for large graphs.

### Particle Swarm Optimization

Particle Swarm Optimization (PSO) is a computational method inspired by the social behavior of birds flocking or fish schooling. It optimizes a problem by iteratively trying to improve a candidate solution with regard to a given measure of quality.

### Simulated Annealing

Simulated Annealing (SA) is a probabilistic technique for approximating the global optimum of a given function. It is inspired by the annealing process in metallurgy.

## Installation

To run this project, you need Python and the following libraries:

- numpy
- networkx
- matplotlib
- pandas

You can install these libraries using pip:

```sh
pip install numpy networkx matplotlib pandas

```

## Usage

### Clone this repository:
```sh
git clone https://github.com/yourusername/minimum-graph-coloring.git
```

### Navigate to the project dirctory:

```sh
cd MINIMUM-GRAPH-COLORING
```
### Chose the desired algorithm and run the script

## Results

The results of the experiments, including the number of colors used and execution time for each algorithm, are compared in the 'Rezultati' directory. The comparison is provided in a CSV file and visualized using plots.

## Contributors
- Stefan Mitrovic - [@cefika](https://github.com/cefika)
- Lazar Rankovic - [@LazarR33](https://github.com/LazarR33)


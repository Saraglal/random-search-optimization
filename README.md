# Random Search Optimization for Travelling Salesman Problem (TSP)

This repository contains implementations of three different algorithms for solving the Travelling Salesman Problem (TSP) using random search optimization techniques. The TSP is a classic problem in computer science and operations research, where the goal is to find the shortest possible route that visits each city exactly once and returns to the original city.

## Algorithms Implemented

### 1. Nearest Neighbor Heuristic

The Nearest Neighbor Heuristic is a simple and intuitive algorithm for solving the TSP. It starts from a randomly chosen city and repeatedly selects the nearest unvisited city until all cities have been visited. This algorithm provides a quick solution but may not always yield the optimal route.

### 2. Genetic Algorithm

Genetic Algorithms (GAs) are inspired by the process of natural selection and genetics. In the context of the TSP, GAs work by maintaining a population of candidate solutions (routes), evaluating their fitness (total distance traveled), and using evolutionary operators such as selection, crossover, and mutation to generate new solutions. Over successive generations, the algorithm evolves towards better solutions.

### 3. Ant Colony Optimization

Ant Colony Optimization (ACO) is a metaheuristic inspired by the foraging behavior of ants. In the TSP, ACO simulates the behavior of ants laying pheromone trails to guide their colony towards food sources. In the algorithm, artificial ants construct solutions by probabilistically selecting edges based on pheromone levels and heuristic information. Over time, the pheromone trails are updated based on the quality of solutions found, leading to the discovery of better routes.

## Dataset

The dataset used for evaluating the algorithms consists of information about cities and their coordinates. Each algorithm aims to find the shortest route to visit all cities and return to the starting city.

### Dataset Files

- `tsp_dataset.csv`: CSV file containing the details of cities and their coordinates.

## Usage

To run the notebooks and experiment with the algorithms:

1. Clone the repository to your local machine.
2. Ensure you have the necessary dependencies installed (Python, Jupyter Notebook, etc.).
3. Open the desired notebook in Jupyter Notebook or JupyterLab.
4. Follow the instructions provided in the notebook to execute the code and analyze the results.



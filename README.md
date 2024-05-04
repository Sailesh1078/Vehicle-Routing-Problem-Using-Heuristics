# Vehicle Routing Problem Solver

This Python program provides an implementation to solve the Vehicle Routing Problem (VRP) using various heuristic and metaheuristic techniques. The VRP is a combinatorial optimization problem where a fleet of vehicles must deliver goods to a set of customers, minimizing the total distance traveled or maximizing the total profit earned.

## Key Components

### 1. Instance Generation

- The `create_instance(N, M)` function generates a random dataset of customers and their demands, along with their locations. `N` represents the number of nodes (customers) in the graph, and `M` represents the types of items possible.

### 2. Heuristic Algorithms

- **A-Star 1 (A*)**: Finds the optimal path based on minimizing the total distance traveled by vehicles. It utilizes the A* search algorithm with edge-based heuristic.
  
- **A-Star 2 (A*)**: Finds the optimal path based on maximizing the total profit earned by vehicles. It employs the A* search algorithm with node-based heuristic.

- **A-Star 3 (A*)**: Finds the optimal path based on a combination of minimizing distance and maximizing profit. It integrates both edge-based and node-based heuristics.

- **Depth-First Branch and Bound (DFBB)**: Finds an optimal path using a depth-first search with a heuristic. It employs a branch-and-bound approach to explore the search space efficiently.

### 3. Metaheuristic Algorithms

- **Simulated Annealing (SA)**: An optimization algorithm that probabilistically accepts worse solutions to escape local optima. It iteratively explores the search space by perturbing solutions based on a temperature schedule.

- **Genetic Algorithm (GA)**: An evolutionary algorithm that evolves a population of solutions over generations through selection, crossover, and mutation. It maintains a population of candidate solutions and applies genetic operators to generate new solutions.

## Usage

1. Run the `main()` function in the provided Python script.
2. Input the parameters such as the number of nodes (`N`), types of items (`M`), maximum distance a vehicle can cover (`dmax`), and the total amount of each item the vehicle has (`C`).
3. The program will generate a random dataset and solve the VRP using various techniques.
4. The optimal path(s) will be displayed along with the total distance covered and total profit earned.

## Dependencies

- Python 3.12
- NumPy
- Matplotlib


## Example

```
N = 7
M = 1
C = [10]
dmax = 100
```

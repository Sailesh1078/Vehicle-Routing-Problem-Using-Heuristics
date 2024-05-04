# Vehicle Routing Problem Solver

This Python program provides a solution to the Vehicle Routing Problem (VRP) using various heuristic and metaheuristic techniques. The VRP involves optimizing the routes for a fleet of vehicles to deliver goods to a set of customers while minimizing the total distance traveled or maximizing the total profit earned.

## Features

- **Create Instance**: Generates a random dataset of customers and their demands, along with their locations.
- **Heuristic Algorithms**:
  - **A-Star 1**: Finds the optimal path based on minimizing the total distance traveled by vehicles.
  - **A-Star 2**: Finds the optimal path based on maximizing the total profit earned by vehicles.
  - **A-Star 3**: Finds the optimal path based on a combination of minimizing distance and maximizing profit.
  - **Depth-First Branch and Bound (DFBB)**: Finds an optimal path using a depth-first search with a heuristic.
- **Simulated Annealing (SA)**: An optimization algorithm that probabilistically accepts worse solutions to escape local optima.
- **Genetic Algorithm (GA)**: An evolutionary algorithm that evolves a population of solutions over generations through selection, crossover, and mutation.

## Usage

1. Run the `main()` function.
2. Input the number of nodes, types of items possible, maximum distance a vehicle can cover, and the total amount of each item the vehicle has.
3. The program will generate a random dataset and solve the VRP using various techniques.
4. The optimal path(s) will be displayed along with the total distance covered and total profit earned.

## Dependencies

- Python 3.12
- NumPy
- Matplotlib

```

## Example Usage

```python
N = 7
M = 1
C = [10]
dmax = 100
main()
```

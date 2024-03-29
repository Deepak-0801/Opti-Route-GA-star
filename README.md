# TSP Optimization Project

## Overview

This project explores different approaches to optimize the Traveling Salesman Problem (TSP) using a variety of algorithms. The goal is to compare their performance based on key metrics. 10 cities with static values have been used in this code to compare metrics over multiple approaches.

## Algorithms Used

1. **Brute Force Method:** Exhaustively explores all possible solutions.
2. **Genetic Algorithm (GA) Method:** Evolves and optimizes TSP solutions using genetic algorithms.
3. **A* Swap Optimization (Low Granularity):** Utilizes A* algorithm with swap operations at a low granularity for local optimization.
4. **A* Mutation (Low Granularity):** Applies A* algorithm with mutation at a low granularity for enhanced exploration.
5. **A* Mutation (High Granularity):** Employs A* algorithm with mutation at a higher granularity, focusing on exploitation.

## Metrics Measured

1. **Fitness Value Over Generation:** Tracks the quality of TSP solutions over generations (for GA) or iterations (for A* methods).
2. **Exploration/Exploitation Rate:** Measures the balance between exploring new solutions and exploiting the current best solutions.
3. **Time:** Evaluates the efficiency of each algorithm by measuring the total runtime.
4. **Plateau Detection:** Identifies performance plateaus to understand convergence and potential stagnation.

## How to Run

Code can be run using Colaboratory Research Lab, Google

## Results and Analysis

### Performance of the Fitness over Generations

#### Genetic Algorithm
- Convergence Present [Clear Indication of Evolution]
- Exploration valued more than Exploitation
- Best solution found in all iterations
- 1 second

![Genetic Algorithm](https://github.com/Deepak-0801/Opti-Route-GA-star/assets/84059340/e1105cdd-3587-4e09-8971-db80ad14c833)

#### A* Swap Optimization (Low Granularity)
- Erratic Behavior with no convergence
- Exploration is highly valued
- Best solution not found at all times
- 8 seconds

![A* Swap Optimization (Low Granularity)](https://github.com/Deepak-0801/Opti-Route-GA-star/assets/84059340/dc89c1de-5063-4a96-98b3-4965c849c2b9)

#### A* Mutation (Low Granularity)
- Premature Convergence Present
- Exploitation over Exploration
- Best solution found in all instances
- <1 second

![A* Mutation (Low Granularity)](https://github.com/Deepak-0801/Opti-Route-GA-star/assets/84059340/04864f5a-91f9-4b58-82b5-155bcbc5f397)

#### A* Mutation (High Granularity)
- Extreme Premature Convergence
- Exploitation valued highly
- Best solution found in all iterations
- 25 Seconds

![A* Mutation (High Granularity)](https://github.com/Deepak-0801/Opti-Route-GA-star/assets/84059340/359212e9-4ac2-4cb9-8a6c-52dddd731ec5)

## Contributors

**Preethi Raghuraman**
- *Student, Computer Science Engineering, SRM IST*

**Deepak Kumar S**
- *Student, Computer Science Engineering, SRM IST*

**Dr. Paavai Anand**
- *Asst. Professor, Computer Science Engineering, SRM IST*


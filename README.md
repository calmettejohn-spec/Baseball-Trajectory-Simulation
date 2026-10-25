# Baseball Trajectory Simulation

A computational physics project exploring how different air resistance models affect the flight of a baseball.

## Project Overview

This project uses Python to simulate the trajectory of a baseball under four different conditions:

- No air resistance
- Linear air resistance
- Quadratic air resistance
- Quadratic air resistance with a drag crisis

All four simulations use the same initial launch conditions (50 m/s at 45°) to allow direct comparisons.

## Methods

I used SciPy's `solve_ivp` function to numerically solve the equations of motion and Matplotlib to visualize the trajectories.

**Python libraries:** NumPy, SciPy, Matplotlib

## Results

The simulations demonstrate how different models of air resistance can significantly affect a baseball's flight distance. The drag-crisis model accounts for changes in the drag coefficient as the baseball's speed changes.

## Skills Demonstrated

- Numerical solutions to differential equations
- Python programming
- Physics-based mathematical modeling
- Data visualization
- Comparing simulation results



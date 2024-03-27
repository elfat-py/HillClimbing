# HillClimbing

## Overview
**This Python code simulates the optimization of hospital placements in a grid-based environment. The goal is to minimize the overall distance from houses to hospitals by strategically placing hospitals within the grid.**

## Features
- Point: Represents a point in a grid with x and y coordinates. Provides methods for distance calculation and finding the closest hospital.
- Grid: Represents the grid where hospitals and houses are placed. Includes methods for placing hospitals and houses, calculating the cost of the current configuration, and performing optimization algorithms.
- Hospital: Represents a hospital with a position in the grid. Includes a method to find neighboring hospitals.
- House: Represents a house with a position in the grid.
- Optimization Algorithms: Implements hill climbing and random reset optimization algorithms to find an optimal configuration of hospital placements.
- File I/O Operations: Writes the grid configuration to files for each iteration of the optimization process.

## Usage
- Clone or download the repository to your local machine.
- Ensure you have Python 3.x installed.
- Run the main.py file.
- Adjust parameters such as grid dimensions, number of hospitals, and optimization iterations as needed.
- View the output files generated in the specified directory to observe grid configurations and optimization progress.

## File Structure
- mainClasses.py: Main Python script containing the simulation implementation.
- main.py: Starting point of our console application
- README.md: Documentation providing an overview of the project and instructions for usage.

## Dependencies
- Python 3.x

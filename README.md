# Computer Modeling of Physical Phenomena

This repository contains Python scripts developed for the course **Computer Modeling of Physical Phenomena** at the **Faculty of Physics, University of Warsaw**. These scripts demonstrate various computational techniques and simulations used in modeling physical systems.

## Contents

The repository includes multiple Python files, each focusing on different topics related to computational physics. The contents cover a wide range of numerical and simulation techniques used in solving physical problems. Below is a detailed breakdown:

### Differential Equations
- Implementation of numerical methods such as Euler's method and Runge-Kutta methods to solve ordinary differential equations.
- Applications include modeling physical systems such as pendulums, population dynamics, and simple harmonic oscillators.
- Exploration of stability and accuracy of different numerical approaches.
- Adaptive step-size methods for improving computational efficiency.

### Monte Carlo Simulations
- Random sampling techniques used to estimate physical properties and probabilistic systems.
- Examples include simulations of radioactive decay, statistical thermodynamics, and percolation models.
- Importance sampling techniques to improve convergence.
- Applications in computational statistical mechanics and quantum mechanics.

### Data Visualization and Animation
- Use of Matplotlib and other libraries to create visual representations of physical simulations.
- Generation of animations to demonstrate time-dependent phenomena such as wave propagation and particle motion.
- Implementation of interactive plots to analyze results dynamically.
- Visualization of phase space trajectories and bifurcation diagrams.

### Computational Methods for Physical Problems
- Finite difference methods for solving partial differential equations.
- Numerical integration techniques and root-finding algorithms.
- Simulation of dynamic systems such as coupled oscillators and chaotic systems.
- Application of spectral methods and Fourier transforms in physical modeling.
- Implementation of cellular automata models for complex systems.

### Statistical and Thermodynamic Simulations
- Simulation of gas particle distributions and Maxwell-Boltzmann statistics.
- Computational approaches to phase transitions and critical phenomena.
- Numerical solutions to the Ising model and lattice gas models.
- Application of Markov Chain Monte Carlo (MCMC) methods.

### Special Scripts
- `cmpp08_gif.py` generates animations to visualize physical phenomena dynamically.
- `cmpp08_unused_functions.py` contains auxiliary functions that may assist in various calculations but are not directly used in primary scripts.
- `cmpp10_lite.py` provides simplified versions of computational models for quick simulations.

## Structure

The scripts are named systematically, typically using the format `cmppXX_Y.py`, where:
- `XX` refers to the topic or week number
- `Y` indicates different versions or parts of the topic

## Usage

To run any script, simply execute it using Python:
```sh
python cmppXX_Y.py
```

Some scripts may require additional dependencies, which can be installed using:
```sh
pip install -r requirements.txt
```

## Purpose

This repository serves as a portfolio of my computational physics skills, showcasing my ability to apply Python programming to solve and simulate physical problems. It is intended for educational purposes and as a reference for students and researchers interested in computational physics.


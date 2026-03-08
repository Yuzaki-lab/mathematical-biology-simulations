# Mathematical Biology Simulations in Python

This repository features numerical simulations of fundamental models in mathematical biology. It demonstrates the use of Python for solving differential equations and visualizing complex biological dynamics.

## Implemented Models

### 1. SIR Model
- **Description**: A classic compartmental model in epidemiology that computes the theoretical number of people infected with a contagious illness in a closed population over time.
- **Key Features**: Visualization of Susceptible, Infectious, and Recovered populations.

### 2. Lotka-Volterra Predator-Prey Model
- **Description**: Describes the dynamics of biological systems in which two species interact, one as a predator and the other as prey.

### 3. Lotka-Volterra Competition Model
- **Description**: An extension of the logistic growth equation to model how two species compete for the same limited resources.
- **Analysis**: Explores scenarios of stable coexistence versus competitive exclusion.

## Tech Stack
- **Language**: Python 3.x
- **Libraries**: 
  - `NumPy` & `SciPy`: For numerical integration of ODEs.
  - `Matplotlib`: For generating high-quality simulation plots.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install numpy scipy matplotlib`
3. Open the `.ipynb` files in Jupyter Notebook or Google Colab.

## Future Work
- Implementation of stochastic simulation algorithms (e.g., Gillespie algorithm).
- Spatial modeling using Partial Differential Equations (PDEs).

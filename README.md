# Mathematical Biology Simulations in Python

This repository features numerical simulations of fundamental models in mathematical biology. It demonstrates the use of Python for solving differential equations and visualizing complex biological dynamics,evolutionary processes, and spatial systems.
The goal is to provide intuitive computational experiments for studying biological and ecological systems.
## Implemented Models
### Epidemic Models
### SIR_Model
- **Description**: A classic compartmental model in epidemiology that computes the theoretical number of people infected with a contagious illness in a closed population over time.
- **Key Features**: Visualization of Susceptible, Infectious, and Recovered populations.
### Network_Epidemic_Model
Extends epidemic modeling to network structures, where disease spreads through connections between individuals.
### Ecological Dynamics
### Lotka_Volterra_Predator_Prey_Model
- **Description**: Describes the dynamics of biological systems in which two species interact, one as a predator and the other as prey.
- **Key Features**:Oscillatory population dynamics,predator–prey cycles
### Lotka_Volterra_Competition_Model
- **Description**: An extension of the logistic growth equation to model how two species compete for the same limited resources.
- **Analysis**: Explores scenarios of stable coexistence versus competitive exclusion.
### Pattern Formation
### Reaction_Diffusion(Turing Patterns)
- **Description**:Simulates spatial pattern formation based on reaction–diffusion equations.This model demonstrates how simple local interactions can generate complex biological patterns.
### Evolutionary and Complex Systems
### Game Theory Simulation
- **Description**:Agent-based simulations exploring evolutionary game dynamics such as the emergence of cooperation.
### Agent_Based_Model
- **Description**:Simulates interacting agents whose local rules generate complex global behavior.
### Computational Methods
### Monte Carlo Simulation
- **Descriptions**:Demonstrates stochastic simulation methods for estimating mathematical quantities and modeling probabilistic processes.

## Tech Stack
- **Language**: Python 3.x
- **Libraries**: 
  - `NumPy` & `SciPy`: For numerical integration of ODEs.
  - `Matplotlib`: For generating high-quality simulation plots.

## Project Structure
mathematical-biology-simulations/
│
├── sir_model/
├── lotka_volterra/
├── competition_model/
├── reaction_diffusion/
├── game_theory/
├── network_epidemic/
├── monte_carlo/
├── agent_based/
│
└── README.md

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install numpy scipy matplotlib`
3. Open the `.ipynb` files in Jupyter Notebook or Google Colab.

## Future Work
- stochastic simulation methods (e.g. Gillespie algorithm)
- spatial models using partial differential equations (PDEs)
- additional evolutionary game dynamics
- network-based ecological simulations

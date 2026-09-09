# Evolutionary Computing

Coursework for *Evolutionary Computing* (X_400111) at Vrije Universiteit Amsterdam.

## Overview

This repository contains assignments exploring evolutionary algorithms for combinatorial optimisation. The main project implements a solver for the N-Queens problem using genetic algorithms, investigating the effects of different mutation operators, crossover strategies, and selection mechanisms on convergence and solution quality.

## Contents

- `Assignment_1a/A_1a_N_Queens.ipynb` -- Jupyter notebook with the full implementation and experiments
- `Assignment_1a/A_1a_N_Queens.pdf` -- Written report

## Methods

- Genetic algorithm with permutation-based representation
- Selection: tournament selection, fitness-proportionate selection
- Crossover: order crossover (OX), partially mapped crossover (PMX)
- Mutation: swap mutation, inversion mutation
- Fitness function based on non-attacking queen pairs

## How to Run

```bash
pip install jupyter numpy matplotlib
jupyter notebook Assignment_1a/A_1a_N_Queens.ipynb
```

## Requirements

- Python 3.8+
- Jupyter Notebook
- NumPy, Matplotlib

## Course

Evolutionary Computing (X_400111) -- Vrije Universiteit Amsterdam

# Bayesian Modeling of Skewed Spatio-Temporal Data

This repository contains the code, notebooks, and data supporting the
paper:

**Bayesian Modeling of Skewed Spatio-Temporal Data Using a Flexible
Random Field with Matérn Correlation and Adaptive Hamiltonian Algorithm**

Authors: Omid Karimi and Fatemeh Hosseini  
Department of Statistics, Semnan University, Semnan, Iran

## Overview

The repository provides implementations of a Bayesian spatio-temporal
regression model based on a flexible closed skew-normal (FCSN) random
field with separable Matérn correlation. Bayesian inference is performed
using adaptive Hamiltonian Monte Carlo (AHMC).

## Repository structure

- `data/`: simulation and PM10 data
- `notebooks/`: reproducible Jupyter notebooks


## Reproducing the results

Run the notebooks in numerical order:

1. Generate or load the simulation data.
2. Fit the model using AHMC.
3. Fit the model using MH.
4. Summarize the simulation results.
5. Analyze the PM10 data.
6. Compare competing models.
7. Produce the prediction maps.


# Differentially Private Geodesic Regression

This repository provides Python code for performing geodesic regression on a unit sphere with differential privacy. It includes methods to compute the footpoint and shooting vector, generate replicates using Markov Chain Monte Carlo (MCMC), and validate the results against theoretical bounds.

## Features:

## Geodesic Regression

Computes the footpoint and shooting vector for given input data.

Normalizes points to lie on the unit sphere.

## Differential Privacy

Adds noise to the footpoint and shooting vector to ensure differential privacy.


## MCMC Sampling

Generates replicates of the footpoint and shooting vector using a theoretically proven acceptance probability.

**The acceptance probability is removed from the code as the paper is yet to be published.**

## Validation and Visualization

Generates histograms to visualize the distances between the true values and the noisy replicates.

Validates the results against proven theoretical bounds.

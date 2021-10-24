# Bayesian_Optimization

This repo contains tutorial on how to implement the Bayesian Optimization algorithm for complex optimization problems. 

Bayesian optimization is a directed approach to global optimization that uses probability. It is often used in applied machine learning to tune the hyperparameters of a given well-performing model on a validation dataset. Generally, optimization is applied in machine learning on:
  
  - Algorithm Tuning - optimization of model parameters
  - Algorithm Training - optimization of model hyperparameters
  - Predictive Modeling - Optimization of data, data preparation, and algorithm selection

Global optimization is a challenging problem of finding an input that results in the minimum or maximum cost of a given objective function.

Often times, the objective function is complex and intractable to analyze and is often non-convex, nonlinear, high dimension, noisy, and computationally expensive to evaluate.

Bayesian Optimization provides a principled technique based on Bayes Theorem to direct a search of a global optimization problem that is efficient and effective. It works by building a probabilistic model of the objective function, called the surrogate function, that is then searched efficiently with an acquisition function before candidate samples are chosen for evaluation on the real objective function.

Code mostly adopted from https://machinelearningmastery.com/what-is-bayesian-optimization/

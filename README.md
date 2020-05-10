# Introduction

Optimization can be brought forward to portfolio analysis where each asset's weightage in the portfolio will be optimized with respect to the objective.

Our current objective (constrained maximization problem) is to maximize the sharpe ratio of a portfolio where the x-variable will be the weightage of each asset. 

The long term goal would be to create a ARIMA model that would be backtested using a Model Predictive Control method that could possible be incorporated with multi-objective optimization processes (maximize sortino ratio, minimize volatility etc).

The aim of this git, is to allow users to have a comprehensive view towards how to organize data from online sources and use such data to run optimization processes on. We will first begin with a simple single objective optimization function and compare this optimization result with a randomized monte carlo method.

# Architecture

Below is the architecture of our project:
- 📁 modules
  - 📑 portfolioOptimizationSLSQP.ipynb

- 📑 README.md


# Prerequisites

- **numpy** 👉 the basic scientific library of Python with built-in math functions and easy array handling
- **matplotlib** 👉  for graph plotting
- **pandas** 👉 to manipulate dataframes, a Python object that comes in handy when we manipulate large datasets
- **scipy** 👉 to run an minimization process

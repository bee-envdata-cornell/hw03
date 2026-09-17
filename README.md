# Homework 3 — OLS Is a Likelihood
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Homework 3 for [BEE 4850/5850](https://envdata.viveks.me), Spring 2027. Due **Thu 18 Feb 2027**.
Covers Week 3: linear regression and the hinge — regression as a probability model.

## Learning Objectives

- write out a Gaussian-error linear model with all its assumptions, distinguishing errors from predictor;
- show that OLS maximizes the Gaussian likelihood, and identify the assumption that equivalence rests on;
- derive the estimator implied by a different error distribution and say what it implies about outlier influence;
- pair a residual diagnostic with the assumption it tests;
- simulate from a fitted model and check the spread of refits against the analytic standard error.

## Data

`data/annual_maxima.csv` — as Homework 2. Years with at least 8,000 recorded hours (n = 92).

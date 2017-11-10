# Practical Probabilistic Programming -- Made Simple

## Abstract

This tutorial will guide you through use cases on how to use probabilistic programming in your projects. Through the use of simplified complex examples, you will see how to perform parameter estimation, case/control analysis, hierarchical modelling, and regression analysis. Theory, where appropriate, will be introduced, but is not the focus of the tutorial. There will be multiple structured examples available. This tutorial assumes intermediate Python proficiency, including the use of context managers, Python objects and their methods, and an ability to read code library documentation.

## Outline

1. Introduction (10 min)
    1. Bayes Theorem
    1. Why uncertainty?
    1. Features of a PP language (intro to PyMC3)
        1. Distribution library
        1. Syntax
        1. Sampling algorithms <-- fancy math for lazy programmers! (and non-mathematicians)
    1. Where do you **not** want to deploy a Bayesian model? (e.g. real-time decision systems where the value of uncertainty is very low)
1. Parameter Estimation (30 min)
    1. Worked example (10 min) (coin flip)
    1. Hands-on coding (15 min)
    1. Discussion/questions (5 min)
1. Break (5 min)
1. Case/Control Analysis (40 min)
    1. Worked example (10 min)
    1. Hands-on coding (20 min)
    1. Discussion/questions (5 min)
        1. NTS: someone might ask about comparison to t-test.
1. Break (10 min)
1. Hierarchical Modelling (40 min)
    1. Rationale (5 min)
    1. Worked example (10 min)
    1. Hands-on coding (20 min)
    1. Discussion/questions (5 min)
1. Break (5 min)
1. Regression Problems (40 min)
    1. Problem class description (given Xs, predict Y, but now with uncertainty) (5 min)
    1. Worked example (10 min)
    1. Hands-on coding (20 min)
    1. Discussion/questions (5 min)
1. End

## Getting Prepared

### Simplest Way

1. Make sure you have Python installed. Anaconda distribution recommended.
1. Run environment script: `$ bash conda_environment.sh` to get setup.

### Manual Way

1. Install all packages specified in `environment.yml` using your favourite package manager (e.g. pip, conda).

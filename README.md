# Practical Probabilistic Programming Made Simple

## Description

This tutorial will provide an example-driven introduction on how to use probabilistic programming. Through the use of real-world examples, you will see how to perform parameter estimation, case/control analysis, hierarchical modelling, and regression analysis. Theory will be introduced where appropriate, but is not the focus of the tutorial. Multiple structured examples will motivate learning.

## Audience

If you feel limited by your current toolkit or analytic workflow, in terms of being able to express and solve modeling problems and account for statistical uncertainty, then this tutorial is for you. We assume intermediate Python proficiency, including the use of context managers, Python objects and their methods, and the ability to read code documentation. We also assume some knowledge of introductory statistica (_e.g._ definitions of central tendency and variance measures). If you've ever performed a t-test and know what a Gaussian distribution looks like, you have all the background you need. By the end of the tutorial, you will be able to describe a  problem as a probabilistic model, and and fit that model using PyMC3.

## Outline

1. Introduction (10 min)
    1. Bayes Theorem
    1. Why uncertainty?
    1. Features of a PP language (intro to PyMC3)
        1. Distribution library
        1. Syntax
        1. Sampling algorithms <-- fancy math for lazy programmers (and the algebra-blind)!
    1. Where Bayesian models are (and are not useful?
1. Comparing two groups with binary outcomes (30 min)
    1. Worked example (10 min) (coin flip)
    1. Hands-on coding (15 min)
    1. Discussion/questions (5 min)
1. Break (5 min)
1. Comparing two groups with continuous outcomes (40 min)
    1. Worked example (10 min)
    1. Hands-on coding (20 min)
    1. Discussion/questions (5 min)
        1. NTS: someone might ask about comparison to t-test.
1. Break (10 min)
2. Regression Analysis (40 min)
    1. Problem class description (given Xs, predict Y, but now with uncertainty) (5 min)
    1. Worked example (10 min)
    1. Hands-on coding (20 min)
    1. Discussion/questions (5 min)
1. Break (5 min)
1. Hierarchical Modelling (40 min)
    1. Rationale (5 min)
    1. Worked example (10 min)
    1. Hands-on coding (20 min)
    1. Discussion/questions (5 min)
1. End

## Tutorial Instructors

### Eric J. Ma

Eric finished his doctoral degree in the Department of Biological Engineering at MIT, where he studied influenza evolution and ecology. He currently works at the Novartis Institutes for Biomedical Research, where he is an Investigator on the Scientific Data Analysis team. He has given talks & tutorials on practical aspects of Network Analysis and Bayesian Statistics at a variety of Python conferences, including PyCon, SciPy, and PyData (recordings available online). His website is [www.ericmjl.com][ericmjl].

[ericmjl]: www.ericmjl.com

### Chris Fonnesbeck (creator of PyMC3)

Chris is a professor of Statistics at Vanderbilt University, and is the **creator** and one of the **lead maintainers** of PyMC3. His research interests span computational and Bayesian statistics, epidemiology, and meta-analysis.

## Getting Prepared

### Simplest Way

1. Make sure you have Python installed. Anaconda distribution recommended.
1. Run environment script: `$ bash conda_environment.sh` to get setup.

### Manual Way

1. Install all packages specified in `environment.yml` using your favourite package manager (e.g. pip, conda).

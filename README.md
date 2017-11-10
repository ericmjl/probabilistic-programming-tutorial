# Practical Probabilistic Programming Made Simple

## Description

This tutorial will guide you through use cases on how to use probabilistic programming in your projects. Through the use of simplified complex examples, you will see how to perform parameter estimation, case/control analysis, hierarchical modelling, and regression analysis. Theory, where appropriate, will be introduced, but is not the focus of the tutorial. There will be multiple structured examples available.

## Audience

If you encounter modelling problems at work and your current toolkit does not allow you to quantitatively describe the uncertainty in your predictions, then this tutorial is for you. We assume intermediate Python proficiency, including the use of context managers, Python objects and their methods, and an ability to read code library documentation. We also assume basic statistics knowledge (e.g. definitions of central tendency and variance measures). If you've ever done the t-test and know what a Gaussian distribution looks like, you'll be covered for stats background. By the end of the tutorial, you should be able to describe your modelling problem using probability distributions, and be equipped with the necessary syntax to follow through on modelling.

## Outline

1. Introduction (10 min)
    1. Bayes Theorem
    1. Why uncertainty?
    1. Features of a PP language (intro to PyMC3)
        1. Distribution library
        1. Syntax
        1. Sampling algorithms <-- fancy math for lazy programmers (and the algebra-blind)!
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

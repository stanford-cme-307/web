---
layout: page
title: Goals
has_toc: false
description: >-
    Course learning goals and detailed objectives
---

# Course learning goals
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

These course learning goals and more detailed objectives will guide our course through the quarter and direct our lectures, activities, and assessments. By understanding the connection of each topic to these goals and objectives, students can understand how each course topic connects to our high-level goal of preparing students to model and solve optimization problems and conduct novel research on optimization algorithms.
1. formulate real-world problems as optimization problems
    * List and describe types of optimization problem in standard form
    * Identify objectives, constraints, variables, and their domains, given a free-text or notional description of a problem
    * Write down the optimization problem in standard form (eg in LaTeX)
2. identify appropriate solvers and explain tradeoffs in the context of a real world problem, considering features including size, sparsity, discrete variables, convexity, ill-conditioning, access patterns to problem data, convergence tolerance, speed, generalizability
    * Explain mathematically why features including size, sparsity, discrete variables, convexity, ill-conditioning, access patterns to problem data, convergence tolerance, and speed are important for the effectiveness of optimization algorithms
    * Understand that access patterns to problem data include finite fixed data samples (or expensive-to-query data samples), zero, first, and second order oracles for objectives or constraints
    * Identify features of an optimization problem written in a standard form (eg in LaTeX)
    * List solvers appropriate for a problem with given features
3. make mathematical predictions about the performance of optimization algorithms
 <!-- and understand the implications of mathematical theory for practical optimization. -->
    * Understand convergence guarantees and rates for optimization algorithms, including global and local convergence, and sublinear, linear, and superlinear convergence
    * Use duality to prove lower bounds and develop stopping criteria
    * Assess the sensitivity of a solution to problem data
4. tweak optimization algorithms to adapt them to a specific problem
    * Generate simulated data to exemplify and vary properties of the problem
    * Implement a baseline algorithm from the literature
    * Identify poor performance of the baseline algorithm in a specific problem setting (eg ill-conditioned)
    * Propose solutions (eg preconditioning)
    * Design an improved algorithm
    * Implement the improved algorithm
    * Test the improved algorithm and assess impact of problem properties and algorithm hyperparameters
    * Generate concrete recommendations for algorithm and hyperparameter choice based on problem properties (or easy-to-compute proxies)
5. develop confidence as an optimizer by designing a solution to an optimization problem, including reviewing the relevant literature, selecting methodology, writing code, and presenting results
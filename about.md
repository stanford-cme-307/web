---
layout: page
title: About
description: >-
    Course policies and information.
---

# About
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Course description and prerequisites

Optimization entails seeking decisions that maximize objectives while satisfying constraints, with applications across engineering, business, economics, statistics, data analysis, and everyday life. This course provides an in-depth and rigorous introduction to mathematical optimization, covering how to formulate, analyze, and solve real-world problems using modern optimization theory and software. Topics include finite-dimensional linear optimization problems with continuous and discrete variables, sensitivity and duality, basic elements of convex analysis, first- and second-order optimality conditions for nonlinear optimization problems, and a discussion of important algorithmic and computational aspects related to optimization.
<!-- 2024 Spring 
An optimizer seeks to identify the decisions that will maximize their objectives
while satisfying constraints, with applications across engineering, 
business, economics, statistics, data analysis, 
and everyday life. 
Through this course, students will learn to formulate and solve real-world problems using modern optimization
and the fundamental analysis required to develop new algorithms for 
new problems.
We formalize optimization problems, in particular considering their 
size, sparsity, discrete variables, convexity, ill-conditioning, access patterns to problem data, convergence tolerance, and speed,
and introduce algorithmic paradigms including linear systems,
first and second order methods, 
preconditioning, stochastic optimization, and integer programming. -->
<!-- 2022 and earlier
Applications, theories, and algorithms for finite-dimensional linear and nonlinear optimization problems with continuous and discrete variables. 
Elements of convex analysis, first- and second-order optimality conditions, sensitivity and duality. 
Algorithms for unconstrained optimization, and linearly and nonlinearly constrained problems. 
Modern applications in data analysis, machine learning, engineering system design, communications, game theory, auctions, and economics. -->

This course is required for ICME PhD students. 
PhD students from other disciplines seeking to research optimization or to use optimization in their research or perform optimization research, 
ambitious ICME masters students,
and advanced undergraduates in mathematics, computer science, statistics, and related fields are also welcome.

Prerequisites:
- Math 113 (linear algebra) and 115 (calculus), or equivalent
- fluency in proof-based mathematics

## Course learning goals

<!-- Big dream: students should be able to formulate and solve real-world problems using modern optimization. -->

Through active engagement and completion of course activities, you will be able to:
<!-- * recognize that every problem is an optimization problem. -->
* Formulate real-world problems as optimization problems.
* Characterize and analyze optimal solutions to problems by using the core principles of optimization theory and developing fluency in optimization proof techniques.
* Understand the benefits and drawbacks of modeling and solving an optimization problem 
in any of several standard forms, 
including linear programs (with continuous and discrete variables), 
quadratic and second-order conic problems, 
semidefinite programming, stochastic and robust optimization.
* Identify analytical properties of a real-world problem and understand how these influence guarantees of optimality, algorithm and solver selection, or speed of convergence to an optimal solution.
* Tweak optimization algorithms to adapt them to a specific problem.
<!-- * tweak optimization algorithms to adapt them to a specific problem.  -->
<!-- * develop confidence as an optimizer by designing a solution to an optimization problem, including reviewing the relevant literature, selecting methodology, writing code, and presenting results. -->

## Computing environment

We will be using the Gurobi optimizer through [gurobipy](https://pypi.org/project/gurobipy/) in Python to model and solve optimization problems, as gurobipy is has ample features and documentation,
and is supported by the [OptiMUS optimization modeling toolkit](https://optimus-solver.vercel.app/).
We will also use the Julia programming language for in-class algorithm demos, 
as Julia code is both simple to write and fast to run.
<!-- We will be using the Julia programming language via Pluto notebooks for in-class demos. Most optimization solvers are easy to access and swap out from within the Julia ecosystem, and Julia code is both simple to write and fast to run. Pluto notebooks allow for better interactivity and reactivity and are easy to install and use. [Learn how to install and use Pluto notebooks.](https://plutojl.org/) Students may use any language they wish (and that the course staff can read) to complete homework assignments and projects. -->

## Best practices for learning 

Learning how to learn effectively is a skill unto itself! To get the most out of our course learning experience, we recommend the following:
* If possible, attend all class meetings and be fully present and engaged. 
* Take notes on what you read, either directly in the book or somewhere else, and jot down all of the questions you have. 
* Test yourself on what you have read by trying to summarize key points without looking back at the text.
* Ask questions! During class, in office hours, and asynchronously on our discussion platform. The teaching team welcomes all questions and will address them individually with you, or collectively in class.
* Review these [study tips and tools](https://studentlearning.stanford.edu/academic-skills/tips-and-tools) from Stanford’s Center for Teaching and Learning. 

## The honor code and generative AI
In your written work for this course, you are expected cite sources and individuals from whom you have learned and borrowed as a display of academic, intellectual, and creative integrity. Failure to do so is a violation of Stanford’s Honor Code and is a serious offense, even when the violation is unintentional. Conduct prohibited by the Honor Code includes all forms of academic dishonesty, among them unpermitted collaboration and representing others’ work as one’s own. Please review [Stanford’s Honor Code](https://communitystandards.stanford.edu/policies-guidance/honor-code), and documentation and citation resources from the Hume Center for Writing and Speaking. When in doubt, come chat with the course staff after class or in office hours.

Depending on the context, artificial intelligence (AI) can either enhance and impede learning. There are times when these tools might provide us with new ideas and understandings 
(e.g., brainstorming or getting feedback) 
or accelerate workflows to speed us to our goals 
(e.g., autocompletion of code snippets). 
At other points, practicing skills and synthesizing ideas on our own will be crucial for the learning process. 
Thus, being mindful of when to use these tools will help us 
navigate the complexity of interacting with AI technologies in the classroom and beyond. 
In this class, we will use AI tools, including ChatGPT and Github Copilot, that harness large language models in service of our course goals to develop your skill as an optimizer at modeling, coding, and comparing, assessing, and presenting a solution to an optimization problem.

At the beginning of the course, we will co-create a class agreement on the use of AI tools that ensures everyone has equal access to such tools and knowledge of their benefits and limitations; understands the appropriate use of them; and is clear on policies and procedures for their use (including proper citation), and how they connect to the idea of academic integrity. Our class agreement will be consistent with [guidance from the Board of Judicial Affairs](https://communitystandards.stanford.edu/generative-ai-policy-guidance) regarding use of AI and the Stanford Honor Code, which notes that use of generative AI to “substantially complete” an assignment or exam by entering the prompt and submitting the output as one’s own work is not permitted. 

## Access and accommodations

Stanford is committed to providing equal educational opportunities for disabled students. Disabled students are a valued and essential part of the Stanford community. We welcome you to our class.
 
If you experience disability, please register with the Office of Accessible Education (OAE). Professional staff will evaluate your needs, support appropriate and reasonable accommodations, and prepare an Academic Accommodation Letter for faculty. To get started, or to re-initiate services, please visit [oae.stanford.edu](https://oae.stanford.edu).
 
If you already have an Academic Accommodation Letter, we invite you to share your letter with us. Academic Accommodation Letters should be shared at the earliest possible opportunity so we may partner with you and OAE to identify any barriers to access and inclusion that might be encountered in your experience of this course.

Students who are immunocompromised should register with the OAE as soon as possible. 

Student athletes who anticipate challenges in being able to participate in class or submit assignments on time should speak to a course instructor or teaching assistant as soon as possible about available alternatives or allowances.

## Diversity statement

It is our intent that students from all backgrounds and perspectives be well served by this course and that students' learning needs be addressed both in and out of class. We aim to present materials and conduct activities in ways that benefit from this diversity. Your suggestions are encouraged and appreciated. Please let us know if you have ideas to improve the effectiveness of the course for you personally or for other students or student groups.

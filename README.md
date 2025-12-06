# MazeProblem-GeneticAlgorithm


This project contains four independent tasks that explore different areas of artificial intelligence and machine learning, including Genetic Algorithms, optimization, search in structured environments, and regression modelling using Python. Each task was implemented separately, and the final submission includes the full Python code and report.

Task 1 – Travelling Salesman Problem using a Genetic Algorithm
In the first task I implemented and tested a Genetic Algorithm for solving the Travelling Salesman Problem (TSP). The provided GA implementation was modified to evaluate different parameter combinations. Specifically, I tested four population sizes (10, 20, 50, 100) and four mutation rates (0.9, 0.6, 0.3, 0.1). The goal was to observe how these parameters affect convergence quality and the final tour length. For each parameter value, the GA was run once until termination and the results were collected. In the report, I summarized and compared these outcomes, and discussed how larger populations and moderate mutation rates tend to stabilize the search process while still encouraging exploration.

Task 2 – Fitness Function for a Maximization Problem
In this task I implemented a custom fitness function for maximizing the expression:
2xze^(-x) – 2y^3 + y^2 – 3*z^3
The fitness function was integrated into the given GA template from Canvas. The implementation evaluates the expression for each chromosome and returns the fitness score so that the GA can optimize the variables. Only the fitness function is included in the report, but the full working Python program is included in the submission.

Task 3 – Maze Solving Using a Genetic Algorithm
In this task I designed a Genetic Algorithm to solve a 2D maze by evolving paths from a start position to a goal. The maze was represented as a matrix where valid paths were given a value of 1 and walls were given a very large penalty value (e.g., 1000). Each chromosome in the GA encodes a sequence of moves. The fitness function rewards paths that move closer to the goal while penalizing collisions with walls. Over successive generations, the algorithm converges toward paths that reach the destination. The full Python implementation is included either as a .py file or a Jupyter notebook.

Task 4 – Regression Models for Synthetic Data
In the final task I generated synthetic data using:
x_data = np.linspace(−0.5, 0.5, 200)[:, np.newaxis]
and y_data = x_data^2 + Gaussian noise. I then built and compared three models:
	1.	A linear regression model using scikit-learn.
	2.	A polynomial regression model (degree 2) using scikit-learn.
	3.	A neural network with one hidden layer of 6 neurons, implemented in Keras/TensorFlow.

The dataset was split into 80% training and 20% testing using train_test_split. I calculated mean squared errors for all three models and compared their performance. I also plotted the predicted curves for the linear and polynomial models along with the original data points. These results are described briefly in the report, and the complete Python code is included.

Summary
The assignment covers optimization through Genetic Algorithms, the design of fitness functions, pathfinding in constrained spaces using evolutionary search, and classical machine learning regression tasks. All tasks were implemented in Python and tested according to the instructions. The final submission includes all source code and the report summarizing the results.

⸻

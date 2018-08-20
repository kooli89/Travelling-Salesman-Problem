# Travelling-Salesman-Problem
Genetic algorithm in C++ to solve the TSP problem.

## Problem statement 
Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city and returns to the origin city?

## Constraint 
TSP in an NP problem.
Learn about NP problems: http://mathworld.wolfram.com/NP-Problem.html

## Idea
Use a genetic algorithm to solve the problem.
Learn about genetic algorithms: https://towardsdatascience.com/introduction-to-genetic-algorithms-including-example-code-e396e98d8bf3

Use a String to represent the order in which the towns/nodes are visited
As a simplification we can enumerate the towns/nodes so that the string is any permutation of :
1234…n for problems with n nodes.

Note: if the graph is not connected then we can
artificially introduce an infinite weighting between any 2
nodes that are not directly connected.


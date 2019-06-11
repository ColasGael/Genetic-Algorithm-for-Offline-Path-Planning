# Genetic-Algorithm-for-Offline-Path-Planning

by Gael Colas and Ianis Bougdal-Lambert, graduate students from Stanford University.

This repository gathers our final project for the AA222: "Engineering Design Optimization" class at Stanford (2018). Our teacher was Pr. Mykel Kochenderfer.

Language: Python

Goal: Study the use of a genetic algorithm (GA) for the problem of
offline path planning on a 2D map. 

The problem can be framed as follow: find the optimal feasible path to move from a starting position to a target location across a flat map of
a terrain with impenetrable obstacles. 

A scripts generate maps with variable difficulties. The feasible paths must be evaluated according to two criteria: their length and their difficulty. 
In a first approach, only the length of the paths was considered in a Single-Objective minimization process. 
Then the initial algorithm was extended to optimize under the two criteria (MOGA), in a Pareto optimality search. 
Finally, the performance of the algorithms was compared to the performance of state-of-the-art Optimal Control tools.

More details about the project, the data and the model can be found by reading the report and the presentation located at the root: "aa222_final-report_team12-report.pdf" and "aa222_final-presentation_team12.pdf".
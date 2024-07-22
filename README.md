# Grey Wolf Optimization (GWO) Algorithm
![Swarm_intelligence](https://img.shields.io/badge/Swarm%20intelligence%20-%20brown?style=plastic)
![Grey_Wolf_Optimization](https://img.shields.io/badge/Grey_Wolf_Optimization-2014-%20teal?style=plastic)
![License](https://img.shields.io/badge/license%20-%20MIT%20-%20darkred?style=plastic)
![Python Version](https://img.shields.io/badge/Python-3-%20teal?style=plastic)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Open_Issues](https://img.shields.io/badge/Issues%20-%200%20-%20orange?style=plastic)

## Description
This repository contains a Python implementation of the Grey Wolf Optimization (GWO) algorithm. GWO is a nature-inspired optimization algorithm based on the social hierarchy and hunting behavior of grey wolves. It is effective for solving complex optimization problems by mimicking the leadership and hunting strategies of grey wolves in nature.

The GWO algorithm includes four main phases: alpha, beta, delta, and omega, which represent different levels of the social hierarchy. The algorithm iterates to find optimal solutions by simulating the hunting process and updating positions of candidate solutions.


## Installation
1. Clone the repository: `git clone https://github.com/KhalidMustafaElenani/Grey-Wolf-Optimization-Algorithm.git`
2. Navigate to the project directory: `cd Grey-Wolf-Optimization-Algorithm`

## Usage Examples
  - Run the PSO algorithm by executing the main.py file: `python GW_algorithm.ipynb`

## Example output:
```
[$]Iteration: 4
=======================================================
	    Population	         |      Objective Values	
=======================================================
[ 4.46 -1.41 -4.28  2.29]  |        45.44	
[ 2.67 -1.5  -4.58  1.47]  |        32.54	
[ 3.85 -1.26 -4.    1.85]  |        35.84	
[ 4.31 -1.61 -4.49  2.11]  |        45.81	
[ 3.38 -1.63 -4.55  1.74]  |        37.87	
=======================================================

Alpha->	[ 2.67 -1.5  -4.58  1.47],    Fitness: 32.54
Beta->	[ 3.85 -1.26 -4.    1.85],    Fitness: 35.84
Gamma->	[ 3.38 -1.63 -4.55  1.74],    Fitness: 37.87

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
[$]Iteration: 5
=======================================================
	    Population	         |      Objective Values	
=======================================================
[ 4.54 -1.09 -3.19  2.27]  |         37.13	
[ 2.7  -1.83 -5.47  1.35]  |         42.38	
[ 4.68 -0.9  -2.76  2.37]  |         35.94	
[ 4.23 -1.26 -3.97  2.1 ]  |         39.66	
[ 2.91 -1.67 -4.87  1.49]  |         37.24	
=======================================================

Alpha->	[ 4.68 -0.9  -2.76  2.37],    Fitness: 35.94
Beta->	[ 4.54 -1.09 -3.19  2.27],    Fitness: 37.13
Gamma->	[ 2.91 -1.67 -4.87  1.49],    Fitness: 37.24

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```

## Notes
For detailed notes and explanations, refer to the [NOTES.md](NOTES.md).


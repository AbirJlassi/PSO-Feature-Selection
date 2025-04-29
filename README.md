# PSO-Based Feature Selection for High-Dimensional Data
An implementation of Particle Swarm Optimization (PSO) for feature selection in high-dimensional datasets, with iterative refinement and early stopping capabilities.


## Features

- Particle Swarm Optimization for feature selection
- Iterative refinement of feature subsets
- Early stopping based on accuracy improvement
- Tracks accuracy vs feature count progression
- Modular design for easy customization
- Works with any scikit-learn compatible classifier

## Key parameters

- n_particles: 	Number of particles in swarm	(default 30)
- n_iterations: 	PSO iterations per round	(default 100)
- max_rounds:	Maximum refinement rounds	(default 10) 
- min_improvement: 	Minimum accuracy improvement to continue	(default 0.01)
- w	Inertia weight	(default 0.7)
- c1	Cognitive weight	(default 1.5)
- c2	Social weight	(default 1.5) 

##Required packages:

- numpy
- pandas
- scikit-learn
- matplotlib

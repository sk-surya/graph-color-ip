# graph-color-ip
A study on the Graph Coloring Problem - An attempt to achieve faster &amp; better IP solution quality

This was a course work project at my university.
•	Graph Coloring Problem - Exact algorithm development using Integer Programming
o	Conducted Literature Review on various solution techniques for solving the NP-Hard Graph Coloring Problem
o	Analyzed different formulations and worked on reducing the formulation size through constraint aggregation 
& graph pre-processing & added constraints to break symmetry in branch-and-bound tree.
o	Identified various Upper & Lower bounds (analytical, heuristics, sub-optimization)
o	Investigated cutting planes & implemented a heuristic-edge-cover cutting plane algorithm to use in Gurobi user 
node callbacks
o	Fed the solver with good quality initial solutions as warm-start to speed-up the search process
o	Result - Reduced the formulation size & search space effectively that it outperforms the standard formulation

Tools used:
Python & Gurobi

Future work:
To try various other faster lower bound approaches like Lagrangian relaxation and faster upper bounds using metaheuristics to accelerate the tree search.

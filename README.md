```markdown
# APGLP

## build_sample.ipynb
Uses Gurobi to build graph samples from `.g6` files located in the `graphs_g6` folder. The resulting CSV files, stored in the `apgs` folder, include each graph's adjacency list, `a` and `d` values, computed edge labels, and Gurobi runtime for graphs of various sizes.

## qubo_formulation.ipynb
Generates QUBO formulations (and measures QUBO building times) for use with D-Wave. The outputs are saved in the `apglp_qubos` folder.

## Prerequisites
- Valid licenses and access for Gurobi

## Folder Structure

- **build_sample.ipynb**  
  Jupyter Notebook that uses Gurobi to build graph samples.

- **graphs_g6**  
  Contains the input graph files in `.g6` format used for generating samples.

- **apgs**  
  Stores the output CSV files from `build_sample.ipynb`. Each file includes:
  - The graph's adjacency list,
  - The `a` and `d` values,
  - The computed edge labels, and
  - The Gurobi runtime.

- **qubo_formulation.ipynb**  
  Jupyter Notebook for generating QUBOs for the graphs. This notebook processes the graph samples and formulates the QUBO problems for D-Wave.
```

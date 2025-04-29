# APGLP Solving with Gurobi and D-Wave

This project solves the **APGLP problem** and its **fixed version** using:
- **Gurobi Optimizer** (MIP approach)
- **D-Wave Advantage** (quantum annealing)
- **D-Wave Hybrid Solver** (quantum-classical hybrid approach)
---

## Requirements
- **Gurobi License**: Required to run any Gurobi-based solutions.
- **D-Wave API Token**: Required to access D-Wave quantum solvers.
- **D-Wave Ocean SDK**: Required for interacting with D-Wave systems.

> Geting start with Gurobi : https://support.gurobi.com/hc/en-us/articles/14799677517585-Getting-Started-with-Gurobi-Optimizer
> 
> Install Gurobi for Python: https://support.gurobi.com/hc/en-us/articles/360044290292-How-do-I-install-Gurobi-for-Python
> 
> Install D-Wave's Ocean tools following [D-Wave's Installation Guide](https://docs.dwavequantum.com/en/latest/ocean/install.html).

---

## Data and Results

```
Advantage1_Pegasus/            # Results from Advantage_system_6.3 (Pegasus topology)
Advantage2_Prototype_Zephyr/   # Results from Advantage2_Prototype2.2 (Zephyr topology)
hybrid/                        # Results from hybrid_binary_quadratic_model_version2
apgs/
    base_apgs/                 # Main experiment graphs
    extended_apgs/             # Extended experiment graphs
graphs_g6/                     # Unique graph files (.g6 format) from (https://users.cecs.anu.edu.au/~bdm/data/graphs.html).
qubos/                         # Generated QUBOs with formulation time
```

---

## Notes
- Each experiment is organized into **fixed** and **unconstrained** depending on the problem formulation.


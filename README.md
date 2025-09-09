# MD refinement on-the-fly
**Integrating experimental data and molecular dynamics (MD) simulations on-the-fly.**
This repository contains the code and datasets developed for my MSc thesis, focused on the integration of experimental data into molecular dynamics (MD) simulations.  
The main goal is to modify **on-the-fly** the ensemble, the forward model, and the force field in order to make MD simulations more consistent with experimental observations.

---

## 📁 Repository structure
- `data/` — synthetic experimental data and results from long MD simulations, all stored in pickle format.
- `notebooks/` — Jupyter notebooks for figure generation.
- `example.ipynb` — a minimal working example to try out the method.
- `README.md` This file

---

## 📦 Dependencies

All notebooks require the following Python libraries:

```
numpy
re
numba
tempfile
sys
matplotlib.pyplot
scipy.optimize
pickle
collections

```

---
## 📚 Scientific context
In the literature, the refinement of molecular dynamics (MD) trajectories is typically performed **a posteriori**, that is, on trajectories that have already been generated.  
Several methods have been developed to refine the **ensemble**, the **force field**, and the **forward model** simultaneously in a post-processing step.  

The aim of this work is to build upon these theoretical foundations and implement a strategy that performs the **simultaneous refinement of ensemble, force field, and forward model on-the-fly**, during the course of the simulation itself.

## References
- Gilardoni I., Piomponi V., Fröhlking T. and Bussi, G. (2025).  
  **MDRefine: A Python package for refining molecular dynamics trajectories with experimental data**.  
  *The Journal of Chemical Physics*, 162(19). AIP Publishing.  
  [https://doi.org/10.1063/5.0256841](https://doi.org/10.1063/5.0256841)

- Gilardoni, I., Fröhlking, T. and Bussi G. (2024).  
  **Boosting ensemble refinement with transferable force-field corrections: Synergistic optimization for molecular simulations**.  
  *The Journal of Physical Chemistry Letters*, 15(5), 1204–1210. ACS Publications.  
  [https://doi.org/10.1021/acs.jpclett.3c03423](https://doi.org/10.1021/acs.jpclett.3c03423)

- Fröhlking T., Bernetti M., and Bussi G. (2023).  
  **Simultaneous refinement of molecular dynamics ensembles and forward models using experimental data**.  
  *The Journal of Chemical Physics*, 158(21). AIP Publishing.  
  [https://doi.org/10.1063/5.0151163](https://doi.org/10.1063/5.0151163)

- Cesari A., and Reißer S. and Bussi, G. (2018)
  **Using the Maximum Entropy Principle to Combine Simulations and Solution Experiments**
  *Computation*, 18
  [https://doi.org/10.3390/computation6010015](https://doi.org/10.3390/computation6010015)

  

# MD refinement on-the-fly
**Integrating experimental data and molecular dynamics (MD) simulations on-the-fly.**
This repository contains the code and datasets developed for my MSc thesis, focused on the integration of experimental data into molecular dynamics (MD) simulations.  
The main goal is to modify **on-the-fly** the ensemble, the forward model, and the force field in order to make MD simulations more consistent with experimental observations.

## 📁 Repository structure
- `data/` — synthetic experimental data and results from long MD simulations, all stored in pickle format.
- `notebooks/` — Jupyter notebooks for figure generation.
- `example.ipynb` — a minimal working example to try out the method.
- `README.md` This file




## 📦 Dependencies

All notebooks require the following Python libraries:

```
os
pandas
pickle
numpy
matplotlib
sklearn
MDAnalysis
```

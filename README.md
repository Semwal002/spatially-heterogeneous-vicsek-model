# Spatially Heterogeneous Vicsek Model

This repository contains the Python code for simulations of a spatially heterogeneous-noise Vicsek model.

## Contents

The code includes:

* Simulation of the spatially heterogeneous Vicsek model.
* Storage of particle position `(x, y)`, direction `theta`, and time `t`.
* Calculation of the global polar order parameter.
* Calculation of the polar order parameter inside the heterogeneous region.
* Calculation of the mean direction of particles.
* Analysis of these quantities as a function of the noise strength outside the region.

## Code Files

* `Single_region.ipynb` — Simulation of the spatially heterogeneous Vicsek model and generation of particle trajectory data.
* `order_parameter.ipynb` — Calculation of the order parameters and relative density from the generated trajectory data.
* `Plot_OP.ipynb` — Plotting of the order parameters and relative density as a function of the outside noise strength.

## Requirements

The code requires Python 3 and the following packages:

* NumPy
* SciPy
* Numba
* Matplotlib

## Usage

Run `Single_region.ipynb` to generate particle trajectory data containing the particle positions, directions, and time.

The generated trajectory data can then be used with `order_parameter.ipynb` and `Plot_OP.ipynb` to calculate and visualize:

* Global polar order parameter vs. outside noise.
* Polar order parameter inside the heterogeneous region vs. outside noise.
* Mean direction vs. outside noise.

The simulation parameters are specified in the corresponding notebook.

## Reproducibility

The codes are provided to facilitate reproduction of the simulation results associated with the manuscript.

## Reference

This code is associated with a manuscript submitted to *Soft Matter*.

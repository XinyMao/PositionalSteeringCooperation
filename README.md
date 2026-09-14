# PositionalSteeringCooperation
Code for paper "Positional Steering Reshapes Cooperation on Networks"

The repository contains:

- analytical calculations for sparse and finite steering;
- Python simulations on random-regular graphs and square lattices;
- bootstrap and threshold-crossing analysis;
- plot code for MATLAB figures


## Requirements

The formal simulations were run with:

```text
Python 3.14.0
MATLAB R2026a or newer recommended for plotting
```

Create or activate the project virtual environment and install the packages
listed in `pyproject.toml`:

```bash
cd /path/to/St_EoC
python3 -m venv .venv
.venv/bin/python -m pip install -e .
```

## Repository structure

```text
src/hsr_sim/                    simulation engine and adaptive theory
scripts/run_fig5b_exposure.py   Fig. 5b exposure simulation
scripts/run_fig5c_threshold.py  Fig. 5c sparse drift/threshold simulation
scripts/run_fig5d_phase_space.py Fig. 5d finite phase-space simulation
scripts/matlab/                 editable MATLAB plotting functions
Sparse_Theo/                    sparse theoretical derivations
Finite_Theo/                    finite-steering theoretical derivations
results/                        simulation outputs and metadata
figures/                        exported figures and editable FIG files
README_HSR.md                   internal HSR workflow and implementation history
README_Adaptive_simulation_bc.md adaptive-branch handoff record
```

## Numerical simulations

### Fig. 2: sparse steering 
### Fig. 3: finite steering
### Fig. 4: organization
### Fig. 5: adaptive 


## License and citation

Please cite the associated HSR manuscript when using this code or data. The
repository license and final citation metadata will be added when the project
release is prepared.

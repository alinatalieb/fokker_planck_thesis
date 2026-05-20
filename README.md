# Machine Learning Methods for Solving the Fokker-Planck Equation

Master's thesis project (Systems Analysis, 2026).

## Overview
Implementation of the DL-FP method (Xu et al., 2020) for solving 
the stationary Fokker-Planck equation using physics-informed neural 
networks. Tested on two benchmark problems:
- 1D Double-Well potential
- 1D Triple-Well potential

## Structure
- `src/` — core modules (model, loss, training, problem definitions)
- `notebooks/` — experiment notebooks with results

## Requirements
Python 3.12, PyTorch 2.6 (CUDA 12.4), see `requirements.txt`

## Reference
Xu et al. (2020). Solving Fokker-Planck equation using deep learning. 
*Chaos*, 30, 013133. https://doi.org/10.1063/1.5132840

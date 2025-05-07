# hymate-energy-flow-optimization
Energy Flow Optimization Problem &amp; Solution

This repo solves an energy optimization problem using Pyomo. The objective is to meet hourly electricity demand by minimizing the cost.


Setup instructions:
-Clone the repo
  git clone https://github.com/atavice/hymate-energy-flow-optimization.git
  cd hymate-energy_flow_optimization

-Install required packages
  pip install -r requirements

-Install GLPK solver for pyomo
  On macOS (Homebrew): brew install glpk
  On Ubuntu: sudo apt install glpk-utils
  On Windows: Download from https://winglpk.sourceforge.net/


Model explanation and mathematical formulation of the problem can be found in mathematical formulation pdf


Part_A implemented and added as a .ipynb file including the outputs and plots.

Part_B implemented and added as a .ipynb file including the outputs and plots.

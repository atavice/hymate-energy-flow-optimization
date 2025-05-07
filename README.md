# hymate-energy-flow-optimization
Energy Flow Optimization Problem &amp; Solution

This repo solves an energy optimization problem using Pyomo. The objective is to meet hourly electricity demand by minimizing the cost.


## Setup instructions:
-Clone the repo

  git clone https://github.com/atavice/hymate-energy-flow-optimization.git
  
  cd hymate-energy_flow_optimization

-Install required packages

  pip install -r requirements

-Install GLPK solver for pyomo

  On macOS (Homebrew): brew install glpk
  
  On Ubuntu: sudo apt install glpk-utils
  
  On Windows: Download from https://winglpk.sourceforge.net/



## Objective Function

$$
\min_{q,s,b} \sum_{t \in T} \left[
   (q^{g \to c}_t + q^{g \to b}_t) c^{buy}_t
 - (q^{pv \to g}_t + q^{b \to g}_t) c^{sell}_t
 + (q^{b \to c}_t + q^{b \to g}_t) c^{LCOS}_t
\right]
$$



## Notes
Part_A implemented and added as a .ipynb file including the outputs and plots.

Part_B implemented and added as a .ipynb file including the outputs and plots.

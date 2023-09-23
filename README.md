# Model Predictive Control and Infinite-Horizon Stochastic Optimal Control

# Overview
This project utilizes Model Predictive Control (MPC) and Generalized Policy Iteration (GPI) to compute a control policy for an agent to follow a reference trajectory. Our agent is expected to avoid obstacles while having its motion be affected by noise.

# Implementation
This was implemented in Python using NumPy. The code has been redacted, if you wish to see it, you may contact me at charles.lychee@gmail.com

# Results
## Model Predictive Control (MPC)
### Time Horizon = 20
<img src="MPCT20Q01.gif">

### Time Horizon = 70
<img src="MPCT70Q01.gif">

## Generalized Policy Iteration (GPI)
### Discount Factor = 0.9
<img src="GPI90.gif">

### Discount Factor = 0.99
<img src="GPI99.gif">

# Mathematical Approach (WIP)

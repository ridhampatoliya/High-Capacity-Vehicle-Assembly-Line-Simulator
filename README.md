# High-Capacity Vehicle Assembly Line Simulator

A Python-based simulation project for analyzing the behavior of a **high-capacity vehicle assembly line** under realistic operating uncertainty. The simulator models station-level processing, equipment failures, repair effects, and line behavior across repeated vehicle runs to study throughput and system performance.

This project uses a notebook-driven workflow and supporting Excel input data to simulate a multi-station manufacturing process and evaluate how variability and downtime affect assembly-line operations.

## Overview

The objective of this project is to simulate a vehicle assembly line and better understand how stochastic processing times and equipment reliability influence production performance.

The model incorporates:

- Station-by-station vehicle processing
- Randomized process times
- Equipment failure behavior
- Repair-time effects
- Critical and non-critical station logic
- Rework and flow effects across the line

The simulation is implemented in **Python** inside a Jupyter Notebook.

## Model Highlights

Based on the current implementation, the simulator includes:

- A **40-station production line**
- Process times generated from probability distributions
- Equipment-state decisions based on failure probabilities
- Simulation logic that tracks line progression over repeated runs
- Input data loaded from an Excel file for configurable station parameters

This makes the project useful for studying manufacturing-system behavior under uncertain operating conditions.

## Repository Contents

- `MainCode.ipynb`  
  Main Jupyter notebook containing the simulation logic, helper functions, and analysis workflow

- `Project Data.xlsx`  
  Input data used by the simulator, including station and equipment-related parameters

- `README.md`  
  Project overview and usage notes

## How It Works

At a high level, the project follows this workflow:

1. Load assembly-line data from `Project Data.xlsx`
2. Generate process times for vehicles moving through the production line
3. Model equipment condition using failure-probability logic
4. Simulate station-by-station vehicle movement across the line
5. Track operational effects such as delays, repair impact, and rework behavior

The notebook structure suggests a discrete-event style simulation approach for evaluating system performance over a specified run length.

## Tools Used

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** NumPy, Pandas, SciPy, Matplotlib
- **Input format:** Excel

## Why This Project Matters

This project demonstrates experience with:

- Simulation modeling for manufacturing systems
- Stochastic process analysis
- Translating operational assumptions into executable logic
- Using Python for industrial engineering and operations analysis
- Evaluating how equipment reliability affects production flow

## Potential Applications

This type of simulator can support:

- Assembly-line performance analysis
- Bottleneck identification
- Downtime impact assessment
- Reliability and maintenance studies
- Production-system design exploration

## Usage

To explore the project:

1. Open `MainCode.ipynb` in Jupyter Notebook or JupyterLab
2. Ensure the required Python libraries are installed
3. Keep `Project Data.xlsx` in the same directory as the notebook
4. Run the notebook cells to execute the simulation and inspect outputs

## Author

**Ridham Patoliya**

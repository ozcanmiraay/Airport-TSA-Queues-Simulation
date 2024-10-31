## Complex Systems Modeling: Airport Queue Simulation and Analysis

This project simulates airport security queues to analyze various metrics like average queue length, waiting time, and maximum queue length. By adjusting queue configurations and running multiple trials, we explore how different factors impact the efficiency of queue systems, leveraging statistical analyses to provide confidence intervals for each metric.

### Project Overview

The project uses a simulation model to replicate airport security queues under different scenarios. Through extensive trials, we examine:
- **Average Queue Length**: Estimation and confidence intervals for the average queue length.
- **Average Waiting Time**: Analysis of waiting times based on queue configurations.
- **Maximum Queue Length**: Evaluation of peak queue lengths during high traffic periods.

#### Objectives

1. **Queue Simulation**: Model and simulate various queue configurations at airport security checkpoints.
2. **Statistical Analysis**: Compute average and maximum queue lengths, and waiting times, with 95% confidence intervals across trials.
3. **Parameter Exploration**: Test different numbers of queues, trial counts, and simulation durations to understand system efficiency.

### Data Summary and Model Structure

This simulation generates synthetic data representing queue metrics based on input parameters:
- **Number of Queues**: Total queues in the system.
- **Simulation Duration**: Total time (in minutes) each trial runs.
- **Trial Count**: Number of trials to average results for robust statistical estimates.

The analysis includes confidence intervals and error bars for each metric, providing insights into how queue system designs affect passenger flow.

### Repository Structure

- **`notebooks/`**: Jupyter Notebook with the complete simulation code and results, including statistical analysis and visualizations.
- **`scripts/`**: Python scripts implementing the simulation logic for running standalone analyses.
- **`results/`**: Contains output plots and summary tables of the simulation results, detailing queue length, waiting time, and associated confidence intervals.

### How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/complex-systems-queue-simulation.git
   cd complex-systems-queue-simulation
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run simulations**:
   - Start with the `notebooks/queue_simulation_analysis.ipynb` file to explore different configurations and visualize results.
   - For direct script execution, modify parameters in the `scripts/queue_simulation.py` file.

### Key Results

The simulation demonstrates that:
- Increasing the number of queues generally reduces average and maximum queue lengths and waiting times.
- Confidence intervals provide insights into the reliability of each metric under varying conditions, helping optimize queue systems for efficiency.

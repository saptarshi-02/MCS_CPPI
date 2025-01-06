This script performs a Monte Carlo simulation of the Constant Proportion Portfolio Insurance (CPPI) strategy, 
allowing for interactive exploration of various parameters like the number of scenarios, drift, volatility, multiplier, floor value, and risk-free rate. 
The simulation generates and visualizes the evolution of stock prices under a Geometric Brownian Motion (GBM) model and simulates the CPPI strategy over time. 
Additionally, it provides insights into portfolio performance, including floor violations and terminal wealth statistics.

Interactive Visualization (show_cppi):
	•	Evolution of portfolio wealth over time.
	•	Distribution of terminal wealth.
	•	Reporting of floor violations (if the portfolio value falls below the floor).
	•	Calculations for terminal wealth statistics like mean, median, and shortfall.
 
Interactive Controls:
The script uses ipywidgets to create an interactive dashboard that allows users to adjust the simulation parameters:
	•	n_scenarios: Number of Monte Carlo simulations (scenarios).
	•	mu: Drift (annual return).
	•	sigma: Volatility (annual standard deviation).
	•	floor: Minimum acceptable value (floor) as a proportion of the starting value.
	•	m: The multiplier that determines the risky asset allocation.
	•	riskfree_rate: The rate of the safe (risk-free) asset.
	•	steps_per_year: Number of time steps per year for rebalancing.
	•	y_max: Maximum value for the y-axis of the wealth plot to adjust zoom.




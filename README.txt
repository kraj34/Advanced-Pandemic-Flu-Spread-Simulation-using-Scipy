Simulation Project.ipynb: A Jupyter notebook containing the Python code for study of pandemics using SIR and SEIRDV model.

Packages used: 
1)numpy: for handling array outputs from solving differential equations and general array handling
2)scipy.integrate.odeint: to solve the ODEs from the disease models via integration
3)matplotlib.pyplot: for visualizing the solutions

Functions in the notebook:
1)SIR_model(y, t, beta, gamma)-> to model SIR for a given beta and gamma(Explained in report)
2)plot_sir(beta, gamma, S0, I0, R0, t)->to plot S,I,R solutions from solving the differential equations
3)seirdv_model_with_vaccination(y, t, beta, sigma, gamma, mu, rho, alpha) -> the SEIRDV model for modelling COVID with the given parameters(Explained in the report)

Usage
To reproduce the results from the report:
1)Open the Simulation Project.ipynb notebook in a Jupyter environment.
2)Run each cell sequentially to observe the results/plots.
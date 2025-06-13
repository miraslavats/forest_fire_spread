# Forest Fire Spread Simulation 🌲

This simulation models wildfire spread in a forested area using real NASA tree density data and wind dynamics. Developed as a final project for CS166: Modeling and Analysis of Complex Systems at Minerva University.

## Key Features
- Simulates fire spread on a 2D grid with Moore neighborhood logic.
- Incorporates wind strength, direction, and vegetation density into probabilistic spread model.
- Uses real satellite tree density data (NASA).
- Visualizes spread with heatmaps and histograms.
- Quantifies uncertainty with Monte Carlo simulations and 95% confidence intervals.

## Technologies
- Python (NumPy, Matplotlib, etc.)
- Jupyter Notebook

## Results & Insights
- Identified tipping points in base spread rate.
- Mapped high-risk zones based on starting location and environmental parameters.
- Recommended windbreaks as the most effective intervention strategy.

## Files
- `fire_simulation.ipynb`: Full implementation with explanations.
- `report.pdf`: Detailed write-up with methodology, visuals, and policy implications.
- `/figures`: Key visuals generated from simulations.

## To Run
1. Clone this repo.
2. Open `fire_simulation.ipynb` in Jupyter.
3. Adjust parameters and run simulations.

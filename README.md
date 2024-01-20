# Smart-Supply-Chain-Management


## Overview

This project focuses on optimizing the supply chain operations of a multinational company. The goal is to minimize costs and ensure efficient production and distribution across various countries. The optimization model is built using the Pulp library in Python, considering factors such as variable costs, freight costs, storage costs, CO2 emissions, delivery lead times, fixed costs, production capacities, and demand constraints.

## Project Structure

- **Data Files:** The project includes several datasets stored in Excel files, providing information on variable costs, freight costs, storage costs, CO2 emissions, delivery lead times, fixed costs, production capacities, demand, CO2 emission limits, and delivery deadlines.

- **Linear Programming Model:** The linear programming model is implemented using the Pulp library. Decision variables, objective function, and constraints are defined to optimize the supply chain operations.

- **Scenarios:** Different scenarios are considered to analyze the impact of various factors on the supply chain. Scenarios include standard conditions, increased freight costs due to the COVID pandemic, increased demand in specific countries, increased variable costs, and changes in CO2 emission limits and storage costs.

- **Results and Visualizations:** The optimized production quantities for each location under different scenarios are presented using bar charts. Additionally, an interactive plot is provided to visualize the scenarios.

## Dependencies

- Python 3.x
- Pandas
- Pulp
- Seaborn
- Matplotlib
- NumPy
- Jupyter Notebooks (for interactive visualization)

## Usage

1. Install the required dependencies using `pip install -r requirements.txt`.
2. Execute the main script to run the linear programming model and generate results.
3. View the visualizations and scenarios in the Jupyter Notebook or execute the provided interactive plot.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Contributions are welcome!


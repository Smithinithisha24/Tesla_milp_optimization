Tesla MILP Optimization Model 🚗🔋

This project solves a Mixed Integer Linear Programming (MILP) model using Pyomo to optimize Tesla's Gigafactory operations. It includes logistics, energy consumption, and production allocation across multiple plants.

 📘 Project Overview

- Suppliers: Lithium and Nickel from Chile and Indonesia
- Gigafactories: Nevada, Berlin, Texas
- Customers: Tesla assembly plants in Fremont and Shanghai
- Goal: Minimize total cost (transport + energy + fixed) while satisfying demand and energy caps.

✨ Features

- MILP model built with Pyomo
- GLPK solver integration
- Energy usage under TOU pricing
- Visualizations:
  - Plant operational status
  - Material and product flow
  - Time-based energy usage

 🛠 Requirements


pip install pyomo pandas seaborn matplotlib
sudo apt-get install glpk


📊 Visual Output

The notebook generates 3 bar plots:
- Open/Closed status of each Gigafactory
- Battery flow per customer
- Hourly energy usage

▶️ Run the Notebook

Run the notebook in Jupyter




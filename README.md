# MAS.552-Fall-2024

This repository contains materials for the **MAS.552 Fall 2024 Workshop**, focusing on Agent-Based Modeling (ABM), sentiment analysis, and machine learning using **NetLogo** and **Python**.

## Project Overview

In this project, we simulate the spread of information and the associated sentiment dynamics within a community of agents using **NetLogo**. These agents interact, share information, and experience changes in sentiment over time. After running the simulation in NetLogo, we export the data and use **Python** to analyze and predict future behaviors through **machine learning models** such as **Random Forest** and **XGBoost**.

## Files

- **`MASS_552_Fall_2024_W5.html`**: This is the interactive web interface for running the **NetLogo** model.
- **`MASS_552_Fall_2024_W5.nlogo`**: This is the **NetLogo** model file, which contains the code and setup for simulating the behavior of agents.
- **`mem_MAS_552.csv`**: The CSV file generated by **NetLogo** during the simulation, containing the raw data for further analysis in **Python**.

## How It Works

1. **NetLogo Model**:
   - Agents represent individuals in a population that share information.
   - Each agent can be in an "informed" or "uninformed" state.
   - Agents influence each other's state through interactions, which are influenced by their sentiment (modeled as a rate).
   - Sentiment rate changes over time based on information flow.

2. **Python Analysis**:
   - The data exported from the **NetLogo** simulation is loaded into Python.
   - We clean and format the data, then extract key features like:
     - **Spread Rate**: How quickly information spreads.
     - **Attempt Rate**: The rate of attempts to share information.
     - **Success Rate**: How successful agents are in spreading information.
   - Machine learning models such as **Random Forest** and **XGBoost** are applied to predict future behaviors.
   - The results are visualized to compare actual outcomes and model predictions.

## Setup Instructions

1. **NetLogo**:
   - To run the **NetLogo** model, open the `.nlogo` file in **NetLogo Web** or the desktop version.
   - Use the **`Go`** button to start the simulation and visualize how information and sentiment spread among agents.
   - You can adjust parameters such as **sentiment-sharing rate** using the slider.

2. **Python**:
   - To analyze the exported data, use the provided `.csv` file and run the provided **Python** scripts for data processing and machine learning analysis.
   - Ensure you have the necessary Python libraries installed:
     ```bash
     pip install pandas scikit-learn xgboost matplotlib
     ```

## Visualization

- The simulation results can be visualized in **NetLogo** in real-time, showing how agents become informed and how sentiment evolves.
- In **Python**, after training machine learning models, we compare predicted vs actual informed agents using **matplotlib**.

## How to Contribute

If you wish to contribute to this project, please submit a pull request or contact the repository owner.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

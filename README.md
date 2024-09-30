# MAS.552-Fall-2024

This repository contains materials for the **MAS.552 Fall 2024 Workshop**, focusing on **Agent-Based Modeling (ABM)**, sentiment analysis, and machine learning using **NetLogo** and **Python**.

## Project Overview

In this project, we simulate the spread of information and the associated sentiment dynamics within a community of agents using **NetLogo**. These agents interact, share information, and experience changes in sentiment over time. After running the simulation in NetLogo, we export the data and use **Python** to analyze and predict future behaviors through machine learning models such as **Random Forest** and **XGBoost**.

## Files

- **`MASS_552_Fall_2024_W5.html`**: This is the interactive web interface for running the NetLogo model.
- **`MASS_552_Fall_2024_W5.nlogo`**: This is the NetLogo model file, which contains the code and setup for simulating the behavior of agents.
- **`MAS_552_City_Science_W5.ipynb`**: This is the Python notebook where data exported from the NetLogo simulation is processed and analyzed using machine learning techniques.
- **`mem_MAS_552.csv`**: This file contains the raw data generated from the NetLogo simulation, including metrics like total informed agents, sentiment rate, attempts, and successes.

## How to Use

1. **NetLogo Simulation**: 
   - Open the `MASS_552_Fall_2024_W5.nlogo` file in [NetLogo Web](https://netlogoweb.org/).
   - Press `Setup` to initialize the agents and `Go` to start the simulation. Agents will exchange information and experience changes in sentiment over time.
   - Export the data once the simulation finishes.

2. **Python Analysis**: 
   - Download the exported `.csv` data file from NetLogo.
   - Open the [Google Colab notebook](https://colab.research.google.com/drive/xyz) or run `MAS_552_City_Science_W5.ipynb` locally.
   - Load the `.csv` file and follow the notebook instructions to preprocess the data and apply machine learning models to predict agent behaviors.

## Google Colab

You can run the Python analysis directly on Google Colab using the following link:  
[Google Colab Notebook](https://colab.research.google.com/drive/xyz)

## Contributing

Feel free to fork the repository, make improvements, and submit pull requests to contribute to the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

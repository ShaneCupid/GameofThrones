# Game of Thrones Network Analysis

## Overview
This project presents a network analysis of interactions between characters in the "Game of Thrones" book series. The aim is to uncover the most central characters in the books and understand the relationships dynamics through network graphs.

## Technologies Used
- [Python 3](https://www.python.org/doc/) - The programming language used for analysis and network graph generation.
- [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/) - Interactive computing environment for coding and visualizing the network.
- [Pandas](https://pandas.pydata.org/docs/) - Data manipulation and analysis library for Python.
- [NetworkX](https://networkx.org/documentation/stable/) - Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.
- [Matplotlib](https://matplotlib.org/stable/contents.html) - Plotting library for creating static, interactive, and exploratory visualizations in Python.

## Description
This network analysis takes into account the interactions among characters across the five books of the series, represented by five CSV files:

- **book1.csv**
- **book2.csv**
- **book3.csv**
- **book4.csv**
- **book5.csv**

Each file is analyzed to create a network graph representing the connections between characters, with nodes being characters and edges representing their interactions.

### Game_of_Thrones_Network_Analysis.ipynb
- **Input**: CSV files for each of the five books in the series.
- **Process**: 
  - Loading the datasets and constructing the network graphs.
  - Computing network statistics to identify central characters.
  - Visualizing the networks to illustrate character interactions.
- **Output**: Network graphs and centrality metrics for character analysis.

## How It Works

### Data Preparation
- Read and preprocess data from CSV files using Pandas.

### Network Construction and Analysis
- Construct network graphs using NetworkX.
- Calculate centrality measures to identify key characters.
- Visualize the networks with Matplotlib.

## Setup/Installation Requirements
1. Install Python 3 and the necessary libraries with `pip install jupyter pandas networkx matplotlib`.
2. Clone the repository to your local machine.
3. Run `jupyter notebook` in your terminal and open the `Game_of_Thrones_Network_Analysis.ipynb` to view and run the analysis.

## Contact Information
- Business inquiries: [cupidconsultingllc@gmail.com](mailto:cupidconsultingllc@gmail.com)
- Personal inquiries: [shane.cupid@outlook.com](mailto:shane.cupid@outlook.com)
- Phone: 413-461-5472
- LinkedIn: [Shane Cupid](https://www.linkedin.com/in/shane-cupid-92a418b4/)

## License
This project is open-sourced under the MIT License.

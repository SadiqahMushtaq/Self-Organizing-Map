# Self-Organizing Map (SOM)

## Project Overview
This project implements a **Self-Organizing Map (SOM)**, an unsupervised neural network used for clustering and dimensionality reduction. The model is trained on country data from `Q1_countrydata.csv` and visualized using heatmaps.

## Table of Contents
- [Dataset](#dataset)
- [Implementation](#implementation)
- [Results](#results)
- [How to Run](#how-to-run)
- [Acknowledgments](#acknowledgments)

## Dataset
The dataset (`Q1_countrydata.csv`) contains various country statistics used for clustering. It is preprocessed before training the SOM model.

## Implementation
- The project is implemented in **Python** using **Jupyter Notebook (`SOM.ipynb`)**.
- It uses the **MiniSom** library for training a 2D SOM.
- The learning rate and neighborhood function are dynamically adjusted.

## Results
The trained SOM generates the following visualizations:
- **Initial Map (`initial_som_map.png`)**: Shows untrained weights.
- **SOM Clustering (`som_map.png`)**: Displays clustered regions.
- **Trained SOM (`trained_som_map.png`)**: Shows final organization of neurons.

## How to Run
1. **Install dependencies:**
   ```sh
   pip install numpy pandas matplotlib minisom

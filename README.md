# Spatio-Temporal Hybrid Model for Predicting Charging Demand
A spatio temporal hybrid model for predicting the charging demand at charging stations. The model is developed with the intent to evaluate the charging demand at charging stations placed at new locations i.e. without historical time series data. The model is a hybrid between a Graph Neural Network (GNN) and a Gated Recurrent Unit (GRU). 

This project is part of a [Master's thesis](https://drive.google.com/file/d/1vEmE8zrYc0tsoD0ofon-V_XChAVflzZC/view?usp=sharing) in Computer Engineering and is an addition to another project focusing on [forecasting the charging load on public electric charging stations](https://github.com/wblachowski/bhmsds?fbclid=IwAR2WbJRLMxecP4a41iTjJR-_idug6anFvjFdz8XyinaZV7gA8OFwaah7MR8). 


## Contents
The dataset consists of time series data from 392 charging stations, where the model has been tested on three out of the 392 charging stations. There are three different implementations of the hybrid model, which differ in their training strategy: 1) Using the original time series data for all 392 charging stations. 2) Replacing the time series data from the three test charging stations with zeroes (Used to mimic placing a charging station without historical data. 3) Using synthetic data for the three test charging stations based on time series data from surrounding charging stations. 

The repository consists of the following three folders:
- Embeddings: This folder contains the node embeddings from the GNN model and the index mapping connecting the node embeddings to the correct charging station
- Models: Pre-trained models  
- Source: Source code for the GNN model and the three variations of the hybrid model. Additionally, the source code for creating synthetic data is also included.


## Prerequisites
- Python 3.7 or higher
- Jupyter Notebook 

Furthermore, the following packages and libraries are used in the project
- Pandas
- Numpy
- PyTorch
- Sympy
- SKLearn
- Torch_Geometric
- Folium
- Matplotlib

## Usage
1. 
2. 



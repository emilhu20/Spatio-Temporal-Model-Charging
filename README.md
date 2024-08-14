# Spatio-Temporal Hybrid Model for Predicting Charging Demand
A spatio temporal hybrid model for predicting the charging demand at charging stations. The model is developed with the intent to evaluate the charging demand at charging stations placed at new locations i.e. without historical time series data. The model is a hybrid between a Graph Neural Network (GNN) and a Gated Recurrent Unit (GRU). 

This project is part of a Master's thesis in Computer Engineering and is an addition to another project focusing on [forecasting the charging load on public electric charging stations](https://github.com/wblachowski/bhmsds?fbclid=IwAR2WbJRLMxecP4a41iTjJR-_idug6anFvjFdz8XyinaZV7gA8OFwaah7MR8).


## Contents
The model has been trained on 392 charging stations, w
There are three different implementations of the hybrid model: 1) Using  using . 2) . 3)

There are three folders: 
- Embeddings: This folder contains the node embeddings Folder containing the embeddings from the One containing the CNN model without KD (project.ipynb) and one implementing the KD network (project_optimized.ipynb) 
- Data: for evaluating the calculator 
- Source: Pretrained models of the teacher, student and KD student 

## Prerequisites
- Python 3.7 or higher
- Jupyter Notebook 

Furthermore, the following packages and libraries are used in the project
- Pandas
- Numpy
- PyTorch
- Sympy
- Imutils
- Matplotlib

## Usage
1. If you want to train new models, run the project_optimized.ipynb from the start.
2. If you want to evaluate the pretrained models (or newly trained models), run the cells from the "Testing" section. 



# Movie Recommendation with Graph Neural Networks

Movie Recommendation with Graph Neural Networks is a project that demonstrates how to build a movie recommendation system using Graph Neural Networks (GNNs) and PyTorch Geometric. This system uses the MovieLens 100k dataset to recommend movies to users based on their historical preferences.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Model](#model)
- [Training](#training)
- [Recommendations](#recommendations)
- [Contributing](#contributing)

## Introduction

Movie recommendation systems are widely used in today's digital entertainment platforms. This project aims to create a recommendation system using Graph Neural Networks, a powerful technique for modeling structured data like user-item interactions.

## Requirements

Before running the code, ensure you have the following dependencies installed:

- Python 3
- PyTorch
- PyTorch Geometric
- Pandas

You can install these requirements using the following command:

## Getting Started
To get started with the project, follow these steps:

Clone this repository:

git clone https://github.com/your-username/movie-recommendation-gnn.git
cd movie-recommendation-gnn

Download the MovieLens dataset:
wget "http://files.grouplens.org/datasets/movielens/ml-100k/u.data"

## Usage
The project consists of the following main components:

## Data Processing
The MovieLens dataset is loaded using Pandas, and user-item interactions are processed into a graph structure.

## Graph Neural Network Model
A GNN-based recommendation model is defined using PyTorch Geometric. It consists of two Graph Convolutional Network (GCN) layers.

## Training
The GNN model is trained using an autoencoder approach to minimize the Mean Squared Error (MSE) loss.

## Recommendations
After training, the model generates movie recommendations for users based on learned embeddings.

## Model
The recommendation model is defined in the RecommenderGNN class, utilizing GCN layers for graph-based feature extraction.

## Training
The training loop runs for a specified number of epochs, optimizing the model to predict user-item interactions.

## Recommendations
The trained model is evaluated, and movie recommendations for each user are generated.

## Contributing
Contributions to this project are welcome! Feel free to open issues or pull requests to improve the code or add new features.




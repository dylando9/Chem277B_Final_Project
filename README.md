# Prediction of Molecular Energies using Supervised Learning ANN Model

This repository contains the code and resources for predicting molecular energies using a supervised learning Artificial Neural Network (ANN) model applied to the ANI-1 dataset. The project was carried out as part of UC Berkeley's Chem 277B (Machine Learning Algorithms) course.

## Project Overview

This project focuses on predicting the potential molecular energies of organic molecules using a deep neural network called the Accurate NeurAI Network Engine (ANI). The model is trained on the ANI-1 dataset, which includes molecular information such as species, coordinates, and energies.

### Key Features

- Utilizes the ANI-1 dataset containing organic molecules with H, C, N, and O atoms.
- Implements a deep neural network using the PyTorch framework.
- Transforms molecular information into Atomic Environment Vectors (AEVs) for model input.
- Employs the ANITrainer class to handle training, optimization, and evaluation of the model.
- Fine-tunes hyperparameters such as batch size, learning rate, epochs, and L2 regularization to achieve optimal performance.

## Getting Started

### Prerequisites

Ensure you have the following software installed:

- Python 3.7 or later
- PyTorch
- h5py
- NumPy
- Matplotlib


### Dataset

Download the `ani_gdb_s01_toS04.h5` dataset and place it in the `data` directory.

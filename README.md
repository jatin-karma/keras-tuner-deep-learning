# Neural Network Hyperparameter Tuning for Diabetes Classification

A practical deep learning project that demonstrates how to optimize a neural network for binary classification using Keras Tuner. The workflow starts with a simple baseline model and progressively explores hyperparameters such as hidden units, depth, activations, optimizers, and dropout regularization.

## Overview

This project illustrates a step-by-step approach to hyperparameter tuning in Keras:

1. Build a baseline neural network
2. Tune the number of neurons in hidden layers
3. Tune the number of hidden layers
4. Run a broader search over architecture and optimization settings
5. Compare results and select the best-performing model

## Tech Stack

- Python
- TensorFlow / Keras
- Keras Tuner
- Scikit-Learn
- Pandas
- Matplotlib

## Dataset

The notebook uses a diabetes classification dataset and applies preprocessing, feature scaling, and train/test splitting before training the models.

## Workflow

- Load and inspect the dataset
- Separate features and target
- Standardize the input features
- Split data into training and testing sets
- Train a baseline model
- Use Keras Tuner to search for better configurations
- Evaluate the best model and interpret results

## Project File

- `keras_Hyperparameter_tuner.ipynb` — complete notebook with the full tuning workflow

## Purpose

This repository is intended for learning and experimentation in model tuning, especially for anyone looking to understand how Keras Tuner can be used to improve neural network performance systematically.

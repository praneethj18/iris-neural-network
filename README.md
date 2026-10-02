# Iris Classification using Neural Network

## Project Overview

This project uses a Neural Network built with TensorFlow and Keras to classify Iris flowers into three different species.

## Dataset

The Iris dataset contains 150 samples with 4 features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target classes:

- Setosa
- Versicolor
- Virginica

The dataset is loaded directly using Scikit-learn.

## Workflow

Dataset
↓
Data Preprocessing
↓
Train/Test Split
↓
Neural Network
↓
Training
↓
Validation
↓
Evaluation
↓
Prediction

## Neural Network Architecture

- Input Layer: 4 features
- Hidden Layer 1: 16 neurons with ReLU
- Hidden Layer 2: 8 neurons with ReLU
- Output Layer: 3 neurons with Softmax

## Training

The model was trained using:

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 40
- Batch Size: 8
- Validation Split: 20%

## Evaluation

The model was evaluated using:

- Test Accuracy
- Test Loss
- Confusion Matrix
- Training and Validation Loss
- Training and Validation Accuracy

## Prediction

The trained model can predict the species of a new Iris flower based on its four measurements.

## Saved Model

The trained neural network is saved as:

`iris_neural_network.keras`

## Technologies

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Files

- `day11_final.ipynb` — Jupyter Notebook
- `iris_neural_network.keras` — Saved Neural Network
- `README.md` — Project Documentation
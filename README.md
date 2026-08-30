# Parking Occupancy Classification

Academic project developed for **PSI3471 – Fundamentos de Sistemas Eletrônicos Inteligentes** at the Escola Politécnica da Universidade de São Paulo (USP).

## Overview

Development of a **Deep Learning model to classify parking spaces as available or occupied from images**.

The project combines computer vision techniques, dataset preparation, convolutional neural networks and model evaluation.

## Approach

The pipeline includes:

1. Reading parking-space annotations from XML files
2. Extracting individual parking spaces from images
3. Applying perspective transformation to standardize parking-space regions
4. Preparing and normalizing the dataset
5. Training a Convolutional Neural Network
6. Evaluating the model on validation and test data

## Technologies

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- scikit-learn
- Matplotlib

## Model Evaluation

The model was evaluated using classification metrics on validation and test datasets, including:

- Accuracy
- Precision
- Recall
- F1-score
- AUC
- Confusion matrix

## Dataset

The dataset is not included in this repository.

To run the notebook, place the training and test data under:

```text
data/
├── train/
└── test/

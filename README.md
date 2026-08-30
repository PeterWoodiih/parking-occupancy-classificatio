# Parking Occupancy Classification

Academic project developed for **PSI3471 – Fundamentos de Sistemas Eletrônicos Inteligentes** at the Escola Politécnica da Universidade de São Paulo (USP).

## Overview

This project develops a Deep Learning model to classify parking spaces as **available** or **occupied** from images.

The workflow combines image preprocessing, dataset construction, Convolutional Neural Networks and model evaluation.

## Approach

The pipeline includes:

1. Reading parking-space annotations from XML files
2. Extracting individual parking spaces from images
3. Applying perspective transformation to standardize the parking-space regions
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

## Repository

- `parking_occupancy_classification.ipynb` — cleaned and organized project notebook
- `requirements.txt` — Python dependencies
- `.gitignore` — files and directories excluded from version control

## Dataset

The dataset is not included in this repository.

To run the notebook, place the training and test data under:

```text
data/
├── train/
└── test/
```

and adjust the paths in the notebook if necessary.

## Academic Context

**Course:** PSI3471 – Fundamentos de Sistemas Eletrônicos Inteligentes  
**Institution:** Escola Politécnica da Universidade de São Paulo (USP)

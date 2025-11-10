# yalong_eece5644_hw3
**Author:** Anthony Yalong  
**NUID:** 002156860  
**Course:** EECE5644

## Assignment Overview
This repository contains the Python implementations, mathematical derivations, and report for Homework 3.

## Project Directory
```
yalong_eece5644_hw3/
├── problem1/                  # Contains all relevant synthesized work for Question 1
├── problem2/                  # Contains all relevant synthesized work for Question 2
├── .gitignore                 # GitHub formatting
├── README.md                  # This file
└── yalong_eece5644_hw3.pdf    # Complete report with results and analysis
```

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- TensorFlow/Keras
- scikit-learn
- SciPy

## Implementation Details

### Question 1: Multi-Layer Perceptron Classification
- Implementation of MLP classification with 10-fold cross-validation
- Comparison against theoretical optimal MAP classifier
- Analysis across training set sizes: 100, 500, 1000, 5000, 10000 samples

### Question 2: GMM Model Order Selection
- Implementation of EM algorithm for GMM parameter estimation
- 10-fold cross-validation for model order selection (K=1 to K=10)
- Statistical analysis across 100 trials for dataset sizes: 10, 100, 1000 samples

## Documentation
Complete analysis, mathematical derivations, results, and discussion are available in `yalong_eece5644_hw3.pdf`.

## Running the Code
Open the Jupyter notebooks in Google Colab.
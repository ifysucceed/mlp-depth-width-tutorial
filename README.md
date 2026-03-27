# Understanding Neural Network Design: How Depth and Width Affect Multilayer Perceptron Performance

## Overview
This project explores how the depth (number of layers) and width (number of neurons) of a Multilayer Perceptron (MLP) affect its performance.

The goal is to understand how model complexity influences accuracy and generalisation.

## Dataset
The Breast Cancer Wisconsin dataset from scikit-learn is used. It contains 569 samples with 30 numerical features and a binary classification target, where 0 represent malignant tumors and 1 represents benign tumors.

## Key Experiments
- Effect of depth (1–4 hidden layers)
- Effect of width (8–64 neurons)
- Overfitting analysis (training vs testing accuracy)
- Improved model using regularisation

## Results
- Best performance achieved with moderate model complexity
- Larger models showed clear signs of overfitting
- Regularisation techniques improved generalisation

## How to Run
1. Install required libraries:
   
   pip install -r requirements.txt

3. Run the Jupyter Notebook:
   
   jupyter notebook MLP_depth vs width.ipynb

## Author
Chukwufumnaya Favour Nonum

## License
This project is licensed under the MIT License.

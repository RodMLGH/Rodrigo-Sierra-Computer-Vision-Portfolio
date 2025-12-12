# Classic Machine Learning

## Problem Statement

This project shows how to build an image classification system using classical machine learning instead of deep learning.

## Approach

Loaded a small face dataset and split it into training, validation, and test sets.
Extracted features using:
HOG (Histogram of Oriented Gradients)
LBP (Local Binary Patterns)

Trained multiple classical ML models:
SVM
Random Forest

Compared two training strategies:
A reasonable model with good generalization
An overfitted model with 99% training accuracy but poor real-world performance

Evaluated and analyzed the results with validation accuracy.

## Results

Best model: SVM + HOG
Because it had the highest validation accuracy and the smallest difference between training and validation, showing it generalizes well.
Random Forest had very high training accuracy but lower validation accuracy, which shows overfitting.
The project clearly shows how training methods affect real-world performance.

## Key Findings

Having high training accuracy does not guarantee the model will perform well on new data.
HOG features detect edges and shapes that help recognize faces.
SVM works well for small datasets if the features are well designed.
Overfitting happens when the model memorizes the data instead of learning patterns.
Validation accuracy is more important than training accuracy.

## Technologies

I used these technologies in the lab: Python, NumPy, Seaborn, Scikit-learn, Matplotlib, Colab.

## How to run

Follow the instructions provided by teacher: Google Colab, upload the notebook, run the cells in order.

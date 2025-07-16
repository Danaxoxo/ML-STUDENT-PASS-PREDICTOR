# Student Math Performance Predictor

This machine learning project aims to predict whether a high school student will pass or fail their final math grade (G3) using a variety of classification models.

## Project Objective

The goal was to develop an accurate prediction model while addressing the issue of **overfitting** — ensuring the model performs well on unseen data, not just the training set.

## Techniques Used

The following models were implemented and evaluated:

- Decision Tree (Unpruned and Pruned)
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

All models were trained and tested on the same dataset to allow a fair comparison.

##  Workflow

- Importing libraries and loading the dataset
- Data cleaning and encoding
- Splitting data into training and testing sets
- Scaling data (for SVM and KNN)
- Training models and generating predictions
- Evaluating model performance using accuracy, precision, recall, F1 score
- Applying pruning to improve Decision Tree generalization
- Visualizing results and printing final accuracy comparison

## Repository Files

- `MachineLearningProject.ipynb` – Full Jupyter notebook with code and analysis
- `DATASET.md` – Dataset explanation and source
- *(Optional)* `student-mat.csv` – Dataset file, if you choose to include it

## Dataset Notice

The dataset is not included in this repository. See `DATASET.md` for details on how to obtain it.
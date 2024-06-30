# K-Nearest Neighbors (KNN) Classification

This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm using the sklearn library on the Digits dataset.

## Output


https://github.com/sarvesh-2109/KNN/assets/113255836/5c3afb68-b948-4eda-afb7-49a9b9e376a1



## Project Overview

K-Nearest Neighbors is a simple, non-parametric, and lazy learning algorithm that is used for classification and regression. The algorithm classifies new cases based on a similarity measure (distance functions).

### Dataset

The Digits dataset contains images of hand-written digits (0-9) and is widely used for classification purposes. Each image is represented as an 8x8 matrix, where each element corresponds to the pixel intensity.

### Objectives

- Load and explore the dataset.
- Implement the KNN algorithm for classification.
- Evaluate the model using confusion matrix and classification report.

## Libraries Used

- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Implementation

1. **Data Loading and Preprocessing**:
   - The dataset is loaded using `load_digits()` from `sklearn.datasets`.
   - The data is split into features and target labels.

2. **Model Training**:
   - The dataset is split into training and testing sets.
   - The KNN model is trained with `n_neighbors=5`.

3. **Model Evaluation**:
   - The model's accuracy is assessed on the test set.
   - A confusion matrix and classification report are generated to evaluate the model's performance.

## Results

- The confusion matrix and classification report provide insights into the model's precision, recall, and F1-score across different classes.


## Conclusion

KNN is a straightforward algorithm that can achieve good performance on various datasets. The results of this project illustrate the algorithm's effectiveness in classifying handwritten digits.

# Sonar Rock vs Mine Classification

This project is aimed at classifying objects as either rocks or mines using Sonar data. The dataset is processed and a Logistic Regression model is trained to perform the classification.

## Project Workflow

1. **Step 1:** Load Sonar data, perform data preprocessing, and split the dataset into training and test sets.
2. **Step 2:** Train a Logistic Regression model on the training set.
3. **Step 3:** Use the trained model to classify new data as either Rock (R) or Mine (M).

## Dataset

The dataset used in this project is Sonar Data, which consists of 60 sonar signal attributes for objects and their corresponding labels (R for Rock, M for Mine).

## Libraries Used

- `numpy`
- `pandas`
- `scikit-learn`

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/xNart06/sonar-rock-vs-mine.git
2. Install the required libraries:
3. Open the Jupyter Notebook and run all the cells to train the model

## Model
The model used for classification is Logistic Regression.
The dataset is split into training and testing sets using an 80-20 ratio.
Accuracy is evaluated using the accuracy_score from scikit-learn.

## Results
The model achieves an accuracy of approximately [add accuracy] on the test set.

## Future Work
Explore different classification algorithms like Decision Trees, SVM, and Neural Networks.
Perform hyperparameter tuning to improve model performance.

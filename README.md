# Employee Attrition & Department Classification Project

## Overview
This project aims to predict employee attrition and department classification using a deep learning model. It processes features related to employee demographics, job characteristics, and the work environment to make predictions about whether an employee is likely to leave the company (attrition) and to which department they belong.

## Data Preprocessing
The preprocessing stage involved handling categorical variables, normalizing numerical features, and splitting the data into training and testing sets. Categorical variables such as 'OverTime', 'Department', and 'Attrition' were handled through one-hot encoding.

## Model Architecture
The architecture is a multi-output neural network developed using TensorFlow's Keras API. It features shared layers for processing common features and diverges into two separate outputs for attrition and department classification predictions.

## Training
The model was trained on a combined loss function incorporating both output losses. It aimed to optimize accuracy, with distinct accuracy metrics for department and attrition predictions.

## Evaluation
Evaluation on the test dataset revealed specific accuracy metrics for both department and attrition predictions, indicating the model's performance on unseen data.

## Code Source and Assistance
All code in this repository was authored by the project contributor with assistance from Data Insight AI, a GPT customized by the contributor. This project did not involve direct collaboration with others or use of external code sources.

## Discussion
- **Accuracy as a Metric:** Considering the potential imbalance in the dataset, the appropriateness of accuracy as a metric is discussed, evaluating its reliability for both outputs.
- **Activation Functions:** Justification for the choice of activation functions for the output layers is provided, considering the specific needs of each prediction task.
- **Improvements:** Suggestions include data augmentation, hyperparameter tuning, and exploration of more complex model architectures to enhance prediction accuracy.

## Summary
This project demonstrates the application of deep learning to human resource analytics, using a neural network for multi-output classification. It highlights the potential of such models in predicting employee attrition and department alignment, with avenues for future enhancements to improve prediction accuracy further.
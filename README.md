# Glassdoor Review Rating Prediction

This repository contains a machine learning project designed for a prediction competition. The task involves predicting overall ratings of companies from Glassdoor reviews based on features constructed from the data. The model achieved **1st place** in the competition with an impressive accuracy of **0.87**.

## Project Overview
The competition provided training and test datasets with varying sizes:
- Training sets:
  - Small: 100,000 observations.
  - Large: 500,000 observations (not a superset of the small set).
- Test set: 100,000 observations (without response variable).

Participants were required to:
1. Handle missing feature values to ensure predictions for all test set entries.
2. Construct features and train machine learning models.
3. Evaluate performance using mean squared error (MSE) and R².

### Tasks Performed
1. **Feature Engineering**:
   - Processed Glassdoor review data to create predictive features.
   - Addressed missing values to include all test set entries.
2. **Model Training and Evaluation**:
   - Trained models using both training datasets.
   - Achieved 1st place in the competition with **0.87 accuracy**.
   - Reported metrics:
     - MSE on the test set.
     - R² on the training set.
3. **Model Visualization**:
   - Included a figure illustrating the model structure and input features.

## Results
- **Accuracy**: 0.87
- **Rank**: 1st place in the competition

## Files
- `model_training.py`: Code for feature engineering, model training, and evaluation.
- `results_visualization.pdf`: Contains the figure showing the model structure and features used as inputs.
- `predictions.csv`: Final predictions for the test set.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Glassdoor_Review_Rating_Prediction.git

# Glassdoor Review Rating Prediction

This repository contains the code and results for a prediction competition focused on predicting review ratings from Glassdoor data. The competition involved constructing features from textual reviews and training machine learning models to achieve the best performance measured by mean squared error (MSE). 

## Project Overview
In this competition, I utilized advanced machine learning techniques to predict overall review ratings from structured and textual data. The tasks included:
1. Preprocessing textual reviews and constructing meaningful features.
2. Building and optimizing machine learning models, including a BERT-based regression model.
3. Reporting performance metrics (MSE and R²) for training and test sets.
4. Visualizing the model structure and input features.

### Achievements
- **Ranked 1st** in the competition with a score of **0.87** (R²).
- Demonstrated expertise in:
  - Preprocessing and tokenizing a dataset of 600,000 reviews for compatibility.
  - Leveraging deep learning frameworks and optimization techniques for accurate predictions.

### Competition Details
- **Training Data**: Two datasets with 100,000 and 500,000 observations, not subsets of each other.
- **Test Data**: 100,000 observations without response variables.
- **Challenge**: Make predictions for all test observations, even with missing feature values.

### Key Techniques
- Constructed features using advanced embedding techniques.
- Utilized a BERT regression model for textual data analysis.
- Applied preprocessing, tokenization, and imputation strategies for missing values.

### Included Files
1. **`prediction_model.py`**: Python file containing the preprocessing steps, model training, and prediction logic.
2. **`model_structure.pdf`**: A figure illustrating the model structure and input features.
3. **`competition_results.pdf`**: Detailed competition results, including evaluation metrics and ranking.

### How to Run
1. Clone this repository.
2. Install required dependencies listed in `requirements.txt`.
3. Run the Python script to reproduce the results.

### Insights
This project highlights the importance of:
- Advanced NLP techniques in predictive modeling.
- Effective handling of missing data and large-scale datasets.
- Model explainability through visualization and metrics reporting.

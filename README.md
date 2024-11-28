
markdown
Skopiuj kod
# Sonar Data Classification Project

This project is a beginner-level implementation of data science and machine learning techniques to classify objects as either rocks (R) or mines (M) using sonar data. It leverages logistic regression for classification and includes steps for data exploration, preprocessing, and evaluation.

## Dataset

The dataset contains 208 samples, each with 60 numerical features representing sonar signal strength at various frequencies. The target variable indicates whether the object is a rock (`R`) or a mine (`M`).

### Key Statistics
- **Shape:** 208 rows, 61 columns (60 features + 1 target column)
- **Class Distribution:**
  - Rocks (R): 97 samples
  - Mines (M): 111 samples

## Methodology

1. **Data Exploration:**
   - Inspected dataset structure and statistical summaries.
   - Examined class distributions and feature means grouped by the target variable.

2. **Preprocessing:**
   - Split the data into training and test sets using a stratified approach to preserve class balance.
   - Training set size: 197 samples  
   - Test set size: 11 samples  

3. **Modeling:**
   - Logistic Regression was chosen as the classifier.
   - The model was trained on the training dataset.
   - Performance metrics (accuracy) were calculated on both training and test sets.

4. **Evaluation:**
   - **Training Accuracy:** ~83.76%  
   - **Test Accuracy:** ~72.73%  

5. **Feature Selection (Planned):**
   - Implemented a function to identify the best subset of features using combinations and residual sum of squares (RSS).

## Results

- Logistic regression provided a reasonable baseline for sonar object classification.
- Feature selection techniques are included for further exploration of model optimization.

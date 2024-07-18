# TODO

### This file is to document any action items and potential next steps. Please list below.

---

1. Approach data preprocessing, including data cleaning (not neccessary), imputation and feature scaling and feature selection
    - Consider **mean imputation** for normal distribution; Otherwise, consider **median imputation** or **log transformation** for highly skewed data
    - **Standard Scaling** for normal distribution; Otherwise, **Min-Max Scaling** to bring all features into the same range (0, 1)
    - Feature selection (Pending completion)
        - Correlation Analysis: Remove highly correlated features to avoid redundancy.
        - Univariate Selection: Select features based on statistical tests.
        - Model-Based Selection: Use models to determine the importance of features.
        - Use “explained_variance_ratio” to determine how many features to keep.

2. Add more eda methods potentially in accordance to Step 1. 
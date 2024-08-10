# TODO

### This file is to document any action items and potential next steps. Please list below.

---

1. Determine if feature selection is needed by checking correlation matrix after PCA
    - Feature selection
        - Univariate Selection: Select features based on statistical tests.
        - Model-Based Selection: Use models to determine the importance of features.

2. Consider EDA on transformed data; Approach clustering

3. Refine bagging and boosting

4. Consider data preprocessing from a time series/signal processing aspect and implement the following:
    - Low pass filter or high pass filter
        - High pass filter is working. In the preprocess.ipynb, updates are only made until Log Transformation. Still need to check any updates have to be done for dimensionality reduction. 

5. Consider feature engineering ideas:
    - Local min max given window size
    - Signal freq
    - ...


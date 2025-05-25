# Implementation Details

## Data Source and Preprocessing
- Dataset: 27,874 instances, 43 features encompassing air pollutant levels, meteorological variables, and health indicators.
- Data cleaning involved handling missing values and outliers.
- Feature scaling and normalization prepared data for modeling.

## Feature Engineering
- Feature selection techniques applied: MRMR, Chi-Squared, ANOVA, and Kruskal-Wallis Test.
- ANOVA outperformed other methods in selecting features that maximized the neural network's accuracy.
- Optimal feature count was determined to be 15, balancing model complexity and performance.

## Modeling Approaches
- Baseline classifiers: Logistic Regression, SVM, and Naive Bayes.
- An optimized Neural Network model trained and tuned with selected features.
- Stratified cross-validation ensured robustness and reliability of results.

## Tools and Languages
- Data preprocessing,feature engineering,Model building and evaluation : MATLAB and Python.
- Visualization: Python libraries such as matplotlib and seaborn.

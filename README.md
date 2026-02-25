This code performs breast cancer classification using Logistic Regression. It first imports necessary libraries for data handling, visualization, and machine learning. The Breast Cancer dataset is loaded from scikit-learn, and features (X) and target labels (y) are separated.

The code calculates the correlation between each feature and the target variable using `corrwith()` and visualizes the results with a heatmap. A function `run_logistic_regression()` is defined to split the data into training and testing sets, train a Logistic Regression model, and evaluate it using metrics such as Accuracy, Precision, Recall (Sensitivity), Specificity, F1-score, and ROC-AUC. It also plots a Confusion Matrix and ROC curve.

Finally, the model is trained twice: once using highly correlated features (|correlation| > 0.6) and once using weakly correlated features (|correlation| < 0.3), allowing performance comparison based on feature relevance.

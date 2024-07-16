#Machine Learning Model Comparison on the Iris Dataset
Overview
This project compares the performance of four different machine learning models on the Iris dataset. The models used are:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
Dataset
The dataset used for this project is the Iris dataset, which is a classic dataset in machine learning. It consists of 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The target variable has three classes: setosa, versicolor, and virginica.

Preprocessing
Standardization: The features are standardized using StandardScaler from the sklearn library to ensure they have a mean of 0 and a standard deviation of 1.
Train-Test Split: The dataset is split into training and testing sets using an 80-20 split.
Models
The following models are used in this project:

Logistic Regression: A linear model used for binary classification, extended here to multi-class classification using a one-vs-rest approach.
Decision Tree Classifier: A non-linear model that splits the data into subsets based on feature values.
Random Forest Classifier: An ensemble model that builds multiple decision trees and merges their results to improve accuracy and control overfitting.
Support Vector Machine (SVM): A linear model that finds the hyperplane that best separates the classes in the feature space.
Evaluation Metrics
The models are evaluated using the following metrics:

Accuracy: The ratio of correctly predicted instances to the total instances.
Precision: The ratio of correctly predicted positive observations to the total predicted positives.
Recall: The ratio of correctly predicted positive observations to all observations in the actual class.
F1-Score: The weighted average of Precision and Recall.

Results
The performance of each model is summarized in the table below:
| Model                | Accuracy | Precision | Recall | F1-Score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression  | 0.967    | 0.968     | 0.967  | 0.967    |
| Decision Tree        | 0.967    | 0.968     | 0.967  | 0.967    |
| Random Forest        | 0.967    | 0.968     | 0.967  | 0.967    |
| Support Vector Machine | 1.000    | 1.000     | 1.000  | 1.000    |

Cross-Validation (Commented Out)
For a more robust evaluation, cross-validation can be performed. This involves splitting the dataset into multiple training and testing sets and averaging the results. The cross-validation accuracy for each model is printed in the commented section of the code.
Conclusion
This project demonstrates the process of training and evaluating multiple machine learning models on a well-known dataset. The results show that all models perform well on the Iris dataset, with SVM achieving perfect scores. Cross-validation can provide further insights into the models' robustness and generalization capabilities.

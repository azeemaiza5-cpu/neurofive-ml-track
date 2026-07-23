&#x20;Titanic Survival Prediction - ML Track



&#x20;Approach

This project performs exploratory data analysis (EDA) and builds a machine learning model to predict passenger survival on the Titanic.



Steps:

1\. Loaded and cleaned the Titanic dataset (handled missing values in Age, Embarked, and Cabin)

2\. Performed EDA with visualizations (histogram, boxplot, bar chart, correlation heatmap)

3\. Encoded categorical features (Sex, Embarked) using one-hot encoding

4\. Split data into training (80%) and test (20%) sets

5\. Trained a Logistic Regression model using scikit-learn

6\. Evaluated using accuracy score and a confusion matrix



&#x20;Results

\- \*\*Model:\*\* Logistic Regression

\- \*\*Accuracy:\*\* \~81%

\- \*\*Confusion Matrix:\*\*

&#x20; - True Negatives: 90

&#x20; - False Positives: 15

&#x20; - False Negatives: 19

&#x20; - True Positives: 55



The model performs reasonably well, correctly predicting survival outcomes for the majority of test passengers, with slightly more errors in identifying survivors than non-survivors.


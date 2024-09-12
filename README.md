# Credit Card Fraud Detection Model
This project is focused on detecting fraudulent credit card transactions using machine learning models. The dataset contains anonymized features and the goal is to classify whether a transaction is legitimate (Class 0) or fraudulent (Class 1).


**Introduction**
Credit card fraud is a major concern for financial institutions and cardholders. In this project I built a predictive model to classify transactions as either fraudulent or legitimate using various machine learning techniques, with the goal of improving accuracy and detecting fraudulent transactions effectively.


**Dataset**
The dataset used is highly imbalanced, with only a small fraction of the transactions being fraudulent. The features have been anonymized for privacy reasons.

 Key columns include:

- Time: Time elapsed between the transaction and the first transaction in the dataset.

- Amount: Transaction amount.

- Class: 1 indicates a fraudulent transaction, 0 indicates a legitimate transaction.
The dataset contains 284,807 transactions and 31 columns.


**Exploratory Data Analysis**
1. Check for null values and basic statistics.

2. Visualize the distribution of legitimate vs. fraudulent transactions.

3. Analyze transaction amounts in both classes (legitimate vs. fraud).


**Key Findings**
The dataset is highly imbalanced (fraudulent transactions are a small fraction).
Legitimate transactions have a higher average transaction amount than fraudulent ones.


**Models used**
Logistic Regression: A simple linear model used as a baseline.
Decision Tree: A tree-based model that splits data into branches to make predictions.
Random Forest: An ensemble method that combines multiple decision trees to improve performance.
XGBoost: A gradient-boosting algorithm that builds trees sequentially, optimizing accuracy.
Model Training and Evaluation
Each model is trained on the training data and evaluated on both the training and test sets.



**ROC Curve and AUC**
ROC (Receiver Operating Characteristic) curves and AUC (Area Under Curve) scores are used to evaluate the model's ability to distinguish between classes.


**Conclusions**
The dataset is highly imbalanced, but downsampling helped in improving the model's performance.
Among the models, XGBoost provided the best results with a higher accuracy, precision, recall, and AUC score.
This model can be fine-tuned further or enhanced with techniques like feature engineering, hyperparameter tuning, or using advanced models.

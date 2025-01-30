# Credit Card Customer Segmentation 
The goal of this project is to create a machine learning model that can accurately detect fraudulent credit card transactions. Fraudulent transactions can lead to financial losses for both businesses and customers, so it's crucial to identify them quickly. The dataset contained 568,629 transactions out of which were fraudulent (1) or normal transactions (0). 	
# Algorithms Used
Models like Random Forest, Logistic Regression, or XGBoost were used since they handle both linear and non-linear relationships and perform well in binary classification tasks. 
1.	Random Forest is often a strong candidate due to its ability to handle complex   patterns and feature interactions.
2.	Logistic Regression and SVM are simpler models that could also perform well if the relationships in the data are relatively straightforward.
3.	XGBoost is an advanced method that might outperform others if you're looking for top-tier performance.

After  training and testing several models,  their performance when compared using metrics like accuracy, precision, recall, or mean squared error (MSE) to choose the best-performing one.
# Common Workflow
1.	Exploratory Data Analysis (EDA): Understand the data and its features.
2.	Preprocessing: Clean and prepare the data for analysis.
3.	Model Training:
o	Train multiple models (e.g., logistic regression, random forest, support vector machine, etc.).
o	Split the dataset into training, validation, and testing subsets.
4.	Model Evaluation:
o	Compare performance metrics for all models.
Key Metrics and Graphs
# Visualization
•	Confusion Matrix:
o	The Confusion Matrix helps us visualize how well the model is classifying transactions. It shows how many fraudulent transactions (fraudulent or legitimate) are correctly or incorrectly predicted by the model. The matrix has four parts:
	True Positive (TP): Correctly identified fraud.
	True Negative (TN): Correctly identified legitimate transactions.
	False Positive (FP): Legitimate transactions wrongly identified as fraud.
	False Negative (FN): Fraudulent transactions wrongly identified as legitimate.
o	By understanding the confusion matrix, we  assessed how many fraud cases were missed (False Negatives) or incorrectly flagged as fraud (False Positives).
•	ROC Curve was used to measure how well the model distinguishes between fraud and legitimate transactions. It plots the True Positive Rate (sensitivity) against the False Positive Rate (1 - specificity). A score closer to 1 indicates a better model, while a score closer to 0.5 suggests the model is not performing well.
o	ROC AUC was used to measure the likelihood that the model ranks a randomly chosen fraudulent transaction higher than a randomly chosen legitimate transaction.
•	The Feature Importance Ranking graph shows the relative importance of each feature in predicting fraudulent transactions. For example, it might reveal that the transaction amount, location, or time of day is more important than other features in detecting fraud.
5.	Model Selection: Random Forest Classifier was chosen as the model that performs best and meets the project's requirements.


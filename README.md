# Credit Score Prediction
Problem Statement
The goal of this project is to develop a machine learning model using Python that accurately predicts the credit score of customers based on their financial and personal information. The model should handle large datasets, account for different credit reporting agency models, and be scalable for use in real-time credit scoring applications. By improving the accuracy of credit scores, the model aims to enhance lending decisions and identify high-risk customers.

Dataset Description
The Credit Score Classification dataset from Kaggle is used for this project. It is a publicly available dataset containing information on customer credit scores and other relevant attributes. The dataset consists of 100,000 records, each with 27 features, including the customer's ID, Name, AGE, Annual income, and Occupation, among others.

The target variable in this dataset is a binary classification label indicating whether a customer is likely to default on their loan (represented by a label of '1') or not (represented by a label of '0'). This dataset is commonly used by data scientists and machine learning practitioners to build predictive models for credit risk assessment, fraud detection, and other financial applications.

Conclusion
While Performing the Logistic Regression we obtained the Accuracy of the model to be 0.6349801930480389 to be precise.
While Performing the KNN with n value as 2, we obtained the Accuracy of the model to 0.7759626257215974 to be precise.
We can say that accuracy is increased to 0.7046360768910314 by doing the PCA reduction .

Therefore , We can say out of all KNN with n=2 , Gives us the best accuracy rate.

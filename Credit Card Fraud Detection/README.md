# **Credit Card Fraud Detection**

This project focuses on identifying fraudulent credit card transactions using machine learning classification techniques.

Credit card fraud detection is a critical real-world problem where the goal is to distinguish between genuine and fraudulent transactions based on transaction-related features.

The objective of this project is to build a reliable classification model that can accurately detect fraud while handling highly imbalanced data.

## **Dataset**

* Dataset Name: Credit Card Transactions Dataset

* Source: Credit Card Fraud Dataset

* Records: Large-scale transaction dataset

Features:

* Transaction Amount

* Time

* PCA-transformed numerical features (V1–V28)

## **Target Variable**

* Class

  * 0 → Legitimate Transaction

  * 1 → Fraudulent Transaction

## **Technologies Used**

* Python

* Jupyter Notebook

* Pandas

* NumPy

* Matplotlib

* Seaborn

* Scikit-learn

## **Machine Learning Models Used**

* Logistic Regression

* Random Forest Classifier

To handle class imbalance, techniques such as oversampling and undersampling were considered during model training.

## **Model Evaluation**

The models were evaluated using the following metrics:

* Precision

* Recall

* F1-Score

* Confusion Matrix

These metrics are crucial due to the imbalanced nature of fraud detection problems.

## **Sample Results**

* High accuracy on legitimate transactions
  * Training Accuracy : ~96-99%
  * Testing Accuracy : ~95-99%
    
* Improved recall for fraudulent transactions

## **Model Testing**

The trained model was tested on unseen transaction data to classify transactions as fraudulent or genuine.

## **Conclusion**

This project demonstrates the complete machine learning pipeline, including:

* Data loading

* Data preprocessing and normalization

* Handling class imbalance

* Model training

* Model evaluation

* Fraud prediction

It provides strong practical insight into solving real-world imbalanced classification problems using machine learning.

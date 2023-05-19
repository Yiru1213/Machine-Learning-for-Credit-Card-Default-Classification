# **Classification of Bank Account Risk -- Credit Default Prediction** 

## 1. Introduction

This project focuses on the binary classification of predicting whether a credit card client would default.

Specifically, we used 5 kinds of machine learning algorithms to train the model, which is based on attributes such as payment history, amount of credit, and demographic information.

![](images/%E5%9B%BE%E7%89%87-02.png){width="616"}

## **2. Learning Tasks**

### 1. Dataset, input and expected output

1) The dataset includes the 23 features and target.

2) The input features are numerical features, categorical features and ordinal features

3) The expected outputs are the correct class label based on the given input features.

### 2. Data processing and split

The raw dataset was split into the training (70%), validation (15%) and testing (15%) parts.

### 3. Machine learning model training

1) Decision Trees: Classification And Regression Trees (CART)

2) Instance-based Learning: K-Nearest Neighbor (KNN)

3) Bayesian: Naive Bayes

4) Neural Network: Multi-Layer Perceptron (MLP)

5) Model Ensemble: Stackink Bagging&Voting

### 4. Model evaluation methodology

-   Confusion matrix

-    Accuracy (ACC)

-   Precision

-   Recall

-   F1-score

-   Matthews Correlation Coefficient (MCC)

## 3. Conclusion

Based on the evaluation metrics and the context of credit default prediction, CART is seen as the best performing model. It not only achieves the highest accuracy but also maintains a good balance between the precision and the recall, which is crucial for making informed credit decisions and managing risk effectively.

## 4. Contributors

-   Dodo Wang

-   Jishuo Zhang

-   Haijin Li

-   Yiru Xu

-   Zonghe Ma

***Further detailed information can be found in the PDF file Credit Default Prediction Report***

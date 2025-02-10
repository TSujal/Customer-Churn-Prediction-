# Customer-Churn-Prediction-

## Project Overview
Customer churn is a critical issue for businesses, as losing customers directly impacts revenue and growth. This project aims to predict customer churn using an Artificial Neural Network (ANN) model. By analyzing customer behavior, transaction history, and demographic details, the model helps businesses identify customers who are likely to leave, allowing them to take proactive measures to retain them.

## Objective 
The goal of this project is to build a deep learning model using an ANN to predict whether a customer will churn (leave) based on historical data.

## Dataset
https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn
The dataset used contains customer details, such as:
Demographics: Age, Gender, Location
Account Information: Tenure, Services subscribed, Monthly charges
Payment Details: Payment method, Contract type
Churn Status: Whether the customer has left or not (target variable)
The dataset is preprocessed by handling missing values, encoding categorical variables, and scaling numerical features to optimize model performance.

## Model Architecture (ANN)
The Artificial Neural Network (ANN) consists of the following layers:

Input Layer: Accepts preprocessed features
Hidden Layers:
Fully connected layers with ReLU activation
Dropout layers to prevent overfitting
Output Layer:
Single neuron with sigmoid activation (binary classification)

## Training Process
The dataset is split into training and test sets
The model is compiled using binary cross-entropy loss and Adam optimizer
It is trained over multiple epochs, and early stopping is applied to prevent overfitting

## Evaluation Metrics
The model is evaluated using:

Accuracy: Measures the percentage of correctly classified customers
Precision & Recall: Determines how well the model identifies churners
F1-score: Balances precision and recall
Confusion Matrix: Provides insights into false positives and false negatives

## Results & Insights
The trained ANN model achieves high accuracy in predicting churn
Feature importance analysis shows that contract type, tenure, and monthly charges are the most significant indicators of customer churn
Businesses can use the model to implement targeted retention strategies, such as offering discounts or personalized promotions to high-risk customers

## Future Enhancements
Hyperparameter tuning to optimize model performance
Feature engineering to extract more meaningful insights
Integration with real-time dashboards for real-world deployment

## Conclusion
This project demonstrates how deep learning can be applied to customer churn prediction, helping businesses make data-driven decisions to improve customer retention. 🚀

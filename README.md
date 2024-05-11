 
# Financial Fraud Detection Model Analysis (Part-I)

## Overview
This project focuses on detecting financial fraud using a variety of machine learning and deep learning models. The dataset used contains transactional data with features such as transaction type, amount, and balance changes. The goal is to develop effective models that can accurately classify transactions as either fraudulent or non-fraudulent.

Link to the dataset: [Synthetic Financial Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1)

## Dataset
The dataset used in this project consists of transactional data containing the following features:
- Transaction type (e.g., debit, credit)
- Transaction amount
- Balance changes
- Other relevant transaction details

## Methodology
### Preprocessing
- Data cleaning: One-hot encoding and data normalization.
- Feature engineering: Dropping irrelevant features.

### Model Selection
The project explores both traditional machine learning models and deep learning architectures for classification:
#### Machine Learning Models:
1. Logistic Regression
2. Decision Tree
3. K-Nearest Neighbors (KNN)
4. Random Forest
5. Naive Bayes
6. XGBoost

#### Deep Learning Models:
1. Artificial Neural Network (ANN)
2. Convolutional Neural Network (CNN)

### Model Training and Evaluation
- Splitting the dataset into training and testing sets.
- Training each model using the training data.
- Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.
- Comparing the performance of different models to identify the most effective ones for fraud detection.

## Results
- Among the machine learning models, the Random Forest classifier demonstrated the best performance based on evaluation metrics.
- Within the deep learning models, the Convolutional Neural Network (CNN) showed promising results for fraud detection.
- Detailed analysis and interpretation of model performance, including confusion matrices and ROC curves.

## Contributors
- **Saket Kulkarni**
  - [GitHub](https://github.com/StrangeCoder1729)
  - [LinkedIn](https://www.linkedin.com/in/saketkulkarni1729)
  
- **Tirth Mehta**
  - [GitHub](https://github.com/TirthM21)
  - [LinkedIn](https://www.linkedin.com/in/mehta-tirth/)

## Deployed Model
- The trained model has been deployed using Flask for inference. Access the deployment repository [here](https://github.com/StrangeCoder1729/FinancialFraudDetector).

 
 

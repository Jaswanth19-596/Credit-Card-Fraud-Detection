# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. It utilizes a dataset containing transactions made by credit cards in September 2013 by European cardholders. The dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.

## Data Description

The dataset consists of the following columns:

- Time: The number of seconds elapsed between this transaction and the first transaction in the dataset.
- V1, V2, ..., V28: Principal components obtained with PCA.
- Amount: Transaction amount.
- Class: The target variable, where 1 indicates a fraudulent transaction and 0 indicates a normal transaction.

## Data Pre-processing

- The dataset is pre-processed to prepare it for modeling.
- StandardScaler is used to scale the features.
- The data is split into training and testing sets using train_test_split.

## Modeling

- Support Vector Classifier (SVC) is used to build the model.
- The model is trained on the training data.
- Model evaluation is performed on both training and testing data.

## Evaluation Metrics

- The model's performance is evaluated using classification report and confusion matrix.
- Precision, recall, and F1-score are calculated for both classes (fraudulent and normal transactions).
- A heatmap visualization of the confusion matrix is generated using seaborn.

## Results

- The model achieves high accuracy on both training and testing sets.
- However, the recall for detecting fraudulent transactions is relatively low, indicating that the model may miss some fraudulent cases.

## Conclusion

- This project demonstrates the use of machine learning techniques to detect credit card fraud.
- Further optimization of the model or exploration of other algorithms may improve the detection of fraudulent transactions.

## How to Use

1. Clone the repository:
  - git clone https://github.com/yourusername/credit-card-fraud-detection.git

2. Install the required dependencies:
  - pip install -r requirements.txt

3. Run the Jupyter notebook or Python script to execute the code.

4. Explore the results and evaluate the model's performance.

## Credits

- Dataset Source: [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)



  

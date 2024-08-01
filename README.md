# Credit Card Fraud Detection

## Project Overview

This project focuses on detecting fraudulent credit card transactions using various machine learning models. The dataset used for this project is obtained from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). The project includes Exploratory Data Analysis (EDA), data processing, and the implementation of different classification algorithms.

## Project Structure

- **`creditcard.csv.zip`**: The dataset containing credit card transactions, including both fraudulent and non-fraudulent transactions.
- **`FraudDetection.ipynb`**: Jupyter Notebook containing the code for EDA, data processing, model training, and evaluation.
- **`README.md`**: This file providing an overview of the project.

## Dataset

The dataset contains transactions made by credit cards in September 2013 by European cardholders. It presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

## Steps Involved

1. **Exploratory Data Analysis (EDA)**
   - Understanding the distribution of classes.
   - Visualizing data patterns and anomalies.
   - Analyzing correlations between features.

2. **Data Processing**
   - Handling missing values.
   - Scaling features.
   - Splitting data into training and testing sets.

3. **Model Implementation**
   - Logistic Regression
   - Naive Bayes
   - Random Forest

4. **Model Evaluation**
   - Calculating ROC AUC scores.
   - Plotting ROC AUC curves to compare model performance.

## Running the Project

1. **Ensure Required Libraries**: Make sure you have all the necessary libraries installed. You can install them using:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
2. **Navigate to the Project Directory**: Ensure you are in the project home directory where the `FraudDetection.ipynb` file is located.

3. **Unzip the Dataset**: Unzip the `creditcard.csv.zip` file to get the `creditcard.csv` file.

4. **Open the Notebook**: Use Jupyter Notebook or Jupyter Lab to open `FraudDetection.ipynb`.

5. **Run the Notebook**: Execute the cells in the notebook to perform EDA, data processing, model training, and evaluation.

## Conclusion

The **`Credit_Card_Fraud_Detection`** project demonstrates the application of various machine learning algorithms to detect fraudulent transactions. The project provides insights into the effectiveness of different models and their performance metrics.

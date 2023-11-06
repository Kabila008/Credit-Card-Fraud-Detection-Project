# Welcome to My Paypal
***

## Task
The problem at hand is credit card fraud detection, a critical concern for credit card companies and consumers alike. 
The challenge lies in identifying fraudulent transactions within a vast dataset containing legitimate and fraudulent transactions. 
The primary obstacle is the class imbalance, as fraudulent transactions are relatively rare, making it harder to train accurate models.

## Description
The provided Python code tackles this problem by implementing various data science and machine learning techniques. 
It loads and preprocesses the dataset, explores its characteristics, handles missing data, and visualizes class distribution. 
Multiple machine learning models, including logistic regression with balanced class weights, a random forest classifier, 
and a gradient boosting classifier were trained and evaluated. These models are used to detect and predict fraudulent transactions.

## Installation
The code doesn't require installation using npm or make. However, it relies on Python and several Python libraries, such as pandas, 
scikit-learn, matplotlib, and seaborn. You would need to have Python installed, and you can install the required libraries using pip:

    pip install pandas scikit-learn matplotlib seaborn


## Usage
To utilize this code, you need to follow these steps:

**Load Dataset:** Start by loading the dataset using the load_dataset function, providing the file path to your CSV file.

**Dataset Summary:** Use the dataset_summary function to print the first 15 rows, a statistical summary, and dataset dimensions, 
gaining an initial understanding of the data.

**Remove Null Values:** Employ the remove_null_values function to clean the data by removing rows with missing values.

**Class Distribution:** Visualize the distribution of non-fraudulent and fraudulent transactions with the plot_class_distribution function.

**Model Training and Evaluation:** Choose one of the provided machine learning models, such as logistic regression, random forest, or 
gradient boosting, to train and evaluate it on your dataset. The functions train_logistic_regression_with_balanced_weights, 
train_and_evaluate_rf_classifier, and train_and_evaluate_gb_classifier can be used for this purpose.

**Model Performance:** Assess the model's performance by examining metrics like accuracy, precision, recall, F1-score, ROC AUC, 
and average precision score. The code provides classification reports for a comprehensive evaluation.

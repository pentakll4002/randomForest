# 1. Problem Statement
#### "Trips & Travel.Com" is aiming to expand its customer base by introducing a new product: the Wellness Tourism Package. The goal is to optimize marketing strategies to efficiently target potential customers. Currently, the company offers 5 packages: Basic, Standard, Deluxe, Super Deluxe, and King, and 18% of customers purchased these packages last year. However, marketing costs have been high due to random customer contact without leveraging available customer data.

#### To reduce marketing expenditures, the company plans to launch the Wellness Tourism Package, which focuses on travel that promotes a healthy lifestyle and enhances well-being. The company aims to use the existing and potential customer data to improve the targeting strategy, ensuring more efficient customer outreach.

# 2. Data Collection
#### The dataset for this project is collected from Kaggle: Holiday Purchase Prediction Dataset.

## Dataset Overview:
#### - Rows: 4,888
#### - Columns: 20
#### - The data contains customer-related information which can be used to predict the likelihood of a customer purchasing a holiday package.

# 3. Model Overview: Random Forest
#### To predict the likelihood of a customer purchasing the new Wellness Tourism Package, we will use a Random Forest model. Random Forest is a versatile machine learning algorithm that builds multiple decision trees and merges them together to get a more accurate and stable prediction.

## Key Steps:
#### 1. Data Preprocessing: Clean the data by handling missing values, encoding categorical variables, and scaling numerical features.
#### 2. Feature Selection: Identify relevant features that influence the purchase decision of customers.
#### 3. Model Training: Train a Random Forest model using the training set.
#### 4. Evaluation: Evaluate the model using metrics like accuracy, precision, recall, and F1 score.
#### 5. Prediction: Predict the likelihood of customers purchasing the Wellness Tourism Package.

# 4. Usage
#### To implement and use the Random Forest model, follow these steps:

## Requirements:
#### - Python 3.x
## Required libraries:
#### - pandas
#### - numpy
#### - sklearn
#### - matplotlib
#### - seaborn

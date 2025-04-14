# Customer Churn Predictor

Customer Churn Predictor is a machine learning project aimed at identifying customers likely to discontinue their association with a business. Using predictive analytics, this project provides insights to help businesses retain their customers and enhance profitability.

## Features
- Predicts customer churn using various machine learning models.
- Handles imbalanced datasets with advanced techniques like SMOTE.
- Includes Exploratory Data Analysis (EDA) and feature engineering.
- Implements pipelines for streamlined data preprocessing and model training.

## Dataset
The project uses a banking dataset containing customer demographics, account details, and behavior metrics. The target variable indicates whether a customer has churned or not.

## Models Used
- Logistic Regression
- Support Vector Machines (SVM)
- Decision Trees
- Random Forest (best performer with F1-score: 0.62)
- XGBoost

## Key Techniques
- **Data Preprocessing**: Tokenization, stopword removal, and lemmatization for text data. Standard scaling and polynomial feature generation for numerical data.
- **Feature Engineering**: Extracted key features like age, gender, and country from textual descriptions. Binned continuous variables for better analysis.
- **Class Imbalance Handling**: Used SMOTE for balancing the minority and majority classes.
- **Model Selection**: Comprehensive comparison using metrics like F1-score to select the optimal model.

## Getting Started

Please open the jupyter notebook and run the cells for creating the submission file. 
Please make sure to install any required libraries
    1. pip install seaborn
    2. pip install pandas
    3. pip install matplotlib
    4. pip install numpy
    5. pip install scikit-learn
    6. pip install nltk
    7. pip install vaderSentiment
    8. pip install spacy

For spacy 
run 
    python -m spacy download en_core_web_sm

If required, use the following command to download stopwords library
run
    nltk.download('stopwords')

### README.md for Customer Churn Predictor

## Results
The Random Forest model emerged as the top performer, achieving an F1-score of 0.62. This model effectively captures complex relationships in the dataset, ensuring accurate predictions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

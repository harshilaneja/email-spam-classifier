# Email Spam Classifier

## Overview
This project aims to build an Email Spam Classifier using Natural Language Processing (NLP) techniques. The classifier distinguishes between spam and non-spam (ham) emails, assisting users in managing their email inboxes effectively.

## Features
- Cleans the dataset by removing duplicates and handling missing values.
- Utilizes Exploratory Data Analysis (EDA) to understand data distribution and patterns.
- Preprocesses text data through tokenization, stopword removal, and normalization.
- Implements various machine learning models for classification, including SVM, Naive Bayes, Decision Tree, Random Forest, etc.
- Improves model performance through hyperparameter tuning and ensemble learning techniques.
- Deploys the model as a web application using Flask, allowing users to input email content and receive real-time predictions on spam likelihood.

## Repository Structure
- `README.md`: Overview of the project and instructions.
- `app.py`: Flask application for deploying the model.
- `model.pkl`: Pickle file containing the trained model.
- `templates/`: HTML templates for the web interface.
- `static/`: Static files such as CSS and JavaScript.

## Usage
1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Flask application: `python app.py`
4. Access the web interface in your browser and input email content for prediction.

## Credits
- Dataset: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) from Kaggle.
- Libraries: Utilizes various Python libraries including Flask, scikit-learn, etc.


This project is a Machine Learning-based SMS Spam Detection System that classifies text messages as either Spam or Ham (Not Spam).
The model leverages Natural Language Processing (NLP) and supervised learning algorithms to achieve high accuracy in detecting unwanted messages.

🚀 Features

Preprocessing of SMS data (cleaning, tokenization, stopword removal, stemming).

Exploratory Data Analysis (EDA) using pandas, matplotlib, and seaborn.

Model training with multiple ML algorithms (e.g., Naive Bayes, Logistic Regression, Random Forest).

Achieved ~95% accuracy on test data.

User-friendly script for predicting whether a new SMS is spam or not.

🛠️ Tech Stack

Languages: Python

Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn, nltk

Algorithms Used: Naive Bayes, Logistic Regression, Random Forest

Dataset: Publicly available SMS Spam Collection dataset (~50k rows)

📂 Project Workflow

Data Preprocessing

Removed punctuation, numbers, and stopwords.

Applied stemming/lemmatization.

Converted text into feature vectors using TF-IDF.

Exploratory Data Analysis

Visualized message distribution between spam and ham.

Identified most common words in spam messages.

Model Training

Trained multiple classifiers.

Evaluated models using accuracy, precision, recall, and F1-score.

Prediction

Final model predicts whether an input SMS is Spam or Ham.

📊 Results

Accuracy: ~95%

Precision (Spam detection): 0.93

Recall: 0.92

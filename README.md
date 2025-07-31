📩 SMS Spam Detection with Machine Learning
This project implements a Spam Detection System using machine learning techniques to classify SMS messages as either spam or ham (not spam). The workflow includes data preprocessing, feature engineering, model training, evaluation, and real-time prediction via user input.

🔍 Features
Dataset: Based on the SMS Spam Collection dataset, loaded with proper label encoding.

Data Analysis & Visualization:

Class distribution visualization (imbalanced vs. balanced)

Word count analysis

Currency and number detection features

Text Preprocessing:

Noise removal (special characters, numbers)

Tokenization, stopword removal

Lemmatization using NLTK

Feature Engineering:

TF-IDF Vectorization

Models Used:

Multinomial Naive Bayes

Decision Tree Classifier

Both models are evaluated using F1-score and confusion matrices

User Interaction:

Accepts sample SMS input and predicts whether it is spam or not

📊 Evaluation
10-fold Cross-validation using F1 score

Confusion matrix and classification reports for both models

🛠️ Dependencies
Python 3.x

pandas, numpy

scikit-learn

matplotlib, seaborn

nltk

🎬 Sentiment Analysis using NLP Pipeline & Machine Learning

End-to-End NLP Project | TF-IDF + ML Models | 88% Accuracy
Built using real-world IMDB dataset with complete preprocessing, feature engineering, and model comparison.

📌 Project Overview

This project focuses on building a complete Sentiment Analysis system using Natural Language Processing (NLP) and Machine Learning.

The objective is to transform raw movie reviews into meaningful numerical features and classify them as positive or negative sentiments.

It demonstrates a full pipeline starting from raw text to final model evaluation and insights.

📂 Dataset
Dataset: IMDB Movie Reviews Dataset
Total Samples: 50,000
Balanced Dataset (Positive = Negative)

⚠️ Note:
Due to file size limitations, the dataset is not included in this repository.

👉 Download from Kaggle:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

⚙️ NLP Pipeline
Raw Text
   ↓
Text Preprocessing
   ↓
Feature Engineering (BoW, TF-IDF)
   ↓
Model Training
   ↓
Evaluation
   ↓
Comparison & Insights
🧹 Text Preprocessing

The following preprocessing steps were applied to clean and normalize the text data:

Lowercasing
Removing HTML tags
Removing URLs and special characters
Removing punctuation and numbers
Tokenization
Stopword removal
Lemmatization

These steps help reduce noise and improve model learning.

🔢 Feature Engineering
1. Bag of Words (BoW)
Converts text into frequency-based vectors
Simple but treats all words equally
2. TF-IDF (Term Frequency - Inverse Document Frequency)
Assigns importance to meaningful words
Reduces impact of common words
Provided better performance than BoW
🤖 Models Used

The following Machine Learning models were implemented:

Logistic Regression
Naive Bayes (MultinomialNB)
Decision Tree
📊 Model Performance
Model	Accuracy
Logistic Regression	88.46%
Naive Bayes	84.89%
Decision Tree	71.64%
📈 Evaluation Metrics

Models were evaluated using:

Accuracy
Precision
Recall
F1 Score

Logistic Regression achieved the best balance across all metrics.

💡 Key Insights
Proper preprocessing significantly improves performance
TF-IDF outperforms Bag of Words for text representation
Logistic Regression performs best on high-dimensional text data
Naive Bayes is fast and works as a strong baseline
Decision Trees are not suitable for sparse text data due to overfitting

🔍 Sample Predictions
Input: "This movie was absolutely fantastic!"
Prediction: Positive ✅

Input: "Worst movie I have ever seen."
Prediction: Negative ❌
🛠️ Tech Stack
Python
Pandas, NumPy
NLTK
Scikit-learn
Matplotlib, Seaborn

📌 Conclusion

This project demonstrates how raw textual data can be effectively processed and transformed into structured features for machine learning models. Among all approaches, TF-IDF combined with Logistic Regression provided the best performance for sentiment classification.

🔗 Connect with Me
LinkedIn: (https://www.linkedin.com/in/saisandeep1912/)
GitHub: https://github.com/saisandeep1912
⭐ If you like this project

Give it a ⭐ on GitHub and share your feedback!

# ML Ticket Triage System

A machine learning–based ticket triage system designed to improve customer support workflows by classifying ticket queues, predicting ticket priority, and generating concise issue summaries.

The project applies natural language processing (NLP) and supervised learning techniques to classify and prioritize multilingual customer support tickets.

---

## Features

- Multi-class ticket queue classification (e.g., Technical Support, Billing, Customer Service)
- Ticket priority prediction (Low, Medium, High)
- Text preprocessing pipeline (normalization, tokenization, lemmatization, TF-IDF)
- Class imbalance handling using SMOTE
- Model benchmarking across:
  - Linear SVC
  - Random Forest
  - Decision Tree
  - KNN
  - Naive Bayes
- Hyperparameter optimization using RandomizedSearchCV
- Cross-validation and learning curve evaluation
- Extractive summarization using BERT
- Abstractive summarization using BART

---
## Requirements

- Python 3.9+
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- nltk
- transformers
- summarizer
- matplotlib
- seaborn

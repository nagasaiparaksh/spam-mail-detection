# Spam Mail Detector using Machine Learning

## Overview

Spam Mail Detector is a machine learning and NLP-based project that classifies messages as **Spam** or **Ham (Non-Spam)** using textual data. The system analyzes message content and predicts whether a message is spam using machine learning classification algorithms.

The project demonstrates the complete Natural Language Processing (NLP) workflow including text preprocessing, feature extraction, model training, evaluation, and prediction.

---

## Objective

The objective of this project is to build a spam detection system capable of classifying messages into spam or ham categories using machine learning techniques.

---

## Dataset

This project uses the **SMS Spam Collection Dataset** from Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

### Dataset Labels

* **Spam** → Unwanted or promotional messages
* **Ham** → Legitimate messages

### Sample Data

| Label | Message                                     |
| ----- | ------------------------------------------- |
| ham   | Hey, are you coming to class today?         |
| spam  | Congratulations! You won ₹50,000 claim now! |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* Scikit-learn

---

## Machine Learning Models Used

The following classification algorithms were implemented and compared:

1. **Naive Bayes**
2. **Logistic Regression**

---

## NLP Techniques Used

The project applies multiple Natural Language Processing techniques:

* Text lowercasing
* Stopword removal
* Tokenization
* Removing punctuation
* Removing numbers
* Text cleaning

---

## Feature Extraction

To convert text into machine-readable numerical features, the project uses:

### TF-IDF (Term Frequency–Inverse Document Frequency)

This helps the model understand the importance of words in messages.

---

## Project Workflow

1. Import required libraries
2. Load and clean dataset
3. Perform exploratory data analysis (EDA)
4. Visualize spam and ham message distribution
5. Preprocess text data
6. Convert text into numerical vectors using TF-IDF
7. Split dataset into training and testing data
8. Train machine learning models
9. Evaluate performance using classification metrics
10. Predict custom messages

---

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

The trained models achieved high classification accuracy for spam detection.

---

## Example Prediction

### Input Message

Congratulations! You won ₹50,000. Click here to claim your reward.

### Output

Spam Message

### Input Message

Hey bro, are you coming to class today?

### Output

Ham Message

---

## Expected Results

The project generally achieves **95–99% accuracy** depending on preprocessing and model selection.

---

## Skills Gained

* Natural Language Processing (NLP)
* Text preprocessing
* Feature extraction using TF-IDF
* Classification modeling
* Model evaluation
* Spam detection system development

---

## Conclusion

This project demonstrates how machine learning and NLP can be used to automatically classify spam and legitimate messages. It provides practical experience in text preprocessing, feature extraction, classification algorithms, and predictive analytics using Python and Scikit-learn.

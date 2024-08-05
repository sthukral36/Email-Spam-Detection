# Email-Spam-Detection

Spam Mail Classification Project Description
# Project Overview:
The Spam Mail Classification project aims to develop a robust system for detecting and filtering spam emails using machine learning algorithms. This project leverages the power of data preprocessing, feature extraction, and machine learning to accurately classify emails as spam or non-spam. The goal is to improve email security and efficiency by reducing the amount of spam reaching users' inboxes.

# Technologies Used:

Python
Scikit-learn
Natural Language Toolkit (NLTK)
Pandas
NumPy

# Data Collection:
A comprehensive dataset of emails is collected, which includes both spam and non-spam emails. This dataset serves as the foundation for training and evaluating the machine learning models.

# Data Preprocessing:

Text Cleaning: Removal of irrelevant characters, punctuation, and HTML tags from the email content.
Tokenization: Splitting email text into individual tokens (words or phrases).
Stop Words Removal: Eliminating common but uninformative words (e.g., 'the', 'and', 'is') that do not contribute to spam classification.
Stemming: Reducing words to their base or root form to standardize the text.
Feature Extraction:

# Bag of Words (BoW): Representing text data as a matrix of word frequencies.
# Term Frequency-Inverse Document Frequency (TF-IDF): Reflecting the importance of words by considering their frequency in a document relative to their frequency across all documents.

Model Development:
Two machine learning algorithms are used for classification:

Naive Bayes: A probabilistic classifier based on Bayes' theorem, well-suited for text classification due to its simplicity and effectiveness.
Random Forest: An ensemble learning method that uses multiple decision trees to improve classification accuracy and control overfitting.
Training and Evaluation:
The dataset is split into training and testing sets. The models are trained on the training set and evaluated on the testing set using performance metrics such as accuracy, precision, recall, and F1-score. The Random Forest algorithm achieved a 98% accuracy, while the Naive Bayes algorithm achieved a 97% accuracy.

 
Results and Impact:
The implementation of the spam classification system significantly improves email management and security. By achieving high classification accuracy, the system reduces the time and resources spent on manually sorting emails and enhances the user experience by minimizing the presence of spam emails in the inbox.


This project demonstrates the application of machine learning techniques in solving real-world problems like spam email detection. By using a combination of data preprocessing, feature extraction, and advanced classification algorithms, the project successfully builds an efficient and accurate spam classification system.


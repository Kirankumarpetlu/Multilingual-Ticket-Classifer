# Multilingual-Ticket-Classifer
🔹 Project Overview:
This project is an AI-powered ticket/complaint classification system that can understand and classify customer complaints in multiple languages. It leverages natural language processing (NLP) and machine learning to categorize complaints into predefined product categories.

🔹Features

Classifies complaints into 11 categories:

Bank account or service

Consumer Loan

Credit card

Credit reporting

Debt collection

Money transfers

Mortgage

Other financial services

Payday loan

Prepaid card

Student loan

Multilingual support: Translate complaints from languages like Telugu, Hindi, Spanish, German, and more into English before classification.

🔹Dataset

The model was trained on the Consumer Complaints dataset, containing complaints across various financial products.

Columns used:

Consumer complaint narrative → Complaint text

Product → Complaint category

Preprocessing:

Removed null complaints

Lowercasing and lemmatization

TF-IDF vectorization for text features

Oversampling with SMOTE to handle class imbalance

High accuracy: Achieves an overall accuracy of ~85% on the test dataset.

Easy-to-use web interface: Built with Streamlit to upload complaints and get real-time predictions.

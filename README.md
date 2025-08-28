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

🔹Complaint	Predicted                                         Category
I was charged extra fees on my credit card without notice.	Credit card
My mortgage application has been delayed for months.	      Mortgage
The loan interest rate is much higher than promised.	      Mortgage
Unauthorized transactions happened on my bank account.	    Bank account or service


🔹Example Predictions
<img width="952" height="720" alt="Screenshot 2025-08-28 231008" src="https://github.com/user-attachments/assets/7b3355ea-5b91-41df-a0bc-5de2230f0101" />
<img width="934" height="676" alt="Screenshot 2025-08-28 231049" src="https://github.com/user-attachments/assets/fdc9e5c6-b3c6-4789-9c1a-50ef2e3e6a53" />
<img width="998" height="707" alt="Screenshot 2025-08-28 231129" src="https://github.com/user-attachments/assets/edcdd124-612b-4f86-81fe-0cbb9f091ad5" />



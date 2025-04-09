# Spam Email Detection using Machine Learning

This project implements a spam email classifier using two machine learning algorithms: **Naive Bayes** and **Logistic Regression**. The system classifies emails as either `spam` or `ham` (non-spam) using intelligent text preprocessing techniques.



# Features
- Preprocessing of email text (removal of punctuation, stop words, lowercasing)
- Vectorization using CountVectorizer
- Model training using:
- Multinomial Naive Bayes
- Logistic Regression
- Evaluation using accuracy score, confusion matrix, and classification report
- Visual heatmaps for performance comparison



#Algorithms Used
- Naive Bayes: Fast and efficient for text classification
- Logistic Regression: Effective baseline classifier for binary classification tasks



#Dataset
- A CSV file containing labeled messages (`spam_data.csv`)
- Columns:
- Category: Label (spam/ham)
- Message: Email text



#Requirements
See requirements.txt for Python dependencies.


#Project Structure

spam-email-detector/
├── spam_email_detection.ipynb   # Main Jupyter Notebook
├── spam_data.csv                # Labeled email dataset
├── README.md                    # Project documentation
└── requirements.txt             # List of required Python libraries


#Results
Both models are evaluated using an 80-20 and 60-40 train-test split. Naive Bayes showed a slight edge in performance over Logistic Regression due to its probabilistic nature and suitability for text classification.



#Future Scope
- Deploy the model using Flask as an API
- Expand dataset to improve model robustness
- Incorporate advanced models like SVM, Random Forest, or Neural Networks



#References
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [SpamAssassin Dataset](https://github.com/dmitrynogin/SpamAssassin.git)

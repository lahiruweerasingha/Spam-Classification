# **Spam Classification using NLP**
This project uses Natural Language Processing (NLP) to classify SMS messages automatically as spam or ham (non-spam). The project encompasses the following steps:

## **Dataset Obtained from:-**
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset


**01. Data Handling:**
 - Importing and exploring the dataset using pandas.
 - Data cleaning by removing unnecessary columns and duplicate entries.

**02. Data Preprocessing:**
 - Lowercasing, tokenization, and stemming of text data.
 - Removal of special characters, stop words, and punctuation.

**03. Feature Extraction:**
 - Utilization of TF-IDF vectorization to convert text data into numerical features.
 - Limiting features to the 3000 most important words.

**04. Model Training:**
 - Training a Multinomial Naive Bayes classifier using scikit-learn.
 - Evaluating model performance with accuracy metrics.
   
**05. User Interaction:**
 - Allowing users to input SMS messages for classification.
 - Cleaning user input and predicting spam or ham classification.

## **Technical Stack:**
- Programming Language: Python
- Libraries:
  - pandas
  - NLTK (Natural Language Toolkit)
  - scikit-learn
  - Data Visualization: Matplotlib, seaborn

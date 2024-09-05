# Yelp Sentiment Analysis

## Project Overview
This project aims to perform sentiment analysis on Yelp restaurant reviews. The objective is to classify the reviews into different sentiment categories (positive, neutral, or negative) using machine learning models. The dataset consists of Yelp reviews, and the analysis leverages natural language processing (NLP) techniques to preprocess the text and predict sentiment.

## Project Structure
- **Data Preprocessing**: The reviews are cleaned and transformed using text preprocessing techniques such as tokenization, removing stopwords, and converting text to lowercase.
- **Feature Extraction**: The `TF-IDF` method is used to convert text data into numerical features.
- **Model Training**: Various machine learning models were trained and evaluated, including Logistic Regression, Naive Bayes, and Random Forest.
- **Evaluation**: The models are evaluated using accuracy, precision, recall, and F1-score.
- **Prediction**: Given a new Yelp review, the trained model predicts the sentiment of the review.

## Dataset
Link: https://www.yelp.com/dataset

## Models Used
- **Logistic Regression:** 
- **Naive Bayes:**
- **Random Forest:**

## Conclusion
This project demonstrates how machine learning and NLP techniques can be applied to classify the sentiment of restaurant reviews. Future improvements could include using more advanced NLP models like LSTM or BERT for better performance.

## Installation
To run this project, you'll need to set up a Python environment and install the required dependencies. The dependencies are listed in the `requirements.txt` file.

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Yelp-Sentiment-Analysis.git
2. Navigate to the project directory
   ```bash
   cd Yelp-Sentiment-Analysis
3. Install the required packages:
  ```bash
pip install -r requirements.txt

  

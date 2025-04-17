# Fake News Detection

A machine learning project to detect fake news articles using natural language processing (NLP) and classification algorithms.

## Dataset
The dataset contains news articles with the following features:
- `title`: Title of the news article
- `author`: Author of the news article
- `text`: The article content (can be complete or incomplete)
- `label`: 0 for real news, 1 for fake news

## Objective
To build a model that accurately classifies whether a news article is real or fake based on textual content.

## Technologies Used
Python  
Pandas, NumPy  
NLTK (for text preprocessing and stemming)  
Scikit-learn (for model building and evaluation)  
TF-IDF Vectorizer

## Steps Involved
1. Data cleaning and preprocessing (removing stopwords, stemming, etc.)
2. Feature extraction using TF-IDF
3. Splitting data into training and testing sets
4. Model training and evaluation
5. Accuracy and performance metrics

## Model Performance
Achieved **97% accuracy** on the test set using  Logistic Regression.

## Future Improvements
Explore deep learning approaches  
Add a web interface for user input  
Include more robust datasets

## How to Run
```bash
# Download the .ipynb file and the dataset
# Run the notebook
Open in Jupyter or Google Colab

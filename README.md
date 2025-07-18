# Fake News Detection

This project builds a machine learning model to classify news articles as fake or real. It uses natural language processing (NLP) for text preprocessing, TF-IDF vectorization, and logistic regression for classification. The model is deployed using Streamlit for an interactive web app.

## Features

- Text preprocessing with spaCy (lemmatization, stopword removal)
- TF-IDF vectorization for feature extraction
- Logistic Regression classifier
- Confusion matrix visualization
- Interactive web app for real-time predictions using Streamlit

## Installation

```bash
git clone <your_repo_url>
cd fake-news-detection
pip install -r requirements.txt
python -m spacy download en_core_web_sm
streamlit run app.py

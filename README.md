# Fake News Classification Using LSTM

## Overview
This project focuses on scraping articles from websites like **Misbar** using **Selenium** and **BeautifulSoup**, creating a dataset labeled as *fake* or *real* news, and training an **LSTM model** for classification.

## Objective
The goal of this project is to build a robust deep learning model that can classify news articles as either **real** or **fake** based on textual content.

## Dataset Creation
- **Scraping Data**: Extracted articles from fact-checking websites using **Selenium** and **BeautifulSoup**.
- **Labeling**: Articles were manually labeled based on their credibility.
- **Preprocessing**: Removed stopwords, tokenized text, and converted data into embeddings for training.

## Approach
1. **Web Scraping**:
   - Used **Selenium** for dynamic content extraction.
   - Employed **BeautifulSoup** for parsing HTML content.
2. **Data Processing**:
   - Cleaned and preprocessed text data.
   - Used **word embeddings** for text representation.
3. **Model Selection**:
   - Implemented an **LSTM (Long Short-Term Memory) neural network**.
   - Experimented with different hyperparameters and architectures.
4. **Training & Evaluation**:
   - Optimized the model using **loss functions** and **accuracy metrics**.
   - Evaluated using confusion matrix and F1-score.


## Results
- Achieved **high accuracy** in classifying real vs. fake news.
- Improved model robustness using **data augmentation**.
- Identified common patterns in fake news articles.





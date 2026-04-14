# Fake News Detection using LSTM

This project focuses on detecting fake news using a Deep Learning approach based on LSTM (Long Short-Term Memory) networks. The model is trained on a dataset containing both real and fake news articles, and it learns to classify news text as real (0) or fake (1).

## Overview

With the rapid spread of misinformation online, identifying fake news has become crucial. This project applies Natural Language Processing (NLP) and deep learning techniques to automatically detect misleading content.

## Technologies Used
- Python
- TensorFlow 
- NumPy & Pandas
- Matplotlib
- NLP (Tokenization & Padding)

## Model Architecture
- <b>Embedding Layer</b> – Converts words into dense vectors
- <b>LSTM Layer</b> – Captures context and sequence information
- <b>Dense Layer (Sigmoid)</b> – Outputs probability (Real or Fake)
## Workflow
1. Load and combine real & fake news datasets
2. Label the data (0 = Real, 1 = Fake)
3. Preprocess text (tokenization & padding)
4. Split dataset into training and testing sets
5. Train LSTM model
6. Evaluate model performance

## How to Run
1. Clone the Repository
```
git clone https://github.com/your-username/fake-news-lstm.git
cd fake-news-lstm
```
2. Install Dependencies
```
pip install -r requirements.txt
```
3. Run the Notebook / Script
```
jupyter notebook
```

## Dataset
- The dataset contains two types of news:
  - real news
  - fake news
- You can use publicly available datasets like:
  - Kaggle Fake News Dataset
  
## Features
- Handles large text data efficiently
- Uses sequence learning for better context understanding
- Simple and scalable architecture
## Future Improvements
- Use advanced models like BERT or Transformers
- Improve accuracy with larger datasets
- Deploy as a web application

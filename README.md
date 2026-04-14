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

## 📁 Dataset

This project uses the Fake News Detection dataset from Kaggle:

🔗 https://www.kaggle.com/datasets/bhavikjikadara/fake-news-detection

### 📊 Dataset Details
- Contains news articles labeled as:
  - `0 → Real News`
  - `1 → Fake News`
- Includes text-based features for training the model

### 📥 How to Use
1. Download the dataset from Kaggle
2. Extract the files into your project folder
3. Update the file path in the code accordingly

Example:
```python
import pandas as pd

df = pd.read_csv("dataset.csv")
```

## If You Need to Change Columns in Code

That dataset usually has columns like:
- `title`
- `text`
- `label`

### Update your code like this:

``` python
X = df['text']   # input (news content)
y = df['label']  # output (0 or 1)
  ```
## Features
- Handles large text data efficiently
- Uses sequence learning for better context understanding
- Simple and scalable architecture
## Future Improvements
- Use advanced models like BERT or Transformers
- Improve accuracy with larger datasets
- Deploy as a web application

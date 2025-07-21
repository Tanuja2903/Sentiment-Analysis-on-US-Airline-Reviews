# ✈️ Sentiment Analysis on US Airline Reviews

## 📝 Description

This project performs binary sentiment analysis (positive vs. negative) on airline tweets using an LSTM-based deep learning model. It leverages preprocessed textual data from the **US Airline Sentiment** dataset to classify reviews and visualize model performance.

## 🛠️ Tech Stack

- Python
- Pandas, Matplotlib
- TensorFlow / Keras (LSTM, Embedding, Tokenizer)

## ✅ Features

- Data preprocessing (removal of neutral sentiments)
- Tokenization and padding of tweets
- Word embedding layer with LSTM architecture
- Training and evaluation using binary cross-entropy loss
- Visualization of training accuracy and loss
- Real-time prediction for new tweet inputs

## 📊 Dataset

- Source: [Kaggle - US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- Key columns used:
  - `text`: The tweet
  - `airline_sentiment`: Target label (positive, negative)

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/airline-sentiment-lstm.git
   cd airline-sentiment-lstm

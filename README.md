
# Sentiment Analysis using RNN

This project implements a sentiment analysis model using Recurrent Neural Networks (RNN), specifically LSTM or GRU, to classify text as positive or negative.

## 📌 Features
- Uses **Keras** and **TensorFlow** for deep learning.
- Implements **text preprocessing** using `pad_sequences` instead of `Tokenizer`.
- Trains a sentiment analysis model on labeled text data.
- Predicts the sentiment of new input texts.

## 🚀 How to Use
1. **Install Dependencies:**
   ```bash
   pip install tensorflow numpy pandas
   ```

2. **Run the Notebook:**
   Load and execute `Sentiment_Analysis_RNN.ipynb` in Jupyter Notebook or Google Colab.

3. **Test the Model:**
   ```python
   new_reviews = ["This movie was amazing!", "The film was terrible and boring."]
   predict_sentiment(model, new_reviews, sequence)
   ```

## 🛠 Requirements
- Python 3.x
- TensorFlow/Keras
- Jupyter Notebook or Google Colab

## 📄 License
This project is open-source and free to use for learning purposes.


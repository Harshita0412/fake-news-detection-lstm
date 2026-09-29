
# Fake News Detection using LSTM

An NLP-based deep learning project for classifying news articles using a Long Short-Term Memory (LSTM) neural network.

## Overview

This project uses the WELFake dataset to explore Natural Language Processing and recurrent neural networks for binary news classification.

## Technologies Used

- Python
- TensorFlow
- Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLP

## Models Evaluated

| Model | Test Accuracy | Macro F1 |
|---|---:|---:|
| SimpleRNN | 60.17% | 58.34% |
| LSTM | 62.31% | 57.44% |
| Improved LSTM | 70.41% | 70.41% |

## Final Model

The final model uses:

- Embedding layer
- LSTM with 64 units
- Dropout
- Dense output layer
- Sigmoid activation

## Final Results

**Test Accuracy:** 70.41%

**Macro F1-score:** 70.41%

The model was evaluated on a held-out test set of 14,404 samples.

## Saved Model

```text
fake_news_lstm.keras
tokenizer.pkl

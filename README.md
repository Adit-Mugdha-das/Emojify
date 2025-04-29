# Emojify - Sequence Models

This repository contains the programming assignment from **Week 2** of **Course 5: Sequence Models** in the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) by Andrew Ng on Coursera.

## Overview

In this assignment, an LSTM-based sequence model is implemented to classify sentences into corresponding emojis, demonstrating the use of Recurrent Neural Networks (RNNs) for text classification tasks.

You will implement two models:
- A baseline model using simple average word embeddings
- An advanced model using an LSTM network to better capture word order and context

Key topics covered:
- Sentence representation using pre-trained word embeddings (GloVe)
- LSTM model architecture for text classification
- Forward and backward propagation through LSTM
- Predicting and evaluating emoji labels

## Contents

- `sentences_to_indices()` – Converts sentences into sequences of word indices
- `pretrained_embedding_layer()` – Loads pre-trained GloVe vectors into an embedding layer
- `Emojify_V2()` – Defines the LSTM model for sentence classification
- Jupyter Notebook – Walkthrough of the assignment, model training, and evaluation
- Pre-trained GloVe embeddings (`glove.6B.50d.txt`) – Used for word vector initialization

## Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy

## Course Information

- Course: Sequence Models (Course 5 of 5)
- Specialization: Deep Learning Specialization
- Instructor: Andrew Ng
- Platform: Coursera
- Institution: DeepLearning.AI

## License

This repository is based on educational content provided by DeepLearning.AI through Coursera. It is intended for educational and personal use only and should not be used for commercial purposes.

---

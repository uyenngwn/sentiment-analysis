# PyTorch Sentiment Analysis

This repo contains tutorials covering understanding and implementing sequence classification models using PyTorch, with Python 3.9. Specifically, we'll train models to predict sentiment from movie reviews.

## Getting Started

Install the required dependencies with: `pip install -r requirements.txt --upgrade`.

## Tutorials

1. Neural Bag of Words

   This tutorial covers the workflow of a sequence classification project with PyTorch. We'll cover the basics of sequence classification using a simple, but effective, neural bag-of-words model, and how to use the datasets/torchtext libraries to simplify data loading/preprocessing.

2. Recurrent Neural Networks

   Now we have the basic sequence classification workflow covered, this tutorial will focus on improving our results by switching to a recurrent neural network (RNN) model. We'll cover the theory behind RNNs, and look at an implementation of the long short-term memory (LSTM) RNN, one of the most common variants of RNN.

3. Convolutional Neural Networks

   Next, we'll cover convolutional neural networks (CNNs) for sentiment analysis. This model will be an implementation of "Convolutional Neural Networks for Sentence Classification".

4. Transformers

   Finally, we'll show how to use the transformers library to load a pre-trained transformer model, specifically the BERT model, and use it for sequence classification.

## Legacy Tutorials

Previous versions of these tutorials used features from the torchtext library which are no longer available. These are stored in the legacy directory.

# 100 Days of Machine Learning - Day 9

### Word Embeddings Visualization

This repository contains code for visualizing word embeddings generated by GloVe and Word2Vec models. The visualization is done using the t-SNE algorithm. The code demonstrates preprocessing of text data (tokenization, stopword removal, and stemming) and training a Word2Vec model on the preprocessed data.
Prerequisites

### To run the code, you need the following Python libraries:

    numpy
    matplotlib
    scikit-learn
    nltk
    gensim

You also need the pre-trained GloVe embeddings file glove.6B.50d.txt. You can [download it from here](https://github.com/stanfordnlp/GloVe).

### Code Description

The code is organized as follows:

    Import required libraries.
    Download the required NLTK datasets (punkt and stopwords).
    Define the preprocess_text function to tokenize, remove stopwords, and stem the text.
    Define a raw text and preprocess it using the preprocess_text function.
    Load the GloVe embeddings into a dictionary.
    Train a Word2Vec model using the preprocessed tokens.
    Define the visualize_embeddings function that takes word embeddings and words as input, and uses t-SNE to visualize them in a 2D space.
    Visualize GloVe embeddings for the preprocessed tokens.
    Visualize Word2Vec embeddings for the preprocessed tokens.

### Usage

To run the code, simply execute the script in a Python environment with the required libraries installed. Make sure to update the path to the glove.6B.50d.txt file as needed. The script will output two plots, one for the GloVe embeddings and the other for the Word2Vec embeddings.
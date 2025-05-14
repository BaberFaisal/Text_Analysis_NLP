# Text_Analysis_NLP


## 📘 Overview

This project explores natural language processing (NLP) techniques, particularly language modeling using both classical n-gram models and neural network-based approaches like Transformers.

It is designed as a homework assignment demonstrating:

- Data cleaning and tokenization using NLTK
- Building n-gram models with Laplace smoothing
- Evaluating models via perplexity
- Introduction to Transformer models using PyTorch

## 📂 Dataset

The dataset used is a collection of informal forum posts from the [20 Newsgroups dataset](https://www.kaggle.com/datasets). It combines 20 different categories of newsgroup discussions, such as:

- `alt.atheism`
- `comp.graphics`
- `rec.sport.hockey`
- `sci.med`
- … and more

The dataset is stored in a CSV format, with each post treated as a separate text entry.

## ⚙️ Features and Methods

- **Preprocessing**: Tokenization using NLTK, vocabulary extraction
- **Statistical Language Modeling**:
  - Unigram, bigram, and trigram models
  - Laplace smoothing
  - Perplexity calculation
- **Transformer-Based Modeling** (initial setup):
  - Token embedding
  - Positional encoding
  - Transformer encoder layers using PyTorch

# Part-of-Speech Tagging with LSTM

## Introduction
This project presents an end-to-end implementation of a Part-of-Speech (POS) tagging model using a Long Short-Term Memory (LSTM) neural network.

POS tagging involves assigning grammatical categories (such as noun and verb) to words in a given text. The model is developed using PyTorch and is trained on a dataset derived from the Penn Treebank.

---

## The Main Dataset

### Source
The primary data source was the Billboard Year-End Hot 100 Singles USA, an annual ranking of the top-performing songs in the United States. It encompasses 5402 lyrics out of the 6889 songs from a diverse array of artists and genres.

### Scope
The dataset spans from 1946 to 2022, capturing the evolution of popular music over several decades. Notably, the first years of the ranking included less than 100 songs.

### Selection Criteria
To ensure a representative dataset, at least the top 20 songs from each year were included. This criterion was applied to account for variations in the number of songs listed each year.


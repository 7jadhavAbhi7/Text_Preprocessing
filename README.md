# NLTK Text Preprocessing

This Python script preprocesses text data using NLTK (Natural Language Toolkit) for tasks such as tokenization, stop word removal, punctuation removal, and lemmatization.

## Overview

The script `preprocess_text.py` reads text data from a file named `data.txt` and performs the following preprocessing steps:
- Tokenization: Splitting the text into individual words or tokens.
- Lowercasing: Converting all tokens to lowercase to ensure uniformity.
- Stopword Removal: Removing common words like "the", "is", "and", etc., which do not carry significant meaning.
- Punctuation Removal: Eliminating punctuation marks from the text.
- Lemmatization: Reducing words to their base or root form to handle variations like plurals, verb tenses, etc.
- HTML Tag Removal: Stripping HTML tags from the text to clean it from any markup.
The preprocessed data is stored as a list of lists, where each sublist contains the preprocessed tokens for each line of text in `data.txt`.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/your-repository.git

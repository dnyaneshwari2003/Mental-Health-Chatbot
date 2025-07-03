# Mental Health Chatbot - Retrival Based Bot With API Integration

## Overview
This project is a chatbot designed to respond to frequently asked questions about mental health using Natural Language Processing (NLP) techniques. It utilizes TF-IDF vectorization and cosine similarity to find the most relevant response from a dataset of mental health-related questions and answers.

## Features
- Preprocesses input text (lowercasing, tokenization, lemmatization, punctuation removal).
- Recognizes greetings and provides predefined responses.
- Uses TF-IDF vectorization to find the most relevant answer.
- Interacts with users in a conversational manner.

## Requirements
- Python 3.x
- Required Libraries:
  - numpy
  - nltk
  - pandas
  - scikit-learn
  - random

## Setup
1. Install dependencies:
   ```bash
   pip install numpy nltk pandas scikit-learn
   ```
2. Download necessary NLTK data:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   ```

## Usage
1. Place your dataset file (`Mental_Health_FAQ.csv`) in the appropriate directory.
2. Run the chatbot script:
   ```bash
   python chatbot.py
   ```
3. The chatbot will prompt you to enter text. Type 'Bye' to exit.

## File Details
- `Mental_Health_FAQ.csv`: Contains questions and answers used for chatbot responses.
- `chatbot.py`: The main chatbot script.
- `Tokanization (1).ipynb `: Preprocessing on dataset 
## Dataset 
- https://www.kaggle.com/datasets/narendrageek/mental-health-faq-for-chatbot
- https://www.kaggle.com/datasets/thedevastator/nlp-mental-health-conversations
- https://huggingface.co/datasets/jkhedri/psychology-dataset
  Note: The dataset provided is merged dataset (from above 3 datasets ), feel free to use any dataset , just modify the column headers as 'Questions ' and 'Response' .


## Images
![Screenshot 2025-05-08 192353](https://github.com/user-attachments/assets/d4497276-be9d-46a6-ac44-cdbf8b6364b7)



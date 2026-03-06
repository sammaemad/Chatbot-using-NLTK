# ROBO Chatbot 
Robo is a simple Python-based chatbot designed to interact with users by answering questions and responding to greetings. It demonstrates basic Natural Language Processing (NLP) techniques such as tokenization, lemmatization, keyword matching, and TF-IDF-based similarity for generating responses.

## Features 
#### Greeting response - Recognizes common greetings and responds appropriately.
#### Keyword Matching – Detects key phrases in user input to provide meaningful replies.
#### TF-IDF Response Generation – Uses sentence similarity to generate contextually relevant responses.
#### Interactive Console Chat – Users can chat with Robo in a command-line interface.
#### Lightweight & Easy to Understand – Perfect for beginners exploring NLP and chatbot development.

## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 

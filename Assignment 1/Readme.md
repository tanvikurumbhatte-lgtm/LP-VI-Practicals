# NLP Preprocessing Techniques

##  Overview

This project demonstrates fundamental Natural Language Processing (NLP) preprocessing techniques using Python and NLTK. It includes various tokenization methods, stemming techniques, and lemmatization.

## ⚙️ Technologies Used

* Python
* NLTK (Natural Language Toolkit)

## 🔍 Features

* Implementation of multiple tokenization techniques:

  * Whitespace Tokenization
  * Punctuation-based Tokenization
  * Treebank Tokenization
  * Tweet Tokenization
  * Multi-Word Expression (MWE) Tokenization
* Stemming using:

  * Porter Stemmer
  * Snowball Stemmer
* Lemmatization using WordNet Lemmatizer

## 📝 Sample Input

A sample sentence is used to demonstrate all preprocessing techniques.

## 🚀 How to Run

1. Install required libraries:

   ```
   pip install nltk
   ```
2. Download required datasets in Python:

   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   nltk.download('omw-1.4')
   ```
3. Run the Python script:

   ```
   python filename.py
   ```

## 📊 Output

* Tokenized words using different methods
* Stemmed words using Porter and Snowball
* Lemmatized words with meaningful roots

## 📚 Key Concepts

* Tokenization: Splitting text into words/tokens
* Stemming: Reducing words to base/root form (not always meaningful)
* Lemmatization: Converting words to their meaningful base form

## 🤝 Contributing

Feel free to fork this repository and improve the implementation.

## 📄 License

This project is open-source and available for educational purposes.


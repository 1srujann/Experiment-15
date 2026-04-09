# Experiment 15: NLP Techniques on Text Data

---

## Title

Implementation of Natural Language Processing (NLP) Techniques Using Python and NLTK

---

## Aim

To study and implement basic Natural Language Processing (NLP) techniques on text data using Python libraries such as NLTK.

---

## Objectives

- To understand the fundamentals of NLP  
- To perform tokenization of text data  
- To remove stop words from sentences  
- To apply stemming and lemmatization techniques  
- To identify parts of speech using POS tagging  
- To analyze text using word frequency distribution  

---

## Theory

Natural Language Processing (NLP) is a field of artificial intelligence that focuses on enabling computers to understand, interpret, and process human language.

Text data is unstructured in nature, so various preprocessing steps are required before analysis. NLTK (Natural Language Toolkit) is a widely used Python library that provides tools for text processing.

Some important NLP techniques include:

- **Tokenization:** Splitting text into words or sentences  
- **Stop Word Removal:** Eliminating common words that do not add significant meaning  
- **Stemming:** Reducing words to their root form  
- **Lemmatization:** Converting words into their base or dictionary form  
- **Part-of-Speech (POS) Tagging:** Identifying grammatical roles of words  
- **Frequency Distribution:** Counting occurrences of words in text  

These techniques help in preparing text data for further analysis and machine learning applications.

---

## Problem Statements

### 1. Tokenization

Perform both:
- Word tokenization  
- Sentence tokenization  

**Concepts Used:** word_tokenize(), sent_tokenize()

---

### 2. Stop Word Removal

Remove commonly used words such as "is", "the", "in" from the text.

**Concepts Used:** stopwords, filtering

---

### 3. Stemming

Reduce words like:
- playing → play  
- running → run  

**Concepts Used:** PorterStemmer

---

### 4. Lemmatization

Convert words into their meaningful base form.

**Concepts Used:** WordNetLemmatizer

---

### 5. Part-of-Speech (POS) Tagging

Identify grammatical roles such as noun, verb, adjective, etc.

**Concepts Used:** pos_tag()

---

### 6. Word Frequency Analysis

Count how many times each word appears in the text.

**Concepts Used:** FreqDist

---

## Dataset Used

- Custom text sentences such as:
  - "I am in symbiosis college"  
  - "I like to ride bikes. I have my own bike."  

These were used to demonstrate different NLP techniques.

---

## Conclusion

Thus, various NLP techniques were successfully implemented using the NLTK library. The experiment provided practical understanding of text preprocessing methods such as tokenization, stop word removal, stemming, lemmatization, POS tagging, and frequency analysis, which are essential for text-based applications.

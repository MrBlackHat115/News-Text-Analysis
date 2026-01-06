# News-Text-Analysis

<img width="1041" height="500" alt="Screenshot 2026-01-05 214738" src="https://github.com/user-attachments/assets/5e350a62-5dbd-45d4-bd67-cc5c0d2305c6" />

This project implements a complete Natural Language Processing (NLP) pipeline using BBC news article titles.  
It focuses on text preprocessing, token analysis, Part-of-Speech (POS) tagging, and Named Entity Recognition (NER) to extract meaningful insights from news headlines.

## Project Objectives
- Clean and normalize real-world text data
- Analyze linguistic structure using POS tagging
- Identify people, locations, and organizations using NER
- Compare raw vs cleaned text representations

## Dataset
- Source: BBC News Articles (CSV)
- Size: 1,000 articles
- Fields used: Article titles
- Missing values: None

## NLP Techniques Used
- Lowercasing
- Stopword removal (with negation preserved)
- Punctuation removal
- Tokenization
- Stemming
- Lemmatization
- Unigram and Bigram analysis
- Part-of-Speech tagging
- Named Entity Recognition (NER)

## Libraries & Tools
- Python
- pandas
- NLTK
- spaCy
- Regular Expressions (re)

## Processing Pipeline
1. Load BBC dataset using pandas
2. Extract article titles
3. Clean text (lowercase, stopwords, punctuation)
4. Tokenize titles into word lists
5. Apply stemming and lemmatization
6. Generate unigrams and bigrams
7. Perform POS tagging with spaCy
8. Apply Named Entity Recognition
9. Analyze frequency of linguistic features

## Example Analysis
- Most frequent nouns, verbs, and adjectives
- Commonly mentioned locations and organizations
- Comparison of raw vs cleaned token distributions

## Installation
```bash
pip install pandas nltk spacy
python -m spacy download en_core_web_sm# BBC News NLP Analysis Pipeline

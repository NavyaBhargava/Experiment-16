## Navya Bhargava
## 25070123079

# Experiment 16: NLP Techniques on Text Data in Python

 ## Aim

To understand and implement basic Natural Language Processing (NLP) techniques such as tokenization, stopword removal, stemming, POS tagging, lemmatization, and word frequency analysis using NLTK in Python.

 ## Theory
 

Natural Language Processing (NLP) is a branch of Artificial Intelligence that enables computers to understand, interpret, and process human language.


NLP combines concepts from:

1)Linguistics

2)Computer Science

3)Machine Learning


One of the most commonly used NLP libraries in Python is Natural Language Toolkit (NLTK).

 
 # Important NLP Techniques
 
## 1️⃣ Tokenization

Tokenization is the process of breaking text into smaller units called tokens.

Tokens can be:

1)Words

2)Sentences

3)Characters


## 2️⃣ Sentence Tokenization


Sentence tokenization divides a paragraph into individual sentences.

## 3️⃣ Stop Word Removal


Stop words are common words that usually do not add much meaning to the sentence.

Examples:

is

the

and

in

a

These words are removed during text preprocessing.

## 4️⃣ Stemming


Stemming reduces words to their root form.

## 5️⃣ Part-of-Speech (POS) Tagging


POS tagging identifies the grammatical role of words in a sentence.

Examples:

1)Word	POS Tag

2)Python	

3)is	Verb

4)Powerful	Adjective

## 6️⃣ Word Frequency Count


Word frequency analysis counts how often each word appears in a text.


## 7️⃣ Lemmatization

Lemmatization reduces words to their base dictionary form (lemma).

Unlike stemming, lemmatization produces meaningful words.

Word	Lemma
Writing	Write
Studies	Study
Running	Run

---


nltk.download(): Downloads required NLP datasets like tokenizers, stopwords, and lexical resources.

word_tokenize(): Splits text into individual words (tokens).

sent_tokenize(): Splits text into sentences.

stopwords.words(): Provides a list of common words (like “is”, “the”) to remove from text.

set(): Converts list into a set for faster lookup during filtering.

List comprehension: Used to filter words by removing stopwords efficiently.

PorterStemmer(): Reduces words to their root form by removing suffixes.

stem(): Returns the stemmed (root) version of a word.

WordNetLemmatizer(): Converts words into their meaningful base (dictionary) form.

lemmatize(): Returns the correct base form of a word using vocabulary knowledge.

pos_tag(): Assigns grammatical tags (noun, verb, adjective, etc.) to each word.

FreqDist(): Calculates frequency distribution of words in a text.

most_common(): Returns most frequent words along with their counts.

POS Tagging: Identifies grammatical roles like noun (NN), verb (VB), adjective (JJ), etc.

Text preprocessing: Includes tokenization, stopword removal, stemming, and lemmatization for cleaning text.


## ✅ Conclusion

In this experiment, several fundamental NLP preprocessing techniques were implemented using Natural Language Toolkit in Python.
Techniques such as tokenization, stopword removal, stemming, POS tagging, word frequency analysis, and lemmatization help convert raw text into structured data, making it easier for machine learning models to analyze and process textual information.

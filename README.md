# Natural Language Processing Fundamentals in Python

Course Description
In this course, you'll learn Natural Language Processing (NLP) basics, such as how to identify and separate words, how to extract topics in a text, and how to build your own fake news classifier. You'll also learn how to use basic libraries such as NLTK, alongside libraries which utilize deep learning to solve common NLP problems. This course will give you the foundation to process and parse text as you move forward in your Python learning.

What is natural language processing?

You will learn the basics of NLP

Topic identification, text classification

NLP applications include:
Chatbots, translation, sentiment analysis etc.


## Regular expressions & word tokenization

This chapter will introduce some basic NLP concepts, such as word tokenization and regular expressions to help parse text. You'll also learn how to handle non-English text and more difficult tokenization you might find as you explore the wide world of NLP.

### Introduction to regular expressions

re library 

What exactly are regular expressions?

Strings with special syntax

Allow us to match patterns in other strings

Applications of regular expressions: 

Find all that web links in a document

Parse email addresses, remove or replace unwanted characters

### Common regex patterns: (?)

Practicing regular expressions: re.split() and re.findall()

Now you'll get a chance to write some regular expressions to match digits, strings and non-alphanumeric characters. Take a look at my_string first by printing it in the IPython Shell, to determine how you might best match the different steps.

Note: It's important to prefix your regex patterns with r to ensure that your patterns are interpreted in the way you want them to. Else, you may encounter problems to do with escape sequences in strings. For example, "\n" in Python is used to indicate a new line, but if you use the r prefix, it will be interpreted as the raw string "\n" - that is, the character "\" followed by the character "n" - and not as a new line.

### Introduction to tokenization

nltk library (Word tokenization with NLTK)

What is tokenization

Turning a string or document into tokens (Smaller chunks)

One step is preparing a text for NLP

You can create your own rules using regular expressions, For example: Breaking out words or sentences, separating punctuation, separating all hashtags in a tweet 

Why?

Easier to map part of speech, matching common words, Removing unwanted tokens, Determine meaning from simple text

Nltk tokenizers (?)

regex ranges and groups (?)

Regex with NLTK tokenization

Non-ascii tokenization

Charting word length with NLTK

Charting practice


## Simple topic identification

This chapter will introduce you to topic identification, which you can apply to any text you encounter in the wild. Using basic NLP models, you will identify topics from texts based on term frequencies. You'll experiment and compare two simple methods - bag-of-words and Tf-idf using NLTK and a new library - Gensim.

Word counts with bag-of-words

Bag-of-words picker

Building a Counter with bag-of-words

Simple text preprocessing

Text preprocessing steps

Text preprocessing practice

Introduction to gensim

What are word vectors?

Creating and querying a corpus with gensim

Gensim bag-of-words

Tf-idf with gensim

What is tf-idf?

Tf-idf with Wikipedia

## Named-entity recognition

This chapter will introduce a slightly more advanced topic - Named-entity recognition. You'll learn how to identify the who, what and where of your texts using pre-trained models on English and non-English text. You'll also learn how to use some new libraries - polyglot and spaCy - to add to your NLP toolbox.



Named Entity Recognition

NER with NLTK

Charting practice

Stanford library with NLTK

Introduction to SpaCy

Comparing NLTK with spaCy NER

spaCy NER Categories

Multilingual NER with polyglot

French NER with polyglot I

French NER with polyglot II

Spanish NER with polyglot


## Building a "fake news" classifier

Here, you'll apply the basics of what you've learned along with some supervised machine learning to build a "fake news" detector. You'll begin by learning the basics of supervised machine learning, and then move forward by choosing a few important features and testing ideas to identify and classify "fake news" articles. 


Classifying fake news using supervised learning with NLP

Which possible features?

Training and testing

Building word count vectors with scikit-learn


CountVectorizer for text classification

TfidfVectorizer for text classification

Inspecting the vectors


Training and testing a classification model with scikit-learn

Text classification models

Training and testing the "fake news" model with CountVectorizer

Training and testing the "fake news" model with TfidfVectorizer

Simple NLP, complex problems

Improving the model

Improving your model

Inspecting your model


<img src="https://analyticsinsight.b-cdn.net/wp-content/uploads/2020/09/NLP1-1024x542.jpeg" />

# NLP (Natural Lenguage Processing)

This repository holds a serie of challenges done for the NLP course, part of the IA Specialization at the University of Buenos Aires (UBA)

## Challenge N°1: word2vec

My first steps in NLP. Using the basic concepts of NLP, we coded by hand the conversion of sentences to vectors using, first of all, a simple **OneHotEncoding**, 
then **frequency vectors**, and finally **TFIDF** vectors. Once we had vectors instead of sentences, the documents of the corpus were compared using the **cosine
similarity** to analyse which sentences are closer to each other.

[Link to Colab](https://github.com/franz6ko/natural-lenguage-processing/blob/master/challenge_1_word2vec.ipynb)

## Challenge N°2: rule-based bot using DNN + spaCy

In this challenge, we put into practice the **preprocessing** in NLP using **tokenization**, **steeming** and **lemmatization** to build a rule-based 
customer service chat bot. During the cursus, we used the libraries **NLTK** and **SpaCY** for NLP but we chose SpaCy for this project.

[Link to Colab](https://github.com/franz6ko/natural-lenguage-processing/blob/master/challenge_2_bot_dnn_spacy.ipynb)

## Challenge N°3: custom embeddings using Gensim

It consisted of **training of custom embeddings** using the library **Gensim** to analyse the lyrics of songs written by different artists and their songwritting style. On a first stage, 
one particular artist was analysed: Radiohead. On a second stage, the concept of the word "love" was compared among 5 different artists to see what 
things/words/feelings they tend to associate with it.

[Link to Colab](https://github.com/franz6ko/natural-lenguage-processing/blob/master/challenge_3_custom_embedding_gensim.ipynb)

## Challenge N°4: word prediction using RNN

The concept of a **Recurrent Neural Network (RNN)** is put into practice on this challenge. A **many_to_one architecture** was implemented for doing **word prediction**
using a kaggle dataset of dialogues of serveral Marvel movies.

[Link to Colab](https://github.com/franz6ko/natural-lenguage-processing/blob/master/challenge_4_word_prediction.ipynb)

## Challenge N°5: reviews classification using LSTM

Using the improved **Long-Short Term Memory (LSTM)** layer and the **FastText** library which provides **pretrained embeddings**, a model was developed to classify reviews 
of a clothing ecommerce.

[Link to Colab](https://github.com/franz6ko/natural-lenguage-processing/blob/master/challenge_5_clothing_ecommerce_reviews.ipynb)

## Challenge N°6: Q&A bot using Seq2seq

In this challenge, a **conversational bot** was implemented using an **encoder-decoder seq2seq** architecture. The user can talk interactively with the bot which answers
surprisingly well with well-formed sentences given its resources and potential. 

[Link to Colab](https://github.com/franz6ko/natural-lenguage-processing/blob/master/challenge_6_bot_qa.ipynb)

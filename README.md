# Discoverify-Content Based Music Recommendation System

Our project involves the development of a content-based music recommendation system using the Spotify Million Song dataset. 
Leveraging the power of Python and popular libraries such as Pandas, NLTK, and TFIDF Vectorizer,
we have created a sophisticated system that provides personalized music recommendations based on the content of songs.

### Spotify Million Song Dataset:

We utilized the extensive Spotify Million Song dataset. This dataset includes information such as artist, song name, link of the song and lyrics of the song.

### Content-Based Recommendation:

The recommendation system focuses on the content of the songs rather than collaborative filtering. This means that it suggests songs based on their inherent features and characteristics, making the recommendations more personalized to individual user preferences.

### Text Processing with Pandas and NLTK:

To analyze and understand the textual aspects of the dataset, we used the Natural Language Toolkit (NLTK) and the Pandas library for text processing. This includes tasks such as curating the dataset, tokenization, and stemming to extract valuable information from the lyrics.

### TFIDF Vectorizer:

The Term Frequency-Inverse Document Frequency (TFIDF) Vectorizer was used to convert the processed textual data into numerical vectors. This transformation enables the system to quantify the importance of words in describing the content of each song accurately.

### Recommendation Algorithm:

Our recommendation algorithm calculates the similarity between songs based on TFIDF vectors using cosine similarity. The system recommends songs with similar textual content, ensuring that the recommendations are compatible with the user's preferences and the content they enjoy.

## How To Use

To use the application, simply run the Jupyter Notebook file in NLP_Model folder. In this way, you will be able to perform the necessary operations on the data set and train the model with this data. In the last part, you can get your output by giving the requested inputs to the program appropriately.

## Programming Language and Required Libraries

- Python 3.12.0
- Pandas 2.1.4
- NLTK 3.8.1
- Numpy <= 1.25.2

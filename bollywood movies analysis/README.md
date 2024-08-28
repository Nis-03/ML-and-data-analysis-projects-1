Bollywood Movie Dialogue Analysis
This project analyzes the content of top-grossing Bollywood movies by extracting dialogue from subtitle files, generating a document-term matrix using TF-IDF, and visualizing the most common words using word clouds.

Project Overview
The goal of this project is to analyze the dialogue content of the top 3 highest-grossing Bollywood movies from the last five years to determine which words and themes are most commonly mentioned.

Steps Involved
1.Subtitle Extraction: Extract dialogue from .srt subtitle files for each movie.
2.Text Preprocessing: Clean the extracted text by removing special characters, stop words, and performing lemmatization.
3.TF-IDF Analysis: Create a document-term matrix using the TF-IDF method to identify important words in the dialogue.
4.Word Cloud Visualization: Generate word clouds for each movie to visualize the most common words.

Tools and Libraries Used
Python
scikit-learn (TF-IDF Vectorizer)
NLTK (Stop words, Lemmatization)
WordCloud (Word Cloud Generation)
matplotlib (Visualization)
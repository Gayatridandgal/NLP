# YouTube Comment Scraper and TF-IDF Vectorization
### This project scrapes YouTube video comments, processes them, and generates TF-IDF vectors. The generated vectors are stored in a pickle file for further analysis or modeling.

### Table of Contents
Overview

Prerequisites

Installation

Project Structure

Steps

1. Scrape Comments
2. Pre-process Comments
3. Generate TF-IDF Vectors
4. Save TF-IDF Vectors

## Overview
This project performs the following tasks:

Scrapes comments from a YouTube video using the youtube-comment-downloader Python package.
Pre-processes the comments by removing punctuation, stopwords, and other unnecessary characters.
Converts the pre-processed comments into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency).
Saves the TF-IDF vectors into a pickle file (tfidf_vectors.pkl) for further analysis.


## Prerequisites
Before running the project, ensure you have the following installed:

-Python 
-pandas
-youtube-comment-downloader
-scikit-learn
-nltk
-pickle

## Steps
1. Scrape Comments
The script reads a CSV file containing YouTube comments or directly scrapes comments from a YouTube video using the youtube-comment-downloader library.
2. Pre-process Comments
Pre-process the comments by converting them to lowercase, removing punctuation, URLs, stopwords, and non-alphabetic characters.
3. Generate TF-IDF Vectors
Use TfidfVectorizer from the scikit-learn library to generate TF-IDF vectors for the pre-processed comments.
4. Save TF-IDF Vectors
Save the generated TF-IDF vectors into a pickle file (tfidf_vectors.pkl), which can be loaded later for machine learning models or further analysis.


### Additional Notes:
Make sure to replace the URL and repository name in the Installation section with your own GitHub repository details.
The requirements.txt file should include the following:

-pandas
-youtube-comment-downloader
-scikit-learn
-nltk











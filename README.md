# movie-recommender-mvp

This is a simple Collaborative Filtering-based Movie Recommendation App built using Python, Pandas, Scikit-learn, and Streamlit. It utilizes the MovieLens 100k dataset to provide item-based movie recommendations to users based on their past ratings.

## Features
Loads and merges movie rating data with movie titles.

Creates a user-item matrix for collaborative filtering.

Computes cosine similarity between movies.

Recommends movies similar to a selected movie.

Simple web interface using Streamlit.

## How to Run
Clone the repository or download the code.

Make sure you have the required packages installed:

### pip install -r requirements.txt

Run the Streamlit app:


### streamlit run app.py


## Dataset Used
Ratings: https://files.grouplens.org/datasets/movielens/ml-100k/u.data

Movies: https://files.grouplens.org/datasets/movielens/ml-100k/u.item

The dataset contains 100,000 ratings from 943 users on 1,682 movies.

## Tech Stack

Python

Pandas

NumPy

Scikit-learn

Streamlit

## Methodology

A User-Item Matrix is created from the merged dataset.

Cosine Similarity is computed between movie vectors.

Based on a selected movie, the app finds the most similar ones and displays them as recommendations.

Movie Recommendation System

A content-based movie recommender that suggests movies similar to the one you input based on metadata such as genres,
keywords, tagline, cast, and director. The system uses TF-IDF vectorization and cosine similarity to find similar movies.

Features
Recommends movies based on a given favorite movie.
Uses TF-IDF for feature extraction and cosine similarity for movie comparison.
Takes user input to find the closest matching movie title from the dataset.
Suggests top 30 similar movies.

Tech Stack
Python 
NumPy & Pandas (Data processing)
Scikit-learn (TF-IDF Vectorization, Cosine Similarity)
difflib (Fuzzy matching)

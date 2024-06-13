# Movie Recommendation System

## Importance of Recommendation Systems

Recommendation systems play a vital role in enhancing user experience and engagement across various platforms. In the entertainment industry, such as movie streaming platforms, recommendation systems help users discover new content that aligns with their preferences, leading to increased user satisfaction and retention.

## Movie Recommendation System Overview

This project focuses on building a content-based movie recommendation system. Unlike collaborative filtering methods that rely on user behavior data, content-based recommendation systems recommend movies based on the similarity of their attributes to movies the user has shown interest in.

## Content-Based Recommendation System

A content-based recommendation system suggests movies to users based on the similarity of movie attributes such as genres, keywords, cast, crew, and plot summaries. This approach ensures personalized recommendations without the need for user interaction data.

## How It Works

### Data Collection and Preprocessing:

- Gathered data from the TMDB (The Movie Database) dataset, including movie details like genres, keywords, cast, crew, etc.
- Preprocessed the data by extracting relevant features and cleaning the text data.

### Feature Vectorization:

- Utilized techniques like CountVectorizer or TF-IDF to convert textual features (genres, keywords, cast, crew) into numerical vectors.

### Similarity Calculation:

- Calculated cosine similarity between movie vectors to determine how similar they are based on their attributes.

### Recommendation Generation:

- When a user searches for a movie, the system calculates similarity scores between the user's preferences (based on past interactions) and all available movies.
- Ranked movies based on their similarity scores and recommended the top-ranked movies to the user.

## Dataset

The dataset used for this project includes two CSV files:

- movies.csv: Contains movie details like budget, genres, keywords, cast, crew, etc.
- credits.csv: Contains movie credits information including movie_id, title, cast, and crew.

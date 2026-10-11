# 🎬 Movie Recommendation System

A beginner-friendly Python project that recommends 5 similar movies based on their story descriptions, genres and keywords.

## Features

- Movie selection dropdown
- Recommend Movies button
- Top 5 similar movies with genres and similarity scores
- Styled interface inside Google Colab
- Handles movie names regardless of capitalization
- Displays a message when a movie is not found

## Tools Used

- Python
- Pandas
- Scikit-learn
- ipywidgets
- Google Colab

## How It Works

TF-IDF converts movie descriptions, genres and keywords into numerical vectors. Cosine similarity compares these vectors and ranks similar movies.

Similarity scores represent text similarity, not ratings or accuracy percentages.

## Dataset

This project uses the TMDB 5000 Movie Dataset:

https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Download and extract `tmdb_5000_movies.csv` before running the notebook.

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Upload `tmdb_5000_movies.csv` to the Colab session.
3. Run the required setup, preprocessing, recommendation and interface cells in order.
4. Select a movie from the dropdown.
5. Click Recommend Movies.

The interface runs inside the notebook. After a session reset, upload the CSV again and rerun the setup cells.

## Limitations

Recommendations depend on matching text and metadata, so some results may be less relevant. Recommendation quality has not been formally evaluated.

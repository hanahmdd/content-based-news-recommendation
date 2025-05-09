# Content‑Based News Recommendation System

This project builds a simple content‑based recommender that suggests news articles based on user preferences.  
It uses the [MIND dataset](https://www.kaggle.com/datasets/arashnic/mind-news-dataset/data) and TF‑IDF + cosine similarity.

## Structure

- **data/news.csv**: Article metadata (titles, abstracts, categories).
- **notebooks/**
  - `01_data_preprocessing.ipynb`: Load & clean data; extract TF‑IDF features.
  - `02_user_profile_construction.ipynb`: Build user profile vector.
  - `03_content_similarity.ipynb`: Compute cosine similarities.
  - `04_ranking_and_recommendation.ipynb`: Rank & output top‑N recommendations.
- **results/**
  - `sample_recommendations.csv`: Example output.
  - `user_feedback_notes.txt`: Placeholder for future feedback.
- **requirements.txt**: Python dependencies.

## Setup

1. Clone this repo  
   ```bash
   git clone <repo-url>
   cd news-recommender

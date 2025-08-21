# AI_book_recommender
Sentiment-aware, data-cleaned book recommendations using classic recommenders + lightweight NLP.
This project builds a hybrid book recommender that combines:
Data cleaning & redundancy removal
Sentiment analysis on user reviews
Content similarity (TF-IDF / embeddings)
Weighted rating (IMDB-style)
Simple, explainable scoring with NumPy & visualizations with Matplotlib
✨ Features
Robust preprocessing: drops redundant columns, handles missing values, de-duplicates books/users.
Sentiment pipeline: review cleaning → sentiment scoring (e.g., VADER/TextBlob) → normalized sentiment.
Hybrid scoring: final_score = α·weighted_rating + β·sentiment + γ·similarity.
Content-based recommendations using title/author/genres/description.
Reproducible EDA with Matplotlib plots.
CLI for quick runs and optional API server.
 Tech Stack
Python, NumPy, Pandas, Scikit-learn
NLTK (VADER) or TextBlob (choose one)
Matplotlib
(Optional) FastAPI / Uvicorn for serving

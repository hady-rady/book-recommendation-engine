# Book Recommendation Engine

## Project Overview
A machine learning application that recommends books based on user ratings and similarities between readers' preferences.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- K-Nearest Neighbors (KNN)
- Cosine Similarity
- Data Preprocessing

## How It Works
1. Load and preprocess book and rating datasets.
2. Filter users and books based on rating frequency.
3. Build a user-book rating matrix.
4. Train a KNN model using cosine distance.
5. Recommend similar books based on a selected title.

## Key Features
- Book recommendations based on rating patterns.
- Similarity-based recommendations using KNN.
- Data filtering and preprocessing.
- Model testing and evaluation.

## Project Files
- `book_recommendation_engine.ipynb` — Notebook containing the implementation and testing.

## How to Run
Open the notebook in Google Colab, run the cells in order, and use the `get_recommends()` function to generate book recommendations.

## Dataset
The project uses book information and user ratings to generate recommendations.

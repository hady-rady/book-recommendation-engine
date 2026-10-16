# Book Recommendation Engine

## Project Overview
A machine learning system that recommends books based on user ratings. It uses the K-Nearest Neighbors (KNN) algorithm to identify books with similar rating patterns and suggest relevant recommendations.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- K-Nearest Neighbors (KNN)
- Cosine Similarity

## Project Workflow
1. Load and explore the book ratings dataset.
2. Filter users and books based on the number of ratings.
3. Prepare a user-book rating matrix.
4. Train a KNN model using cosine distance.
5. Recommend similar books based on a selected title.

## Features
- Book recommendations based on rating patterns.
- Data preprocessing and filtering.
- Similarity-based recommendation using KNN.

## How to Run
1. Open `book_recommendation_engine.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Use the `get_recommends()` function with a book title to generate recommendations.

## Project Goal
To apply machine learning and recommendation-system concepts to a real-world book recommendation task.

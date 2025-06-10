# movie-recommendation-system
A machine learning project to recommend movies based on similarity
# 🎬 Movie Recommendation System (Content-Based)

A machine learning project to recommend movies based on content similarity using TF-IDF and cosine similarity.

---

## 📚 Overview

This project applies natural language processing and similarity metrics to recommend movies similar to a user’s input.  
The model analyzes genres and computes the closeness between movie descriptions using TF-IDF vectorization.

---

## 📊 Dataset

- **Source**: Local CSV file (e.g., `movies.csv`)
- **Size**: ~1,000+ movie records with features like `title`, `genres`

---

## 🚀 Features

- TF-IDF Vectorization of movie genres
- Cosine similarity to measure closeness between movies
- Input-based movie name matching using `difflib`
- Content-based filtering system
- Simple and interactive notebook interface

---

## 🧠 Machine Learning Concepts

- Text Vectorization using `TfidfVectorizer`
- Cosine Similarity for recommendation ranking
- String Matching using `difflib.get_close_matches`

---

## 💻 Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Jupyter Notebook
- matplotlib, seaborn (optional for visualization)

---

## 📈 Example Workflow

1. User enters a movie they like (e.g., `"Avatar"`)
2. System finds the closest matching title from the dataset
3. Recommends top N similar movies based on genre similarity

---

## 🧪 Sample Input & Output
Input: Enter a movie you like: Inception

Top 5 Recommended Movies:

Interstellar

The Matrix

Shutter Island

Memento

Tenet

🎬 Movie Recommendation System
A Machine Learning–based **Movie Recommendation System** that suggests movies to users based on their preferences. This project demonstrates the use of data preprocessing, similarity measures, and recommendation techniques commonly used in real-world platforms like Netflix and Amazon Prime.
📌 Project Overview
Recommender systems help users discover relevant content by analyzing user behavior and item characteristics.  
This project implements a **Content-Based Movie Recommendation System** using movie metadata.

 🚀 Features

- Recommends movies similar to a selected movie
- Uses cosine similarity for measuring movie similarity
- Text vectorization using TF-IDF / CountVectorizer
- Simple and efficient implementation
- Easy to extend to collaborative filtering

 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries Used:**
  - NumPy
  - Pandas
  - Scikit-learn
  - NLTK (optional)
  - Streamlit (optional for UI)

 📂 Dataset

- Movie metadata dataset (movies, genres, overview, keywords, cast, crew)
- Source: Kaggle / TMDB Dataset


## ⚙️ How It Works

1. Load and preprocess the movie dataset  
2. Combine important features (genres, overview, keywords, etc.)
3. Convert text data into numerical vectors
4. Calculate similarity using **Cosine Similarity**
5. Recommend top N similar movies based on similarity score

📈 Recommendation Technique

- **Content-Based Filtering**
  - Recommends movies similar to the movie selected by the user
  - Uses movie attributes instead of user ratings

---
 Example Output

Recommended Movies:
1. Guardians of the Galaxy
2. Interstellar
3. Star Wars
4. Avengers
5. Inception

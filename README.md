
# 🎬 Movie Recommender System Using Machine Learning

> A smart web app that helps you find movies you'll love — built using ML, Streamlit, and cosine similarity.

---

## 🚀 Overview

Recommendation systems are everywhere — from Netflix to Spotify — helping users discover content they’ll enjoy without spending hours searching.

This project builds a **movie recommendation system** that suggests similar movies based on user preferences using **content-based filtering** and **cosine similarity**.

---

## 🔍 Types of Recommendation Systems

### 1️⃣ Content-Based Filtering

* Uses features like genre, cast, and keywords.
* Suggests similar items to what the user liked before.
* Examples: YouTube, Spotify.

### 2️⃣ Collaborative Filtering

* Based on user-user or item-item interactions (ratings).
* Example: Amazon, Goodreads.
* Drawback: Cold-start problem and high computation for large data.

### 3️⃣ Hybrid Filtering

* Combines content-based and collaborative filtering.
* Used by modern platforms for better recommendations.

---

## 📊 Dataset

* Source: [TMDB Movie Metadata on Kaggle](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)
* Used `tmdb_5000_movies.csv` for content-based filtering.

---

## 🧠 ML Concept Used

**Cosine Similarity**

* Measures similarity between movie vectors.
* Score ranges from 0 (no similarity) to 1 (exact match).
* Used for finding similar movies based on feature vectors.




## 🛠️ How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Sauravyadav0811/Movie-Recommendation-System-using-machine-learning.git
cd Movie-Recommendation-System-using-machine-learning
```

### 2️⃣ Create and activate a conda environment

```bash
conda create -n movie python=3.7.10 -y
conda activate movie
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the notebook to generate models

```bash
# Use Jupyter to run this
Movie Recommender System Data Analysis.ipynb
```

### 5️⃣ Start the app

```bash
streamlit run app.py
```

---

## 📂 Project Structure

```
├── data/                  # Dataset files
├── demo/                  # Demo images
├── src/                   # Source code
├── app.py                 # Streamlit app
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
```

---

## 📘 License

Licensed under the MIT License. See `LICENSE` for details.



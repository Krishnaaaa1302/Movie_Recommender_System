# 🎬 Movie Recommender System

A full end-to-end **Movie Recommender System** that suggests similar movies based on user selection.  
This project uses the **TMDB API** to fetch **movie posters** and a **Kaggle Movies Dataset** for building the recommendation engine.  
It is deployed on **Heroku** for live usage.

---

## 🚀 Features
- **Content-based Recommendation** using cosine similarity.
- Fetches **high-quality movie posters** from TMDB API.
- Interactive **frontend** built with Streamlit.
- Fully **deployed** on Heroku for easy access.
- End-to-end pipeline:
  - Data Gathering (Kaggle)
  - Data Preprocessing & Feature Engineering
  - Model Building & Evaluation
  - API Integration for Posters
  - Deployment

---

## 📂 Dataset
- **Source:** [Kaggle - TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Files used:
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv`

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:**
  - `pandas`, `numpy` → Data processing
  - `scikit-learn` → Machine learning & similarity computation
  - `requests` → API calls to TMDB
  - `streamlit` → Web app
  - `pickle` → Model saving
- **Deployment:** Heroku
- **API:** [The Movie Database (TMDB) API](https://www.themoviedb.org/documentation/api)

---


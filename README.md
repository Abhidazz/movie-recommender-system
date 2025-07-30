# 🎬 Movie Recommender System

A content-based movie recommendation system built using Python and Streamlit, powered by TMDB (The Movie Database) API. This app suggests similar movies based on your selection and provides posters and overviews using real-time API data.

---

## 🚀 Features

- 🔍 Search and select any movie from the database
- 🎥 Get 5 similar movie recommendations
- 🖼️ See posters of recommended movies using TMDB API
- 🧠 Recommendation based on **cosine similarity** of genres, tags, and keywords
- 🧰 Easy-to-use Streamlit web interface

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Machine Learning**: Scikit-learn (cosine similarity)
- **Data Source**: TMDB API
- **Storage**: Pickle files (`movie.pkl`, `similarity.pkl`, `movie_dict.pkl`)

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
# 🎵 Spotify Music Recommendation System

A content-based music recommendation system built using Machine Learning that suggests similar songs based on audio features.

## 📊 Dataset
- **Source:** Kaggle - Spotify Tracks Dataset
- **Size:** 114,000 songs | 125 Genres
- **Features:** Danceability, Energy, Tempo, Valence, Acousticness, and more

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn (KNN Algorithm)
- Matplotlib & Seaborn
- Jupyter Notebook

## ⚙️ How It Works
1. Load and clean 114,000 Spotify songs
2. Normalize audio features using MinMaxScaler
3. Train K-Nearest Neighbors model with Cosine Similarity
4. Input any song name → Get Top 10 similar songs

## 📈 Results
- Successfully recommends songs with 99%+ similarity scores
- Handles 81,344 unique songs after data cleaning
- Supports search across 114 music genres

## 🚀 How To Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
Then open `spotify_recommendation.ipynb` in Jupyter Notebook and run all cells.

## 📁 Project Structure

## 👤 Author
**Mohammad Bilal** — Data Science  
📧 bilal031301@gmail.com

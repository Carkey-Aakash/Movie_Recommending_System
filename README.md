🎬 Movie Recommending System

A content-based movie recommendation system that suggests similar movies based on the movie selected by the user.
This model uses cosine similarity on movie metadata features to generate recommendations and displays movie posters fetched from TMDB API.
The web interface is built using Streamlit for an interactive user experience.

🚀 Features

Recommends top similar movies based on user selection

Uses Content-Based Filtering (Cosine Similarity)

Fetches movie posters using TMDB API

Simple & user-friendly Streamlit web interface

Model trained on movie dataset (e.g., TMDB dataset)

🛠️ Tech Stack
Component	Technology Used
Programming Language	Python
Data Processing	Pandas, Numpy
Machine Learning	Scikit-learn
Web App	Streamlit
API for Posters	TMDB API
Model Storage	Pickle

📂 Project Structure
Movie-Recommender/
│
├── app.py
├── movie_list.pkl
├── similarity.pkl
└── README.md

🔧 Installation and Setup

1. Clone the repository

git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender


2. Install dependencies

pip install -r requirements.txt


3. Run the application

streamlit run app.py

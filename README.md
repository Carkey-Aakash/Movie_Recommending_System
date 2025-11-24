# 🎬 Movie Recommending System

A content-based movie recommendation system that suggests similar movies based on the movie selected by the user. This model uses **cosine similarity** on movie metadata features to generate recommendations and displays movie posters fetched from the **TMDB API**. The interface is built using **Streamlit** for an interactive user experience.

---

## 🚀 Features

- Recommends **top similar movies** based on selected movie  
- Uses **Content-Based Filtering** (Cosine Similarity)  
- Fetches movie posters using **TMDB API**  
- Simple & user-friendly **Streamlit Web UI**  
- Model trained on movie dataset (e.g., TMDB Dataset)

---

## 🛠️ Tech Stack

| Component          | Technology Used       |
|-------------------|----------------------|
| Programming Lang. | Python               |
| Data Processing   | Pandas, NumPy        |
| Machine Learning  | Scikit-learn         |
| Web App UI        | Streamlit            |
| Model Storage     | Pickle (.pkl files)  |

---
## Screenshot 
Recommendation Page
<img width="946" height="623" alt="Image" src="https://github.com/user-attachments/assets/7545d3c6-265a-4ae9-b4c1-d4161e19f11e" />
<img width="937" height="610" alt="Image" src="https://github.com/user-attachments/assets/ac16ea0c-8638-4418-8c3a-8df456732d5e" />

## 🔧 Installation and Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
2️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
3️⃣ Run the Application
bash
Copy code
streamlit run app.py

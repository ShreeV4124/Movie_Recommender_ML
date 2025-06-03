🎬 Movie Recommender System

A personalized movie recommender system built using machine learning techniques and the TMDB API. This web app helps users find movies similar to their favorites, complete with posters and titles, all presented in a clean Streamlit interface.


🚀 Features

🔍 Content-Based Recommendation: Suggests movies based on textual and metadata similarity.

🧠 Precomputed Similarity Matrix: Fast and efficient recommendations using cosine similarity.

🖼️ Movie Posters Integration: Uses TMDB API to fetch real movie posters.

🌐 Streamlit Web App: User-friendly and interactive interface for seamless movie discovery.



🛠️ Tech Stack: 

Python - Pandas, NumPy, Scikit-learn

Streamlit – For the web interface

TMDB API – For fetching movie posters

Pickle – For loading precomputed similarity data



📁 Project Structure
perl

movie-recommender-system/
│
├── tmdb_5000_movies.csv            # Dataset
├── tmdb_5000_credits.csv           # Dataset
├── app.py                          # Main Streamlit app
├── movies_dict.pkl                 # Serialized movie metadata
├── similarity.pkl                  # Serialized similarity matrix
├── README.md                       # Project documentation




📦 Setup Instructions

1. Clone the repository
   
git clone https://github.com/ShreeV4124/Movie_Recommender_ML.git
cd movie-recommender-system

2. Install dependencies
It’s recommended to use a virtual environment.

pip install -r requirements.txt
Note: Create a requirements.txt with:
streamlit
pandas
numpy
scikit-learn
requests


3. Run the app : streamlit run app.py

🔑 TMDB API Key
This project uses TMDB to fetch movie posters. Replace the API key in app.py:   API_KEY = "your_tmdb_api_key"




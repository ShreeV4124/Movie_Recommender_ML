🎬 Movie Recommender System
A personalized movie recommender system built using machine learning techniques and the TMDB API. This web app helps users find movies similar to their favorites, complete with posters and titles, all presented in a clean Streamlit interface.


🚀 Features
🔍 Content-Based Recommendation: Suggests movies based on textual and metadata similarity.

🧠 Precomputed Similarity Matrix: Fast and efficient recommendations using cosine similarity.

🖼️ Movie Posters Integration: Uses TMDB API to fetch real movie posters.

🌐 Streamlit Web App: User-friendly and interactive interface for seamless movie discovery.

🛠️ Tech Stack
Python

Pandas, NumPy, Scikit-learn

Streamlit – For the web interface

TMDB API – For fetching movie posters

Pickle – For loading precomputed similarity data

📁 Project Structure
perl
Copy
Edit
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
bash
Copy
Edit
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
2. Install dependencies
It’s recommended to use a virtual environment.

bash
Copy
Edit
pip install -r requirements.txt
Note: Create a requirements.txt with:

txt
Copy
Edit
streamlit
pandas
numpy
scikit-learn
requests
3. Run the app
bash
Copy
Edit
streamlit run app.py
🔑 TMDB API Key
This project uses TMDB to fetch movie posters. Replace the API key in app.py:

python
Copy
Edit
API_KEY = "your_tmdb_api_key"
You can get your free API key by creating an account here.

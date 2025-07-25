# 🎵 Music Recommendation System

A web-based music recommendation system that suggests similar songs based on the selected input using machine learning and Spotify API. Built using **Streamlit**, **Scikit-learn**, and **Spotipy**.

## 🚀 Features

- Recommends top 5 songs similar to the selected track.
- Fetches album cover images using Spotify API.
- Interactive Streamlit UI for user-friendly experience.

## 📁 Project Structure

📦Music-Recommendation-System
├── app.py # Streamlit web app script
├── final.ipynb # Notebook for preprocessing and model creation
├── df.pkl # Pickled song dataset
├── similarity.pkl # Pickled similarity matrix
└── README.md # Project documentation

bash
Copy
Edit

## 🔧 Installation

1. **Clone the repository**

```bash
git clone https://github.com/appump/Music-Recommendation-System.git
cd Music-Recommendation-System
Create and activate a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
If requirements.txt is not available, install manually:

bash
Copy
Edit
pip install streamlit spotipy scikit-learn pandas numpy
Run the application

bash
Copy
Edit
streamlit run app.py
🧠 How It Works
final.ipynb processes the music dataset and calculates cosine similarity.

df.pkl stores the song data.

similarity.pkl stores the precomputed similarity matrix.

app.py handles UI, user input, and displays recommendations along with album covers fetched via Spotify API.

🔑 Spotify API
To use the Spotify API:

Create an app at Spotify Developer Dashboard

Replace CLIENT_ID and CLIENT_SECRET in app.py with your credentials.

📷 Demo
<!-- Replace with actual UI screenshot -->

🛠️ Future Improvements
Add genre/artist filtering

Include audio feature-based recommendations (tempo, mood, etc.)

Deploy the app using Streamlit Cloud or Heroku

👨‍💻 Author
Appu Patil

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
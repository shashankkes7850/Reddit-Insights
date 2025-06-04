📊 Reddit Insights
Reddit Insights is a web-based analytics tool that provides sentiment analysis and topic modeling on Reddit discussions. It helps users understand public opinion, identify trending topics, and summarize discussions in a simple and intuitive dashboard.

🔍 Features
🔎 Search by Subreddit or Keyword

🧠 Sentiment Analysis (Positive / Negative / Neutral)

📈 Topic Modeling & Visualization with BERTopic

🗝️ Key Terms Extraction from Reddit Posts

📄 Post-Level Sentiment Classification

📊 Interactive Charts (Plotly)

📝 Discussion Summary Generator

🛠️ Tech Stack
Frontend:

React.js

TailwindCSS

Backend:

Flask 3.0

Flask-CORS

Python-dotenv

MongoDB (via PyMongo)

NLP & ML:

Transformers (Hugging Face)

BERTopic

Sentence-Transformers

Scikit-learn

UMAP & HDBSCAN

NLTK, spaCy

Data Handling:

Pandas

NumPy

Visualization:

Plotly

Reddit API:

PRAW (Python Reddit API Wrapper)

🐍 Backend Requirements
Below are the Python dependencies used in the backend:

text
Copy
Edit
flask==3.0.0
flask-cors==4.0.0
pandas==2.1.4
numpy==1.26.2
transformers==4.36.2
bertopic==0.16.0
pymongo==4.6.1
python-dotenv==1.0.0
praw==7.7.1
scikit-learn==1.3.2
torch==2.1.2
sentence-transformers==2.2.2
umap-learn==0.5.5
hdbscan==0.8.33
plotly==5.18.0
nltk==3.8.1
spacy==3.7.2
Install with:

bash
Copy
Edit
pip install -r requirements.txt
🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/reddit-insights.git
cd reddit-insights
2. Set Up Backend
bash
Copy
Edit
cd backend
python -m venv venv
# Activate the virtual environment:
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

pip install -r requirements.txt
python app.py
3. Set Up Frontend
bash
Copy
Edit
cd ../frontend
npm install
npm start

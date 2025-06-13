# 🐦 Twitter Data Extraction (Free Tier - v2 API)

This project fetches real-time tweets using Twitter's v2 API and saves them into a structured JSON file for further analysis.

## 📌 Features
- Uses Twitter/X API v2 with free-tier access
- Extracts tweets based on keyword or hashtag
- Saves data in a structured JSON format
- Easy to adapt for SQLite or Pandas DataFrame
- Ready for use in analytics, dashboards, or sentiment analysis

## 🛠️ Requirements
- Python 3.7+
- Tweepy (v4+)

Install dependencies:
```bash
pip install -r requirements.txt

🚀 How to Run
Get your Bearer Token from developer.x.com

Replace your_bearer_token in twitter_fetch_v2.py

python twitter_fetch_v2.py
Check the output JSON file (e.g., Pakistan_2025-06-13-15-42.json)

📂 Sample Output

[
  {
    "id": 123456789,
    "text": "This is a tweet about Pakistan...",
    "user": {
      "screen_name": "user123",
      "followers_count": 500
    }
  }
]
📊 Future Ideas
Store tweets in a SQLite/PostgreSQL database

Create a dashboard in Streamlit or Tableau

Apply sentiment analysis using TextBlob or Vader


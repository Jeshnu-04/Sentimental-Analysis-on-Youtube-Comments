YouTube Comment Sentiment Analysis
This project performs sentiment analysis on YouTube video comments using the VADER SentimentIntensityAnalyzer. It fetches comments via the YouTube API, filters out irrelevant data (hyperlinks, emoji-heavy text), analyzes sentiments (Positive, Negative, Neutral), and visualizes the results.

Features
Fetches YouTube comments using the video URL.

Filters irrelevant comments (hyperlinks, non-alphanumeric, emoji-heavy).

Analyzes sentiments using VADER.

Classifies comments as Positive, Negative, or Neutral.

Visualizes sentiment distribution using bar charts.

Tools and Libraries
Python

YouTube Data API

VADER SentimentIntensityAnalyzer

emoji

matplotlib

How to Run
Clone the repository.

Install required libraries:
pip install -r requirements.txt

Add your YouTube API key in the API_KEY variable.

Run the script and input a YouTube video URL.

# Stock Market Prediction Using Sentimental Analysis

## Overview
This project automates the process of monitoring financial news, summarizing key insights, and analyzing sentiment for specific assets. It is designed to help traders and investors make informed decisions by providing sentiment-based insights for stocks and cryptocurrencies like Bitcoin, Ethereum, Tesla, and Gamestop.

## Features
Web Scraping:
Scrapes financial news articles from platforms like Yahoo Finance using Python and BeautifulSoup.

## Text Summarization:
Leverages a fine-tuned Hugging Face Pegasus Transformer model for summarizing news articles into concise and actionable insights.

## Sentiment Analysis:
Implements a pre-trained transformer-based sentiment analysis pipeline to classify articles as positive, negative, or neutral for targeted assets.

## Extensibility:
Easily configurable to add more stocks or cryptocurrencies to the pipeline.

## Data Export:
Exports sentiment scores and summaries to CSV files for further analysis.

## Installation
Prerequisites
Ensure the following are installed on your system:

Python 3.8 or above
Install the required Python libraries by running:
pip install -r requirements.txt

Clone the Repository
git clone https://github.com/Aryansukhadia/SMP.git
cd financial

Usage
Run the Script
Execute the notebook or Python script:

jupyter notebook Stock-Sentiment_1.1.ipynb

Add Assets:
Update the assets list in the script to monitor sentiment for additional stocks or cryptocurrencies.

Export Results:
The pipeline generates a CSV file containing sentiment scores and article summaries for analysis.

Visualize Data:
Use the exported CSV file to visualize sentiment trends using tools like Tableau, Plotly, or Excel.

Technologies Used
Languages and Libraries:

Python

BeautifulSoup (Web Scraping)

Hugging Face Transformers (Text Summarization and Sentiment Analysis)

Pandas and Numpy (Data Processing)

Deployment (Optional):

Flask or Streamlit for a user-friendly dashboard.
Docker for containerization.

## Future Enhancements

Real-Time Updates:
Integrate APIs like Alpha Vantage for real-time news and stock/crypto price monitoring.

Interactive Dashboards:
Build a Streamlit or Flask-based interface to display sentiment trends and summaries dynamically.

Model Performance Metrics:
Add evaluation metrics for summarization and sentiment analysis pipelines.

Deployment:
Deploy the pipeline on cloud platforms (AWS/Heroku) for continuous monitoring.

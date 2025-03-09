# 📊 Google Play Store Reviews analysis

## 📌 Overview
This project analyzes the impact of major app updates on user engagement and sentiment for **X (formerly Twitter), Instagram, Reddit, and Snapchat**. By performing **sentiment analysis** on Google Play Store reviews, we examine how updates and changes—such as Elon Musk’s acquisition of X—have influenced user behavior.

## 🎯 Objectives
- **Analyze** the effect of major app updates on user engagement and sentiment over time.
- **Perform Sentiment Analysis** using NLP to classify user reviews as **positive, negative, or neutral**.
- **Identify Key Features** that drive positive sentiment and contribute to user retention.
- **Quantify Sentiment Trends** across platforms by detecting patterns in user responses to updates and ownership changes.

## 🛠️ Methodology
1. **Web Scraping**: Collected ~40,000 reviews per app from the **Google Play Store**.
2. **Data Cleaning**: Removed duplicates and incomplete entries to improve data quality.
3. **Exploratory Data Analysis (EDA)**: Identified trends and insights from user reviews.
4. **Sentiment Analysis**: Used **Hugging Face's CardiffNLP Twitter-RoBERTa model** to classify user sentiments.

## 📊 Data Processing
- **Instagram**: 29,600 cleaned reviews
- **Reddit**: 34,420 cleaned reviews
- **X (Twitter)**: 31,952 cleaned reviews
- **Snapchat**: 27,783 cleaned reviews

## 🔍 Sentiment Analysis
- Utilized **cardiffnlp/twitter-roberta-base-sentiment-latest** for accurate sentiment classification.
- Tokenized text, encoded numerical representations, and processed through **Hugging Face Transformers**.
- Classified reviews into **positive, negative, or neutral** categories.



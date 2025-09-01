# 📱Mobile App Sentiment Analysis 2025

## 📌Project Overview
This project performs a comprehensive sentiment analysis on mobile app reviews from 2025, covering popular applications like TikTok, Netflix, and others. The main goal is to extract meaningful insights from user feedback to help developers understand user satisfaction, identify common issues, and prioritize improvements.

## 📊Key features:
  - Sentiment Classification: Categorize user reviews using IBM Watson NLP.
  - Demographic Analysis: Examine sentiment across age groups and gender.
  - Data Visualization: Explore sentiment distributions, top apps, and key trends.
  - Text Analysis: Generate Word Clouds and identify top keywords per sentiment.
  - Actionable Recommendations: Provide insights for app performance and UX enhancements.
    
## 📁 Dataset
The dataset used in this project is the Multilingual Mobile App Review Dataset August 2025 by Pratyush Puri on Kaggle. 
https://www.kaggle.com/datasets/pratyushpuri/multilingual-mobile-app-reviews-dataset-2025
It contains:
  - 2,500+ reviews across 40+ mobile applications
  - Reviews in 24 different languages, including English, Spanish, French, and more
  - Columns: app_name, review_text, gender, age, app_category, rating, sentiment
This diverse dataset is ideal for multilingual sentiment analysis and NLP tasks.

## 🔍 Analysis Process
1. Data Cleaning: Remove duplicates, handle missing values, and standardize text.
2. Sentiment Classification: Apply IBM Watson NLP to classify review sentiments.
3. Exploratory Data Analysis (EDA):
    - Overall sentiment distribution and per app/category.
    - Sentiment analysis by demographic segments.
    - Identify apps with highest positive/negative review counts.
    - Generate Word Clouds and top keywords for each sentiment.
4. Insights Extraction: Detect patterns, trends, and common user complaints.
5. Recommendations: Suggest actionable improvements for app performance and user experience.

## 🚀Insights & Findings
1. Overall Sentiment Distribution
  - Majority of reviews are Positive (47%)
  - Negative reviews (25%) concentrated in apps with performance or UX issues
  - Neutral reviews (28%) are often short or factual
2. Top Apps by Sentiment
  - Positive: Khan Academy, Netflix, VLC, Google Drive and other entertainment apps
  - Negative: Grammarly, Ebay, Microsoft Office and other. Often due to crashes or slow performance
3. Sentiment by App Category
  - Navigation & entertainment apps: High positive review rates
  - Productivity apps: More negative reviews (technical issues, complexity)
4. Sentiment by Demographics
  - Age 18–35: Not too many reviews
  - Age >45: Frequently provide both positive and negative reviews
5. Text Analysis
  - Positive keywords: userfriendly, design, smooth
  - Negative keywords: crashes, improvement, update
  - Neutral keywords: better overall, good, interface

🤖 AI Support Explanation
This project leverages AI at multiple stages:
1. Sentiment Classification
  - IBM Watson automatically classifies each review.
  - Enables scalable, automated sentiment analysis across thousands of reviews.
2. Text Analysis & Keyword Extraction
  - Python NLP libraries (CountVectorizer, WordCloud) extract frequent words and phrases.
  - Highlights common feedback themes for actionable insights.
  - Translate
3. Visualization
  - Matplotlib & Seaborn visualize sentiment distribution, top apps, and word frequency trends.
  - Communicates patterns clearly for decision-making.
Value of AI: Automates processing of multilingual reviews, provides scalable insights, and bridges raw feedback to actionable recommendations.

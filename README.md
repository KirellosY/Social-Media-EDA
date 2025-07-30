# 📊 Social Media Engagement Data Analysis

This project analyzes a dataset of social media posts across Facebook, Instagram, and Twitter (X) using Python. The goal is to understand platform performance, user interactions, and content trends based on likes, comments, shares, post type, and sentiment scores.

## 📁 Dataset

- **Source**: [Kaggle Dataset - divyaraj2006/social-media-engagement](https://www.kaggle.com/datasets/divyaraj2006/social-media-engagement)
- **Size**: 100 posts
- **Features**:
  - `platform`: Facebook, Instagram, Twitter
  - `post_type`: image, poll, carousel, video, text
  - `post_time`: timestamp of the post
  - `likes`, `comments`, `shares`: engagement metrics
  - `post_day`: derived from post time
  - `sentiment_score`: positive, neutral, or negative

## 🔧 Tools and Libraries

- `pandas`, `numpy` – Data loading and preprocessing  
- `matplotlib`, `seaborn`, `plotly.express` – Data visualization  
- `mplcyberpunk` – Cyberpunk-style charts  
- `WordCloud` – Word cloud generation

## 📌 Key Steps

1. **Data Preparation**
   - Downloaded the dataset using `kagglehub`
   - Loaded the `.csv` file and checked for duplicates or missing values
   - Converted post times to datetime and extracted day/month components

2. **Exploratory Data Analysis (EDA)**

   ### One-Column Analyses:
   - **Platform Distribution** (Pie chart)
   - **Post Types** (Bar plot)
   - **Posts by Day, Date, and Hour** (Cyberpunk-style visualizations)
   - **Engagement Distributions**: Histograms of likes, comments, and shares
   - **Sentiment Distribution**: Horizontal bar chart

   ### Multi-Column Analysis:
   - **Interaction Relationships**: Scatter plots between likes, comments, and shares
   - **Platform-wise Engagement**: Bar chart comparing total likes, comments, and shares across platforms

3. **Top Performing Posts**
   - Identified top posts by **likes**, **comments**, **shares**, and **combined engagement**
   - Analyzed:
     - Platforms contributing to top posts (WordCloud + Bar)
     - Post type distribution among top posts (Pie charts)
     - Sentiment scores among top performers
     - Posting month trends for high-performing content


## 📷 Sample Visualizations

- Bar and pie charts for post type and engagement
- Scatter plots showing interaction correlations
- Word clouds for platform frequency in top posts
- Cyberpunk-style line and bar plots showing monthly and daily activity

## 📌 Author
Project created by [Kirellos Youssef] using public Kaggle data

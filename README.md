# 📊 Netflix Movies & TV Shows Analysis (EDA Project)

This project is a detailed exploratory data analysis (EDA) of Netflix’s Movies and TV Shows dataset. The goal is to uncover trends and insights using data visualization.

---

## 📁 Dataset
- **Source:** Netflix Titles Dataset from [Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
- **Columns Used:** title, director, cast, country, rating, duration, genre, date_added, type

---

## 🔍 1. Data Cleaning & Preparation
- Handled missing values in key columns
- Parsed and extracted `year_added` from `date_added`
- Created new columns for `genre` and content types
- Filtered incorrect entries in ratings

---

## 📊 2. Visual Analysis

### 📌 Content Breakdown
- Count & percentage of Movies vs TV Shows
- Year-wise trends in new additions

### 🔢 Ratings & Categories
- Distribution of rating types
- Separate analysis for Movies and TV Shows

### 🎬 Genre & Country Insights
- Top 10 most common genres
- Top countries producing content
- Trend of Indian vs US movies over the years

### 🧑‍🎨 Creators
- Most frequent directors
- Most common cast members

### ⏱️ Duration Analysis
- Movie duration distribution (in minutes)
- TV show season counts

---

## 💡 5. Summary
- Majority of content is **Movies** (~70%)
- Peak in new content additions around **2019-2020**
- U.S dominates Netflix content, but **India** is strong too
- **Documentaries**, **Dramas**, and **Comedies** are most common genres
- Some directors like **Raúl Campos** & **Marcus Raboy** appear frequently
- Movie duration center around **90 minutes**, while most TV shows are **1-2 seasons**

---

## 🛠️ Technologies Used
- Python (Pandas, NumPy)
- Seaborn, Matplotlib
- Google Colab

---

--------------------------------------------------------------THE END------------------------------------------------------------------------

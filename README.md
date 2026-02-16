# 📱 Google Play Store Data Analysis & Sentiment Insights

## 📌 Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) on Google Play Store applications, combined with sentiment analysis of user reviews.

The goal is to uncover:

- 📊 What categories are most popular (by installs)
- ⭐ Which categories receive the highest engagement (reviews)
- 🗺️ How sentiment polarity varies across content ratings
- 🔎 The relationship between content rating, sentiment, and app rating

This project demonstrates practical data cleaning, aggregation, visualization, and analytical reasoning using Python.

---

## 📂 Datasets Used

### 1️⃣ Apps Dataset
Contains app-level metadata:

- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

### 2️⃣ Reviews Dataset
Contains user review sentiment analysis:

- App
- Translated_Review
- Sentiment (Positive / Neutral / Negative)
- Sentiment_Polarity (-1 to 1)
- Sentiment_Subjectivity (0 to 1)

---

## 🧹 Data Cleaning Process

Key transformations performed:

- Removed "+" and "," from `Installs` column and converted to integer
- Converted `Reviews` to numeric
- Handled missing values
- Merged apps dataset with sentiment dataset
- Aggregated installs and reviews by category

---

## 📊 Key Analyses Performed

### 🔹 1. Top 10 Most Popular Categories (by Installs)

- Aggregated total installs by category
- Identified top 10 categories
- Compared total review counts among them

**Insight:**  
High installs do not always correspond to highest engagement (reviews).

---

### 🔹 2. Sentiment Polarity Distribution by Content Rating

- Visualized sentiment polarity using histograms
- Split by content rating categories
- Measured emotional intensity of reviews

**Insight:**  
Apps targeting different audiences generate different emotional response patterns.

---

### 🔹 3. Impact of Content Rating on Sentiment & App Rating

Computed:

- Average Sentiment Polarity
- Average Sentiment Subjectivity
- Average App Rating

**Key Observation:**
- Broader audience apps (e.g., Everyone) show stable sentiment patterns.
- Teen / Mature categories often show more polarized emotional responses.

---

## 📈 Visualizations

- Bar charts for category installs and reviews
- Histograms of sentiment polarity
- Comparative sentiment averages by content rating

All visualizations were built using:

- pandas
- matplotlib

---

## 🛠️ Technologies Used

- Python 3
- pandas
- matplotlib
- Jupyter Notebook

---

## 🎯 Skills Demonstrated

- Data Cleaning & Preprocessing
- Feature Engineering
- Aggregation & Grouping
- Data Merging
- Exploratory Data Analysis (EDA)
- Sentiment Interpretation
- Business Insight Generation
- Data Visualization

---

## 💡 Business Value

This analysis helps:

- Understand which app categories drive engagement
- Detect emotional patterns in user feedback
- Evaluate whether written sentiment aligns with numeric ratings
- Improve marketing & product strategies based on audience targeting

---

## 🚀 Future Improvements

- Perform statistical testing (ANOVA)
- Build interactive dashboard (Power BI / Tableau)
- Apply machine learning to predict app ratings from sentiment
- Create sentiment anomaly detection

---

## 👨‍💻 Author

Ghayth Hajji  
Business Analytics Student | Data Science Enthusiast  
Tunis Business School  

---

## ⭐ If You Found This Project Interesting

Feel free to star the repository and connect with me on LinkedIn!

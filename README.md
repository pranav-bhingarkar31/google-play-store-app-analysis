# google-play-store-app-analysis
EDA and sentiment analysis of Google Play Store apps and user reviews
# 📊 Google Play Store App Review Analysis

## 📌 Overview
This project analyzes Google Play Store app data along with user reviews to understand factors that influence app performance and user sentiment. The analysis focuses on identifying patterns across categories, installs, ratings, and user feedback.

---

## 🎯 Objectives
- Analyze app performance across different categories  
- Understand relationship between installs, ratings, and reviews  
- Evaluate user sentiment (Positive, Negative, Neutral)  
- Identify factors contributing to app success and user dissatisfaction  

---

## 📂 Dataset
The project uses two datasets:

1. **Play Store Data**
   - App
   - Category
   - Rating
   - Reviews
   - Installs
   - Price
   - Type (Free/Paid)

2. **User Reviews Data**
   - App
   - Translated Review
   - Sentiment
   - Sentiment Polarity
   - Sentiment Subjectivity

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 🧹 Data Cleaning
- Handled missing values in key columns  
- Converted `Installs` and `Reviews` to numeric format  
- Removed special characters like `+` and `,`  
- Created grouped features (Install Groups, Review Groups) for better analysis  

---

## 🔗 Data Integration
- Merged app dataset with user reviews dataset using the `App` column  
- Enabled combined analysis of app metrics and user sentiment  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 App-Level Analysis
- Rating distribution  
- Category vs average rating  
- Free vs Paid apps comparison  

### 🔹 Review-Level Analysis
- Sentiment distribution  
- Sentiment vs install groups  
- Sentiment vs review volume  

---

## 💡 Key Insights
- Apps with higher installs show a **slight increase in negative sentiment**, likely due to a larger and more diverse user base  
- Smaller apps tend to have **higher positive sentiment**, possibly due to early adopters and loyal users  
- Certain categories show **higher negative feedback**, indicating potential improvement areas  
- Free vs Paid apps show differences in user expectations and satisfaction levels  

---

## 📈 Visualizations
- Distribution plots  
- Stacked bar charts for sentiment analysis  
- Scatter plots for installs vs ratings  

---

## 🚀 Future Work
- Build a sentiment prediction model using machine learning  
- Develop an interactive dashboard (Streamlit/Power BI)  
- Perform deeper NLP analysis on review text  

---

## 📁 Project Structure

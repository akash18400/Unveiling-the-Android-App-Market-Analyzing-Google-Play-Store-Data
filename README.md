# Unveiling-the-Android-App-Market-Analyzing-Google-Play-Store-Data
# 📱 Play Store App Analysis

This project analyzes Android Play Store app data using Python and provides insights into various aspects like app ratings, installs, pricing, size, and user sentiment.

## 📂 Dataset Used

1. **apps.csv** – Contains metadata about apps (Name, Category, Rating, Size, Installs, Price, etc.)
2. **user_reviews.csv** – Contains user reviews along with sentiment labels and polarity scores.

## 🚀 Features & Analysis

### 🧹 Data Cleaning
- Removed corrupted or missing rows
- Converted values like `Size` from MB/kB, `Installs` from strings to integers
- Cleaned `Price` and `Reviews` for analysis
- Merged sentiment data with app metadata

### 📊 Visualizations
- Bar plots of app counts per category
- Scatter plots: 
  - `Price` vs `Rating`
  - `Size` vs `Installs`
  - `Rating` vs `Sentiment Polarity`
- Interactive Plotly visualizations
- Sentiment analysis tree maps

### 🤖 Sentiment Analysis
- Used `Sentiment` and `Sentiment_Polarity` from user reviews to evaluate public perception of apps
- Mapped average sentiment polarity per app and linked it with ratings

---

## 🧠 Real-Time Use Cases

1. **App Developers & Product Teams**  
   - Understand how app size, price, or category affect installs and ratings.
   - Gauge user sentiment to identify bugs, feature requests, or performance issues.

2. **Digital Marketing Teams**  
   - Pinpoint what types of apps attract better user ratings and engagement.
   - Optimize app listing strategy based on data-driven trends.

3. **Data Science Portfolios**  
   - Showcase EDA (Exploratory Data Analysis) and visualization skills.
   - Present insights with interactive Plotly charts and storytelling.

4. **App Store Optimization (ASO)**  
   - Use category-wise rating trends and install behavior to boost app discoverability.

## 💻 Tech Stack

- Python
- Pandas
- Matplotlib
- Plotly
- CSV

## 🧾 How to Run

1. Clone the repo or download the `.py` file
2. Make sure your working directory has:
   - `apps.csv`
   - `user_reviews.csv`
3. Run the Python file:
   ```bash
   python playstore_analysis.py

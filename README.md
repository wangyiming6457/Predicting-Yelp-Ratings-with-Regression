# Predicting Yelp Ratings with Regression: A Data Science Approach

This project explores how business-related factors influence Yelp ratings using multiple regression techniques. Leveraging real-world data from Yelp's open dataset, I developed a model to predict the Yelp star rating of a restaurant based on features such as location, number of reviews, and business attributes. Project given by: Codecademy

## 📊 Project Motivation

Online reviews significantly influence customer choices, especially in the food and hospitality industry. I wanted to understand:
- What features contribute most to a restaurant's Yelp rating?
- Can we build a model that accurately predicts a restaurant's rating?
- How can insights from the model help businesses improve their online reputation?

## 🗂️ Dataset Description

The analysis uses a subset of Yelp’s dataset:
- `yelp_business.json`: metadata about businesses including location and attributes
- `yelp_review.json`: user reviews and ratings
- `yelp_user.json`: information about reviewers
- `yelp_checkin.json`: user check-in data
- `yelp_tip.json`: short tips from users
- `yelp_photo.json`: business photo metadata

## 🔧 Methods Used

- Data Cleaning & Wrangling (Pandas)
- Feature Engineering
- Multiple Linear Regression (Scikit-learn)
- Exploratory Data Analysis (EDA)
- Data Visualization (Matplotlib, Seaborn)
- Model Evaluation (R² Score, RMSE)

## 📈 Results

- The model achieved an R² score of XX (insert actual score) on the test set.
- Features such as review count, business location, and certain attributes were found to be highly correlated with rating outcomes.
- Some features, like `is_open`, had negligible or inconsistent effects.

## 🧠 Key Takeaways

- Linear regression provides a good baseline, but more complex models (e.g., Random Forests or XGBoost) may yield better performance.
- Feature selection and transformation are crucial for meaningful insights.
- Yelp’s data offers rich opportunities to study consumer behavior.

## 🚀 Getting Started

To run the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

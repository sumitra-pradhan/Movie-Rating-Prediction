# 🎬 Movie Rating Prediction with Python
## 📌 Overview
This project demonstrates a machine learning workflow for predicting IMDb movie ratings based on metadata such as genre, duration, director, and cast. It is built using Python and deployed via a clean Streamlit interface, making it easily accessible for exploration.

## 🧠 Problem Statement
The goal is to predict the movie rating on IMDb using available features from a curated Indian movie dataset. Accurate predictions can support recommender systems, viewer profiling, and content evaluation.

## 🗂 Dataset
Source: IMDb India dataset
Size: ~15,000 movie records
Features:
Name
Year
Duration
Genre
Rating (Target)
Votes
Director, Actor 1, Actor 2, Actor 3

## 🔍 Exploratory Data Analysis
Visualized rating distributions across genres and years
Identified top genres by average ratings
Explored relationships using bar charts, pie charts, histograms, boxplots, and heatmaps
Analyzed genre popularity using count plots

## ⚙️ Data Preprocessing
Dropped missing entries for critical fields
Cleaned string-based numeric columns (e.g., duration and year)
Encoded categorical variables (LabelEncoder for director, actors, genre)
Scaled Votes using log transformation

##🤖 Model Building
Implemented and compared two models:
Linear Regression
Decision Tree Regressor

Evaluation Metrics
Metric	Linear Regression	Decision Tree
MSE	1.78	2.52
MAE	1.05	1.21
R² Score	0.038	-0.36

## 📊 Insights
Linear Regression provided relatively stable performance
Decision Tree overfitted slightly but helped capture non-linear relationships
Ratings showed stronger correlation with Duration, Votes, and encoded Director

## 🔮 Future Enhancements 
Add more features like synopsis (NLP), box office, budget, etc.
Try advanced models (XGBoost, Random Forest)
Improve UI and deploy on platforms like Render or Hugging Face

✅ Conclusion (Short Version)
This project explores IMDb rating prediction for Indian movies using metadata and regression models. It sets a solid foundation with clear preprocessing, modeling.

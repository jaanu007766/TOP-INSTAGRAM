This project analyzes a dataset of top Instagram influencers to understand their growth patterns, engagement behavior, and influence metrics. The dataset includes attributes such as follower count, total likes, average likes, posting behavior, country, and influence score. These features help evaluate both popularity and audience engagement. The data is cleaned and preprocessed to ensure accuracy, followed by exploratory analysis and machine learning modeling to uncover patterns and build predictive systems.

📌 Key Features of the Project

Cleaning and preprocessing of real-world influencer data

Conversion of follower/likes strings (K, M, B) into numerical values

Exploratory Data Analysis with multiple visualizations

Feature engineering (ratios and derived metrics)

Regression models to predict Influence Score

Classification model to categorize Engagement Level

Visualization of model performance through plots and confusion matrix

Insights into influencer trends and global distribution

📁 Dataset Overview

The dataset contains detailed information about top Instagram influencers, including:

Influencer name

Country

Followers

Total likes

Number of posts

Average likes

60-day engagement rate

New post average like

Influence score

These fields represent both visibility (followers) and engagement efficiency (likes, engagement rate). Some fields use shorthand values like “k”, “m”, or “b”, which are cleaned and converted to numeric values for analysis.

🧹 Data Cleaning & Preprocessing

The dataset underwent several preprocessing steps to ensure quality:

Removal of duplicate rows

Filling missing numeric values using median

Filling missing categorical values using mode

Converting strings like “25k”, “3.2m”, “1.5b” into numeric values

Removing “%” from engagement rate and converting to float

Ensuring all feature types are consistent for ML models

These steps produced a clean, reliable dataset ready for analysis and model training.

📊 Exploratory Data Analysis (EDA)

EDA was performed to identify influencer behavior and engagement trends.
Key observations include:

Follower count does not always correlate with high engagement

Some countries dominate the influencer landscape

Influence scores vary widely across the dataset

Ratio features reveal deeper insights into engagement quality

Visualizations include scatter plots, histograms, bar charts, and count plots, helping to better understand influencer performance.

⚙️ Feature Engineering

To improve modeling accuracy, additional new features were created:

Like-to-Follower Ratio

Post-to-Follower Ratio

Average Likes Ratio

These help measure how efficiently influencers engage their audience.

🤖 Machine Learning Models Used
Regression Models (Predicting Influence Score & Engagement Rate)

Random Forest Regressor

Linear Regression

Random Forest performed better, capturing non-linear relationships and delivering lower MSE and higher R² scores.

Classification Model (Engagement Level Prediction)

Influencers were categorized into:

Low

Medium

High

Using a Random Forest Classifier, the model achieved strong accuracy, supported by:

Confusion matrix

Classification report

Actual vs predicted class comparison

📈 Visualizations Included

Followers vs Engagement plot

Influence score distribution

Top countries with most influencers

Feature importance ranking

True vs Predicted influence score

Confusion matrix for engagement classification

Actual vs Predicted engagement class charts

These plots help explain the patterns discovered during analysis.

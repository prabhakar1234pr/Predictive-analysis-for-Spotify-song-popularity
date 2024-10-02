# Predictive-analysis-for-Spotify-song-popularity
Spotify Song Popularity Prediction
Project Overview:
This project aims to predict the popularity of songs on Spotify by analyzing various acoustic and track-related features. The dataset used in this project, spotify_songs.csv, contains attributes such as danceability, energy, and instrumentalness. By employing different statistical and machine learning models, we seek to uncover key factors influencing song popularity and explore how these insights can improve song recommendations and marketing strategies.

Dataset:
The dataset contains the following key features:

Acoustic Features: Acousticness, danceability, energy, instrumentalness, loudness, and more.
Track Details: Track name, artist, duration, release date.
Popularity Metrics: A popularity score based on user interactions.
Metadata: Information like track key, mode, and time signature.
Methods
We utilized the following methods and models to perform our analysis:

1. Exploratory Data Analysis (EDA):
Data Cleaning: Handling missing data, normalizing features, and removing outliers.
Visualization: Histograms, scatter plots, correlation matrix, box plots, and heatmaps to explore relationships between song features and popularity.
Key Insights:
Danceability shows a positive correlation with popularity.
Acousticness has a negative correlation with popularity.
Seasonal trends influence song popularity.
2. Predictive Modeling:
Linear Regression: Predicts song popularity based on acoustic features. Although it provided a baseline, it captured only about 7% of variability in song popularity.
Logistic Regression: Classifies songs as popular or not popular based on features like danceability.
Ridge Regression: Handles multicollinearity between features, reducing model complexity and improving stability.
K-Nearest Neighbors (KNN): Predicts song popularity based on proximity to similar songs, providing an accuracy of about 60%.
Key Findings:
Danceability and energy are positively correlated with popularity, while acousticness and instrumentalness have a slight negative correlation.
Models like Random Forest and KNN performed well in capturing complex patterns in the data.
Logistic Regression provided quick insights but had limited predictive power.
Recommendations:
Algorithm Improvement: Integrating these models into Spotify's recommendation system can improve user satisfaction by better predicting popular songs.
Feature Engineering: Combining key attributes like energy and loudness could enhance predictive power.
Marketing Strategies: Focus on promoting songs with high danceability and energy during peak listening seasons.

Conclusion :
This project demonstrates the application of machine learning models to predict Spotify song popularity. By understanding key features influencing popularity, Spotify can enhance its recommendation algorithms and optimize content curation to meet user preferences.

# Movie Recommender System

## Overview
This project implements a movie recommender system using machine learning techniques. The system recommends movies to users based on their preferences and historical ratings. The dataset used for this project is sourced from TMDB (The Movie Database).

## Project Steps

1. **Data Collection and Preprocessing**:
   - The dataset from TMDB is collected and cleaned.
   - Data preprocessing includes handling missing values, removing duplicates, and ensuring data consistency.

2. **Feature Engineering and Vectorization**:
   - Extract relevant features from the dataset (e.g., movie genres, cast, crew).
   - Use techniques like Bags Of Words to vectorize textual features.

3. **Machine Learning Model**:
   - Train a recommendation model (e.g., collaborative filtering, content-based filtering, or hybrid approaches).
   - Evaluate the model's performance using appropriate metrics (e.g., RMSE, precision, recall).

4. **Recommendation Generation**:
   - Given a user's historical ratings, generate recommendations for movies they might like.
   - Provide the top 5 recommended movies based on similarity to the user's preferences.

5. **Front End with Streamlit**:
   - Create a user-friendly interface using Streamlit.
   - Allow users to input their preferences (e.g., favorite genres, actors).
   - Display recommended movies dynamically.

6. **Model Persistence with Pickle**:
   - Serialize and save the trained model using Python's `pickle` module.
   - Load the model in the Streamlit app for real-time recommendations.

7. **Deployment on Heroku**:
   - Deploy the Streamlit app on Heroku.
   - Users can access the recommender system through a web interface.

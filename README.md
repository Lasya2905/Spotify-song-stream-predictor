# Spotify-song-stream-predictor

## 🤖 Theory
This project is about predicting how many streams a song might get on Spotify using its audio features. We use a dataset that contains information about various songs, including their danceability, energy, tempo, and more. These features are used to train a machine learning model that can predict the number of streams for a song.
The main aim of the project is to build a model that learns from existing song data and helps estimate how popular (in terms of streams) a song could be.

## 🚀 Technologies Used
Python (programming language)

Pandas (for data handling)

NumPy (for numerical operations)

Scikit-learn (for machine learning)

Matplotlib (for graph plotting)

## 📦 What This Project Does
Loads a dataset of Spotify songs with various audio features
Cleans and processes the data
Splits the data into training and testing sets
Scales the feature values using StandardScaler
Trains a Random Forest Regressor model
Predicts the number of streams for test data
Evaluates the model using:
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score (to check model accuracy)
Plots a graph of Actual vs Predicted Streams
Gives a prediction for one random song as a sample result

## 🖥 Steps of the Project
Import all required libraries

Load the dataset (spotify-2023.csv)

Select the useful features and target (streams)

Preprocess and scale the data

Split data into training and test sets

Train the Random Forest model

Make predictions

Evaluate the model using MSE, RMSE, and R²

Plot a graph showing actual vs predicted stream values

Show a sample prediction result for one song

## 🧠 Output & Visuals
Actual vs Predicted Streams graph: shows how close the predictions are to real values

Evaluation Scores:
MSE: Average of squared errors

RMSE: Root of MSE, tells average error size

R² Score: How well the model explains the data (closer to 1 = better)

Sample Prediction:
For a randomly picked song, the model shows the estimated streams and compares it with actual streams

## 🛠 Conclusion
This project shows how machine learning can be used to predict the popularity of a song based on its audio features. It helps in understanding which song traits might lead to more streams and is a great beginner-friendly project for learning about data analysis and regression models.

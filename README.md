# Song Recommendation System
This project involved developing a machine learning-based song recommendation system that can suggest songs to users based on their listening preferences and history. The goal was to create a personalized music recommendation engine that can help users discover new music tailored to their tastes.

The project followed a standard machine-learning workflow:

Data Collection: Song metadata like audio features, genre, artist etc. were extracted from the Spotify API to create a dataset of song attributes.
Data Preprocessing: The raw data was cleaned by handling missing values, removing noise, encoding categorical features etc. Exploratory analysis like correlation plots was done.
Model Training: Supervised machine learning models including KNN, SVM and Neural Networks were trained on the song features to learn patterns and make predictions. An unsupervised K-Means clustering model was also built.
Recommendation: The trained models were used with collaborative filtering techniques to generate song suggestions based on similarity scores between user preferences and song attributes.
Evaluation: Different performance metrics like MAE, RMSE and R-Squared error were used to evaluate and compare the models. KNN gave the best results.
The final recommendation system provides a personalized music experience that adapts as per user listening patterns. It helps discover new music matches and enhances engagement. The project provided hands-on experience with building and deploying a machine learning-powered recommendation engine.

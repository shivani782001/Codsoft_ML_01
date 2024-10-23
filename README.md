# Codsoft_ML_01
TASK 1 ( Movie Genre Prediction)
This repository contains a machine learning project aimed at predicting the genre of a movie based on its plot summary or other textual information. The model is trained using a dataset of movie descriptions, and its goal is to classify movies into one or more genres.

Project Workflow:
 1. Data Preprocessing:
Text data from the DESCRIPTION column is transformed using TF-IDF (Term Frequency-Inverse Document Frequency) to capture the most relevant features for genre prediction.
 2. Model Selection:
A Logistic Regression model is employed for classification due to its effectiveness in handling multi-class classification problems like genre prediction.

 3. Training:
The model is trained on the training dataset, which contains the movie TITLE, GENRE, and DESCRIPTION.

 4. Prediction:
The trained model is used to predict the genres of movies in the test dataset, which contains the movie TITLE and DESCRIPTION (without GENRE in advance).
 
 5. Output:
The predicted genres are saved in a CSV file for evaluation and further analysis.

Technologies Used:

Python: For model building and data preprocessing.
Logistic Regression: For multi-class classification.
TF-IDF: For converting text data into numerical features.

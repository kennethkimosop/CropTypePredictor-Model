# CropTypePredictor-Model
**Crop Selection Based on Soil Metrics Using Machine Learning**
**Overview**
This project aims to assist farmers in selecting the optimal crop for their fields based on essential soil metrics.
By leveraging machine learning techniques, we build a multi-class classification model to predict the best crop to plant given the soil's nitrogen (N), phosphorous (P), potassium (K) content ratios, and pH value.

Dataset
The dataset used in this project, soil_measures.csv, contains the following columns:

N: Nitrogen content ratio in the soil
P: Phosphorous content ratio in the soil
K: Potassium content ratio in the soil
pH: pH value of the soil
crop: Target variable containing various crops
Each row represents the soil metrics for a particular field and the optimal crop for that field.

# **Objective**
The primary objective is to build a classification model that predicts the type of crop best suited for the given soil conditions and identifies the single most important feature for predictive performance.

**Project Structure**
The project is organized as follows:

Data Loading and Preprocessing:

Load the dataset using Pandas.
Encode the target variable (crop) using LabelEncoder.
Model Building and Evaluation:

Split the data into training and testing sets.
Train a Logistic Regression model for each feature.
Evaluate the model using accuracy score.
Identify the feature that provides the best predictive performance.
Results:

Display the best predictive feature and its accuracy score.


Conclusion
The Potassium content ratio (K) in the soil was identified as the most important feature for predicting the optimal crop with an accuracy score of approximately 28.03%. This insight can help farmers prioritize soil metrics when they have budget constraints, ensuring they still make informed decisions about crop selection to maximize yield.

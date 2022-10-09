# machine-learning-challenge
# Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

This project uses the data they gathered to train two machine learning (ML) models that are intended to classify candidate exoplanets.

# Machine learning models used;

This project focused on LinearRegression and Random Forest Classifier to test accuracy of the machine learning algorithm.  

The dataset was preprocessed  before fitting the models. Feature selection was performed to remove unwanted features, this project used MinMaxScaler to scale the numerical data prior to splitting the datasets into training and testing data.

GridSearch was used to tune the model parameters in both algorithms (LR and RFC). A comparison of the models was conducted using two different classifiers.

# Findings and summary

This project tested LinearRegression and Random Forest Classifier to determine the better candidacy for exoplanets dataset. From the screenshot, it is evident that RFC is a better model for predicting exoplanets candidacy, with a tuned model accuracy of 90.39% in comparison to 89.47% of LR model.
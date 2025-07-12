# UNEMPLOYMENTANALYSIS WITH PYTHON

# Author: Saikumar Penke

# Batch: July

# Domain: Data Science

# Aim

The aim of this project is to build unemployment Analysis with Python


# Libraries Used

The following important libraries were used for this project:

numpy

pandas

matplotlib.pyplot

seaborn

sklearn.preprocessing.LabelEncoder

sklearn.preprocessing.MinMaxScaler

sklearn.model_selection.train_test_split

sklearn.linear_model.LogisticRegression

# Model Training

The feature matrix input and target vector target were created using relevant columns from the final dataset df_final.

The data was split into training and testing sets using train_test_split.

The input data was scaled using MinMaxScaler to normalize the values between 0 and 1.

# Model Prediction

A logistic regression model was initialized and trained on the training data using LogisticRegression.

The model was used to predict movie ratings for the test set using model.predict(X_test).

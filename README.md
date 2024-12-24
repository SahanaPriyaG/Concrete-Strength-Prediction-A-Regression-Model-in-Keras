# Concrete Strength Prediction Using Regression Models in Keras #
This project explores the application of neural networks to predict the compressive strength of concrete based on its composition. By experimenting with data preprocessing, training strategies, and neural network architectures, the project demonstrates the impact of these factors on the accuracy of regression models built with Keras.
# Introduction
Predicting the compressive strength of concrete is a crucial task in construction and materials science. This project investigates how changes in preprocessing, training epochs, and model architecture affect the prediction performance of regression models using Keras.

The project is divided into four parts:

1. Building a baseline regression model.
2. Normalizing the input data to improve performance.
3. Increasing training epochs for better accuracy.
4. Adding more hidden layers to explore deeper network architectures.
# Technologies Used
Python
1. Keras: For building and training neural networks.
2. NumPy & Pandas: For data manipulation and analysis.
3. Scikit-learn: For splitting datasets and evaluation metrics.
4. Matplotlib & Seaborn: For visualizing results.

# Dataset
The dataset contains information about the composition of concrete and its corresponding compressive strength. Features include:
Cement, Blast Furnace Slag, Fly Ash, Water, Superplasticizer, Coarse Aggregate, Fine Aggregate.

# Results
1. Baseline Model: Established initial performance with one hidden layer and 50 epochs.
2. Normalized Data: Demonstrated improved prediction consistency by normalizing input features.
3. Extended Training: Increased accuracy by training the model for 100 epochs.
4. Deeper Network: Analyzed the impact of adding more hidden layers on prediction performance.

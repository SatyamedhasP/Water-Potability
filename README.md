# Water Potability

<p align="center">
  <img src="https://github.com/SatyamedhasP/Water-Potability/blob/main/Water_quality_image.jpg" width="50%">
</p>

## Overview
- This project aims to predict the potability of water based on various physical, chemical, and biological factors. 
- The potability of water is an important issue worldwide, and the quality of drinking water is vital for human health. 
- This project involves the development of a machine learning model to classify water samples as potable or non-potable based on various parameters such as pH, hardness, solids, and more.

## Data cleaning, Data visualization and Data Preprocessing
- The dataset used for this project is obtained from Kaggle and contains water quality data for various water sources. 
- The dataset has been preprocessed to handle missing values and outliers. 
- The project includes exploratory data analysis to understand the distribution of the variables and the relationship between the features and the target variable.
- Dataset source: [Kaggle - Water Potability](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- Scaling:
  - A few attributes were in the numerical format but had various ranges.
  - To get them in the same range we used Standard Scaling to scale the data in the desired range.
  - The first step was to import Standard Scaler from the scikit-learn library.
  - We then fit and transform the data by passing in the desired columns of the dataset using Standard Scaler.



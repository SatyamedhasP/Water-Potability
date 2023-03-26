# Water Potability 

<p align="center">
  <img src="https://github.com/SatyamedhasP/Water-Potability/blob/main/Water_quality_image.jpg" width="50%">
</p>

Check your water quality [here](https://satyamedhasp-water-potability-app-imzu8c.streamlit.app/).

Libraries used: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Tensorflow, Keras

Project Notebook link:[Water Quality](https://github.com/SatyamedhasP/Water-Potability/blob/main/Water_Quality(1).ipynb)

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

## Building classifiers
- After data analysis, several machine learning models are developed and compared for their performance in predicting the potability of water. 
- The models include Logistic Regression,Decision trees, Naive Bayes,k-Nearest Neigbors ,Random Forest, and Artificial Neural Nets. 
- The models are evaluated using various metrics such as accuracy, precision, recall, and F1 score

<div style="display:flex;flex-direction:row">
    <img src="https://github.com/SatyamedhasP/Water-Potability/blob/main/Model%20comparison.png" width="50%" />
    <img src="https://github.com/SatyamedhasP/Water-Potability/blob/main/Confusion%20matrix.png" width="40%" />  
</div>

    - The model comparison graph provides the performance of all classifiers based on the scoring metrics.
    - The best performace is provided by the Random Forest algorithm with an accuracy of 70% after hyperparameter tuning and k-fold cross validation.
    - The confusion matrix provides the performance of the Random Forest algorithm on the testing set.
    
## Deployment
- The project also includes a user interface built using Streamlit, allowing users to interact with the model and predict the potability of their water sample by entering the various parameters. 
- Finally, the project is deployed on Streamlit share to make it accessible to a wider audience.
- Try it out [here](https://satyamedhasp-water-potability-app-imzu8c.streamlit.app/)

## Summary
Overall, this project demonstrates the application of machine learning techniques in solving real-world problems and provides a useful tool for individuals and organizations concerned with water quality.
    



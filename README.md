# Mobile_Price_Prediction_Using_MachineLearning #
**Developed this mobile price prediction web application using Streamlit framework. To visit website: http://localhost:8501/**
This application is used to predict the price range for mobile based on different specifications on device.
The price range are divided into 4 categories:
* Low Cost - 0
* Medium Cost - 1
* High Cost - 2
* Very High Cost - 3

mobile_price_prediction.ipynb file contain codes for data analysis and modelling using machine learning.
It contain 2 csv files which are taken from Kaggle:
* Train.csv
* Test.csv

The predicted values of the dataset:
* model.pkl

The prediction.py file contains best model saved as a pickle file for the deployment
* prediction.py

**The python file can be run using command in terminal**
* streamlit run prediction.py

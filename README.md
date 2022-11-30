## About

, links a SQL query to its Query Execution Plan (QEP) and Alternate Query Plans (AQPs), and explains why a certain join/scan algorithm was used in the final query plan. 

SQLink was built as part of the coursework for CZ4032: Database Systems Principles and is built on Python and PostgreSQL, and is optimized for usage on Windows machines. 

In this assignment, we are given a problem of finding a shortest traverse path between two locations within a certain energy budget. This scenario often happens in the transportation where a shorter path is not necessarily more energy efficient (e.g., the road may be very bumpy or has heavy traffic)

## Model
There are 2 python notebooks:

1. CZ4042_EDA contains Exploratory Data Analysis
2. CZ4042 Model contains Data Pre-Processing, Model Exploration, Hyperparameter Tuning, Final Model and Real Time Analysis

Each notebook is seperated into the subsections. 

The data folder cannot be uploaded as it is too large, instead here is the link to the folder: https://drive.google.com/drive/folders/1f18BrqYgUFqrmX8fRVONo3rg6YG7UxMm?usp=sharing

The data folder contains data essential for retraining the model. To retrain the model, run the ‘ Load Data -> Using MFCC + RMS + ZCR -> Data Preprocess’ to load X_train , Y_train and Y_train_new (one-hot encoded)

To run the real-time run all the cells till the last one. Please ensure you update the model checkpoint path when loading the model. Upon reaching the last cell, you can run the cell and test it out. You can refer to our video for the demo.  

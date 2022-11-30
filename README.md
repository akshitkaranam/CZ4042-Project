## About
<img width="377" alt="Screenshot 2022-11-30 at 11 54 12 PM" src="https://user-images.githubusercontent.com/78993046/204846069-d49c8e7f-65ee-449f-90d8-d49903175217.png">

SpeechSense, is a Speech Emotion Recognition (SER) engine that is able to identify emotions in sub-intervals of a speech. We are utilising a hybrid of LSTM with attention and CNN model for the real-time analysis of emotions using datasets: RAVDESS and TESS. 

SpeechSense was built as part of the coursework for CZ4042: Deep Learning and Neural Networks and is trained using Tensorflow. This was built with the help of 2 other team members: Faizan and Pong.



## Model
There are 2 python notebooks:

1. CZ4042_EDA contains Exploratory Data Analysis
2. CZ4042 Model contains Data Pre-Processing, Model Exploration, Hyperparameter Tuning, Final Model and Real Time Analysis

Each notebook is seperated into the subsections. 

The data folder cannot be uploaded as it is too large, instead here is the link to the folder: https://drive.google.com/drive/folders/1f18BrqYgUFqrmX8fRVONo3rg6YG7UxMm?usp=sharing

The data folder contains data essential for retraining the model. To retrain the model, run the ‘ Load Data -> Using MFCC + RMS + ZCR -> Data Preprocess’ to load X_train , Y_train and Y_train_new (one-hot encoded)

To run the real-time run all the cells till the last one. Please ensure you update the model checkpoint path when loading the model. Upon reaching the last cell, you can run the cell and test it out. 

For more information on the project overall you can check our presentation video here: https://www.youtube.com/watch?v=ZIbFgUNf4ZE

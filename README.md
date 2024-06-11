# RTSLD---LSTM-Dense-NN

## Overview
This repository contains the implementation of the RTSLD (Real-Time Sign Language Detection using LSTM and Dense Neural Networks). The goal of this project is to detect and interpret sign language gestures in real-time using a combination of Long Short-Term Memory (LSTM) networks and Dense Neural Networks.

## Feature
- Data Preprocessing: Load and preprocess sign language video data for model training and evaluation.
- LSTM Model: Implement and train an LSTM model for sequential gesture recognition.
- Dense Neural Network: Implement and train a Dense Neural Network for classification tasks.
- Model Evaluation: Evaluate the performance of the models using various metrics.
- Visualization: Plot and visualize the results for better understanding and analysis.

## Installation & Usage
- Clone the Repository
- Install the required packages. (Using pip install ..)
- Collect data for the alphabets manually by providing own dataset individualy for each instance by running "**collectdata.py**".
- Preprocess the fetched image data by running the file named "**function.py**" and then running "**data.py**". This will generate a file with the images in their .npy format for feature extraction.
- Then, train the model "**trainmodel.py**" in your local machine or in Google Collab. Extract the model (_model.json_ & _model.h5_ format file) .
- Finally, Run the "**app.py**" file to detect & recognize the Sign Language actions in real time.

> Note: Use `pip install module_name` to install dependencies ,if any requirement is not fulfilled while running the project in your system.

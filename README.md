# Indoor-Localization-using-Stacked-Denoising-Autoencoder
A deep learning-based system for accurate and noise-resilient indoor localization using SDAE and WiFi fingerprinting.

This repository contains the implementation of an indoor localization system based on Wi-Fi fingerprinting using a Stacked Denoising Autoencoder (SDAE). The system is inspired by the paper:
"WiDeep: WiFi-based Accurate and Robust Indoor Localization System using Deep Learning"
(Yang et al., 2021, IEEE Transactions on Industrial Electronics)

The well-known UJIIndoorLoc dataset is used for training and evaluation.


Indoor localization remains a challenging task due to complex indoor radio propagation environments. This project leverages a deep autoencoder-based approach to learn robust feature representations of WiFi Received Signal Strength Indicator (RSSI) fingerprints for accurate position estimation.

The SDAE network enhances feature extraction by reconstructing corrupted input signals, making the localization model more resistant to noise and signal variability.


## Features
Based on Stacked Denoising Autoencoder (SDAE) architecture.

Uses the UJIIndoorLoc dataset.

Predicts 3D position coordinates: Latitude, Longitude, and Floor.

Incorporates probabilistic localization based on feature reconstruction similarity.

Includes data preprocessing (normalization, noise injection).

Evaluation metrics: Mean Absolute Error (MAE), Root Mean Square Error (RMSE), Floor Accuracy.

## Requirements
Python 3.8+
TensorFlow 2.x / Keras
NumPy
scikit-learn
matplotlib
pandas
for install requirements .... pip install -r requirements.txt
 
 

# Stock Price Prediction using Deep Learning

This project explores the use of deep learning models to predict stock price trends based on historical market data. The goal is to analyze how different neural network architectures perform in capturing patterns in time-series financial data.

## Overview
Financial markets generate large volumes of sequential data. Traditional statistical methods often struggle to capture complex temporal dependencies. In this project, I experiment with deep learning approaches to model stock price movements and compare their performance.
The notebook implements and evaluates three different neural network architectures:
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)
- Long Short-Term Memory Networks (LSTM)
These models are trained on historical stock data to learn patterns and forecast future price trends.

## Key Features
- Data preprocessing and normalization of stock price data
- Time-series sequence generation for model training
- Implementation of **ANN, CNN, and LSTM models**
- Model training and evaluation
- Visualization of predictions vs actual prices

## Technologies Used
- Python
- TensorFlow / Keras
- Pandas
- Matplotlib

## Models Implemented
**ANN (Artificial Neural Network)**  
A baseline model used to learn general patterns from processed stock data.

**CNN (Convolutional Neural Network)**  
Used to capture local patterns and trends within time-series windows.

**LSTM (Long Short-Term Memory Network)**  
Designed for sequential data and capable of learning long-term dependencies in stock price movements.

## Purpose
This project was developed to explore how deep learning models can be applied to financial time-series prediction and to compare how different neural network architectures perform on the same dataset.


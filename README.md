# Project-5
Hybrid Emotion Detection Model
# Overview
This project is a Hybrid Emotion Detection Model created by a team of four as part of a collaborative effort to explore machine learning techniques for emotion detection. The model combines the strengths of Deep Learning and Random Forest algorithms, using a meta model to produce final predictions based on physiological signals.

# Objective
The goal of this project is to accurately classify emotions based on heart rate and Electrodermal Activity (EDA) signals. By combining machine learning models, we aim to improve prediction accuracy and provide a more reliable emotion recognition system.

# Model Architecture
Base Models: A Neural Network (Deep Learning) and a Random Forest model.
Meta Model: Uses stacked predictions from the base models to output a final classification.
Features: Heart rate, EDA signal, and derived features such as heart rate/EDA ratio, difference, sum, and product.
Interface: Designed in Google Colab with an interactive interface allowing input of heart rate and EDA values to predict emotions in real-time.
# Performance
The model achieves an accuracy of 91%, indicating strong performance in emotion detection based on physiological signals.

# Installation
Instructions for setting up the environment, loading models, and running the code are provided in the repository.

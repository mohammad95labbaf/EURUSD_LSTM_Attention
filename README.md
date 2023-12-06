# EURUSD_LSTM_Attention

## Overview

This project is dedicated to predicting 1-hour EURUSD exchange rates using a sophisticated combination of deep learning techniques. The process follows a systematic approach, starting with meticulous data preparation, including formatting and Min-Max scaling to ensure optimal model convergence. The incorporation of technical indicators such as RSI, MA, EMA, and VWAP enriches the model's understanding of market dynamics.

## Model Architecture

The heart of the predictive power lies in the model architecture, which seamlessly integrates LSTM cells, self-attention mechanisms, and 1D convolutional layers. This design is crafted to capture intricate temporal patterns in the EURUSD exchange rates. The implementation is carried out using TensorFlow, providing a customizable and flexible framework.

## Training and Evaluation

The training phase is marked by hyperparameter experimentation and continuous monitoring to ensure the model's effective learning. Evaluation metrics, including Mean Squared Error (MSE) and Mean Absolute Error (MAE), provide valuable insights into the model's performance.

## Deployment and Visualization

Once trained, the model is deployed to predict unseen data. Visualizations play a crucial role in analyzing performance patterns, aiding in the identification of strengths and areas for improvement. The insights gained from these visualizations guide further refinements in the model.

## Goal

Ultimately, this project aims to leverage the power of deep learning to gain nuanced insights into short-term EURUSD fluctuations within the dynamic financial landscape. Whether you're a financial analyst, trader, or enthusiast, this repository provides a comprehensive solution for predicting and understanding the ever-changing landscape of currency exchange rates.

Feel free to explore the code, dive into the details, and contribute to the ongoing refinement of this predictive model. Happy forecasting!

## How to Use

Certainly! Here's a more formal step-by-step guide on how to use the code with your `EURUSD_H1.csv` file in Google Colab:

---

### Project Usage Guide for Google Colab

#### 1. Upload Data to Google Colab

- Open [Google Colab](https://colab.research.google.com/).
- Create a new notebook or open an existing one.
- Use the following code to upload your CSV file:

    ```python
    from google.colab import files

    # Upload your CSV file
    uploaded = files.upload()
    ```

    Click on the "Choose Files" button, select your `EURUSD_H1.csv` file, and wait for the upload to complete.



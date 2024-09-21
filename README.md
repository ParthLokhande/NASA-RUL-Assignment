# NASA-RUL-Assignment
#Predictive Maintenance Using LSTM and GRU on NASA Turbofan Engine Dataset
**Project Overview

This project implements predictive maintenance by predicting the Remaining Useful Life (RUL) of aircraft engines using two types of neural networks: Long Short-Term Memory (LSTM) networks and Gated Recurrent Units (GRU). The NASA CMAPSS Turbofan Engine dataset is utilized to develop and compare the performance of these models.
Objectives

    To implement LSTM and GRU models for RUL prediction.
    To compare the performance of both models using various metrics.
    To visualize the predictions and model performance.

**Features

    Data preprocessing techniques, including normalization and handling of missing data.
    Feature engineering using lag features to capture temporal dependencies.
    Model evaluation using accuracy, precision, recall, and F1-score.
    Visualization of actual vs. predicted RUL and model performance comparisons.

**Dataset

    The project uses the FD001 dataset from the NASA CMAPSS Turbofan Engine dataset.
    Download the dataset from the NASA Open Data Portal.

**Requirements

**Ensure you have the following libraries installed:

pip install numpy pandas matplotlib scikit-learn tensorflow

&&Running the Code

    Clone the Repository:

    bash

    git clone https://github.com/yourusername/predictive-maintenance.git
    cd predictive-maintenance

    Download the Dataset:
        Download the CMAPSSData.zip file from the NASA Open Data Portal and extract it.
        Place the FD001.txt file in the project directory.

    Preprocessing the Data:
        Run the data preprocessing script to clean and prepare the dataset.

    Feature Engineering:
        Execute the feature engineering code  to create lag features.

    Model Building:
        Train the LSTM and GRU models by running train_model.py.

    Model Evaluation:
        Evaluate the models using evaluate_models.py to generate metrics and visualizations.

    Visualizations:
        Visualize the results by running visualizations.py.

**Results

After executing the code, you will obtain:

    Performance metrics for both LSTM and GRU models.
    Visualizations of actual vs. predicted RUL.
    Comparison plots illustrating model performance.

Future Directions

Potential enhancements to this project could include:

    Exploring alternative neural network architectures (e.g., Bidirectional LSTMs).
    Implementing ensemble learning techniques for improved accuracy.
    Conducting further hyperparameter tuning to optimize model performance.

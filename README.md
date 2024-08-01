# Pipeline-automation-using-apache-airflow-for-continuous-machine-learning

# Continuous Machine Learning Pipeline for Fraud Detection

## Project Overview
This project aims to develop a continuous machine learning pipeline for fraud detection, leveraging Apache Airflow for automation and incorporating various sampling techniques to address class imbalance issues. The pipeline ensures models are periodically retrained with new data, adapting to evolving fraud patterns and improving detection performance.

## Features
- **Automated Pipeline**: Uses Apache Airflow to automate the entire machine learning workflow.
- **Continuous Learning**: Periodically retrains models with new data to adapt to changing fraud patterns.
- **Sampling Techniques**: Implements undersampling, SMOTE, and GAN sampling to handle class imbalance.
- **Model Evaluation**: Evaluates the performance of different machine learning models and sampling techniques.

## Technologies Used
- **Apache Airflow**: Pipeline automation and orchestration.
- **Python**: Core programming language.
- **Pandas & NumPy**: Data manipulation and analysis.
- **Scikit-learn**: Machine learning models and evaluation metrics.
- **TensorFlow/Keras**: Building and training the LSTM model.
- **Matplotlib/Seaborn**: Data visualization.

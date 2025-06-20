# Smart Building Cybersecurity System

## Overview

This project implements a machine learning-based cybersecurity system for smart buildings, focusing on detecting and classifying potential attacks. The system leverages various machine learning models and techniques to provide robust protection against a range of threats.

## Dataset

This project utilizes the ToN-IoT dataset, a comprehensive dataset for evaluating IoT security solutions. It can be found at: https://research.unsw.edu.au/projects/toniot-datasets

## Data

The system utilizes a dataset containing data from various IoT devices within a smart building environment. The dataset includes features related to temperature, light status, door state, and other sensor readings.

## Methodology

The project follows a multi-stage methodology:

1.  **Data Preprocessing:** Combining data from multiple CSV files, handling missing values, and dropping irrelevant features (date, time, timestamp).
2.  **Feature Engineering:** Encoding categorical variables and scaling numerical features.
3.  **Model Training:** Training and evaluating multiple machine learning models for binary classification (normal vs. attack) and multiclass classification (identifying specific attack types).
4.  **Imbalance Handling:** Addressing class imbalance using techniques like balanced class weights and SMOTE.
5.  **Performance Evaluation:** Assessing model performance using metrics such as accuracy, AUC, precision, recall, and F1-score.

## Results

The project achieved the following key results:

*   **Binary Classification:** The best performing model for binary classification is [Model Name] with an accuracy of [Accuracy] and an AUC of [AUC].
*   **Multiclass Classification:** The best performing model for multiclass classification is [Model Name] with an accuracy of [Accuracy].
*   **Attack Type Detection:** Individual detectors were trained for specific attack types, with varying levels of performance.

## System Architecture

The recommended production architecture consists of:

1.  **Primary Binary Attack Detector:** A highly accurate binary classifier to detect the presence of attacks.
2.  **Secondary Attack Type Identifiers:** Specialized detectors for specific attack types, providing more granular insights.
3.  **Monitoring Dashboard:** A comprehensive dashboard to visualize key security metrics and monitor system performance.

## Deployment

The system can be deployed as a real-time monitoring solution for smart buildings. The deployment process involves:

1.  Integrating the trained models into a production environment.
2.  Setting up data pipelines to ingest data from IoT devices.
3.  Configuring alerts and notifications based on detected attacks.
4.  Regularly retraining the models to maintain performance.

## Future Work

Potential areas for future work include:

*   Exploring more advanced feature engineering techniques.
*   Investigating the use of deep learning models.
*   Implementing anomaly detection algorithms.
*   Developing a more sophisticated monitoring dashboard.

## Contact

For any questions or inquiries, please contact abyasham at abyasham@gmail.com.

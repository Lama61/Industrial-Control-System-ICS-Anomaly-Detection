# Industrial Control System (ICS) Anomaly Detection

## Project Overview

This project is a machine learning-based anomaly detection system for CAN-based Industrial Control Systems (ICS). The main goal is to detect unusual network traffic and identify different types of cyberattacks.

The project uses the ICS-Flow dataset, which contains normal and malicious network traffic. Different machine learning models were tested and compared to see how well they can detect anomalies and attacks.

## Objectives

* Build an anomaly detection system for CAN-based ICS networks.
* Detect different types of cyberattacks in network traffic.
* Prepare and preprocess the dataset for machine learning.
* Train and test different machine learning models.
* Compare the performance of the models using different evaluation metrics.

## Dataset

The project uses the ICS-Flow dataset, which contains network traffic data from Industrial Control System environments.

The dataset includes normal traffic as well as different attack types, such as:

* Denial of Service (DoS)
* Spoofing
* Fuzzy attacks
* Replay attacks
* Data injection attacks

## Tools and Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn
* Matplotlib
* Seaborn

## Methodology

The project was completed through several main steps:

1. Loading the dataset
2. Cleaning and preprocessing the data
3. Preparing the features
4. Splitting the data into training and testing sets
5. Training the machine learning models
6. Evaluating the models
7. Comparing the results

## Machine Learning Models

Three machine learning algorithms were used in the project:

* Random Forest
* Isolation Forest
* Support Vector Machine (SVM)

Both supervised and unsupervised approaches were explored for detecting anomalous CAN traffic.

## Evaluation

The models were evaluated using different metrics and visualizations, including:

* Accuracy
* Confusion Matrix
* Classification Report
* Model comparison

The models were tested in both multi-class and binary classification modes.

## Project Files

* `Dataset` — Contains the dataset used in the project.
* `Code` — Contains the Google Colab notebook with the Python code.
* `Report` — Contains the full graduation project report.

## Academic Project

This project was completed as a graduation project for the Bachelor of Computer Information Systems at King Khalid University during the academic year 2024–2025.

## My Contribution

My work on the project included data preprocessing, machine learning implementation, model evaluation, analysis of the results, and project documentation.

## Report

The full project report is included in this repository. It provides more details about the project background, methodology, system design, implementation, testing, and results.


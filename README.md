
# Intrusion Detection System (IDS) Using Hybrid Machine Learning

This repository contains the implementation of a hybrid **Intrusion Detection System (IDS)** using three machine learning models: **Multilayer Perceptron (MLP)**, **Random Forest**, and **XGBoost**. The system is designed to detect and classify network intrusions efficiently.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Datasets](#datasets)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Introduction
Intrusion Detection Systems are essential for maintaining the security and integrity of computer networks. This project employs a hybrid approach, leveraging the strengths of different machine learning algorithms to achieve high detection accuracy and performance.

## Features
- **Hybrid Model**: Combines MLP, Random Forest, and XGBoost for robust detection.
- **Scalability**: Optimized for large datasets and real-time applications.
- **Extensibility**: Easily adaptable to incorporate additional machine learning models.
- **Performance Metrics**: Includes accuracy, precision, recall, F1-score.

## Datasets
The project uses the **CICIDS-2017 dataset**, a comprehensive dataset for intrusion detection that contains labeled traffic data. You can download it from [here](https://www.unb.ca/cic/datasets/ids-2017.html).

### Dataset Features:
- Real-world network traffic data.
- Multiple attack types, including DDoS, Brute Force, Infiltration, and more.
- Detailed feature set for advanced analytics.


## Project Structure
```
intrusion-detection-system/
├── data/
│   ├── raw/                # Contains raw CICIDS-2017 dataset files
│   └── processed/          # Contains processed dataset files
├── models/                 # Stores trained models
├── scripts/                # Contains code scripts
│   ├── preprocess.py       # Preprocessing script
│   ├── train.py            # Training script
│   ├── evaluate.py         # Evaluation script
├── notebooks/              # Jupyter notebooks for experimentation
├── requirements.txt        # Required Python dependencies
└── README.md               # Project documentation
```


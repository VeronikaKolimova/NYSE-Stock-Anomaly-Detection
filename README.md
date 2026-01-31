# NYSE Stock Anomaly Detection

Machine learning project for detecting anomalous companies in the NYSE dataset using an ensemble of anomaly detection algorithms.

## Quick Start

To explore the full analysis interactively, open the notebook in your browser:

[![Open in NBViewer](https://img.shields.io/badge/Open%20in-NBViewer-orange?logo=jupyter&logoColor=orange)](https://nbviewer.org/github/VeronikaKolimova/NYSE-Stock-Anomaly-Detection/blob/main/Lab_01.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/)

## 📊 Project Overview

This project applies machine learning techniques to detect anomalous companies...

##  Project Overview
This project applies machine learning techniques to detect anomalous companies in the NYSE dataset based on their financial ratios. Using an ensemble of four anomaly detection algorithms, we identify companies with unusual financial behavior that may require further investigation.

##  Key Features
- **Data Preprocessing**: Cleaning and normalization of financial ratios (P/E, PEG, Debt metrics)
- **Ensemble Anomaly Detection**: Combining Isolation Forest, Elliptic Envelope, One-Class SVM, and Local Outlier Factor
- **Visualization**: Clear plotting of anomalies in 2D feature space
- **Financial Context**: Real-world application to NYSE company data

##  Methods Used
- **Data Cleaning**: Custom cleaning function for financial ratios
- **Anomaly Detection Algorithms**:
  - Isolation Forest
  - Elliptic Envelope (Minimum Covariance Determinant)
  - One-Class SVM
  - Local Outlier Factor (LOF)
- **Ensemble Voting**: Companies flagged by ≥3 methods considered anomalies
- **Visualization**: Matplotlib with custom color coding

##  Results
Identified anomalous companies at 5% and 10% contamination levels across:
- **Debt Metrics** (Debt to Equity, Debt to Assets)
- **Valuation Metrics** (P/E Ratio, PEG Ratio)

##  Technologies
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

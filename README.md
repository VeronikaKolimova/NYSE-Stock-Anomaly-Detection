# NYSE-Stock-Anomaly-Detection
NYSE Stock Anomaly Detection / Обнаружение аномалий в акциях NYSE

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

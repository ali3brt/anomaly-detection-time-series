# Anomaly Detection and Predictive Modeling for Multivariate Time Series Data

This repository contains the implementation of advanced anomaly detection and predictive modeling techniques using multivariate time series data. The project includes data preprocessing, exploratory data analysis (EDA), and the application of machine learning and deep learning models like Isolation Forest, LSTM, and Gradient Boosting Classifier.

## Features
- **Data Preprocessing**: Includes handling missing values, normalization, and memory optimization for large datasets.
- **Exploratory Data Analysis (EDA)**: Comprehensive analysis of dataset features and relationships, including visualizations.
- **Anomaly Detection**: Uses Isolation Forest to detect anomalies in time series data.
- **Predictive Modeling**: Employs LSTM neural networks and Gradient Boosting Classifier for accurate predictions.
- **Real-Time Simulation**: Demonstrates real-time anomaly detection using sliding windows.
- **Scalable Codebase**: Structured for experimentation and scalability.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ali3brt/Anomaly-Detection-TimeSeries.git
Navigate to the project directory:

bash
Copy code
cd Anomaly-Detection-TimeSeries
Install the required Python libraries:

bash
Copy code
pip install -r requirements.txt
Usage
1. Data Preprocessing
Prepare the dataset by running:

bash
Copy code
python src/preprocessing.py
This script handles missing values, normalization, and dataset splitting.

2. Anomaly Detection
Perform anomaly detection using Isolation Forest:

bash
Copy code
python src/anomaly_detection.py
3. Predictive Modeling
Train and evaluate the LSTM model for predictive tasks:

bash
Copy code
python src/lstm_model.py
4. Real-Time Simulation
Simulate real-time anomaly detection using sliding windows:




Dependencies
Python 3.8+
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow
zipfile
Install all dependencies using:

bash
Copy code
pip install -r requirements.txt
Results
Anomaly Detection: Isolation Forest achieved high precision and recall on detecting anomalies in test data.
Predictive Modeling: LSTM neural networks demonstrated robust performance with validation accuracy of over 94%.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Contributions are welcome! Please fork the repository, make changes, and submit a pull request.

Contact
For questions or suggestions, please contact:
Ali Barati Brojeni
Email: [ali.barati93@gmail.com]



Let me know if you’d like to customize any specific sections further!

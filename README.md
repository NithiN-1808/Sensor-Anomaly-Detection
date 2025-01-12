# Sensor-Anomaly-Detection


Anomaly detection is a crucial task in identifying rare events in time series data. This repository provides a collection of methods to detect anomalies using various machine learning models like LSTM Autoencoders, DBSCAN, One-Class SVM, and Isolation Forest.

## **Project Overview**
This project implements anomaly detection on time series data using multiple models and compares their performances. It leverages machine learning techniques such as:
- LSTM Autoencoders for reconstruction-based anomaly detection.
- DBSCAN for density-based anomaly detection.
- One-Class SVM and Isolation Forest for outlier detection.

The notebook trains and evaluates these models on the time series dataset, calculates anomaly scores, and visualizes the performance of each model.

## **Installation and Setup**

1. **Clone the repository**
   To get started, clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name

    Install dependencies Create a virtual environment and install the necessary dependencies using pip:

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt

Dataset Setup

    Download the necessary datasets (e.g., from Kaggle).
    Place the datasets in the data/ folder or the appropriate directory:
        train_FD001.txt
        test_FD001.txt
        RUL_FD001.txt

Environment Variables (Optional) If your project requires any environment variables, specify them here:

    export DATA_PATH="/path/to/dataset"

Usage

    Running the Jupyter Notebook The primary code for anomaly detection is in the src/anomaly_detection.ipynb file. Open the notebook in Jupyter and run through the cells:

    jupyter notebook src/anomaly_detection.ipynb

    This will:
        Load the training and test data,
        Preprocess the data,
        Train multiple anomaly detection models (LSTM Autoencoders, DBSCAN, One-Class SVM, and Isolation Forest),
        Evaluate their performance, and
        Visualize the results.

    Results The notebook will generate:
        Anomaly detection results using different models.
        Performance metrics such as Precision, Recall, F1-Score, and ROC-AUC for each model.
        Visualizations comparing the reconstruction errors and anomalies detected by each model.

Project Structure

Sensor-Anomaly-Detection/
│
├── data/                    # Dataset files (train, test, RUL data)
│   ├── train_FD001.txt
│   ├── test_FD001.txt
│   └── RUL_FD001.txt
│
├── src/                     # Source code
│   └── anomaly_detection.ipynb
│
├── requirements.txt         # Python dependencies
├── README.md                # Project overview and instructions
└── LICENSE                  # Project license

Dependencies

The project requires the following Python packages:

    numpy
    pandas
    matplotlib
    scikit-learn
    tensorflow
    jupyter

You can install all dependencies by running:

pip install -r requirements.txt

Contributing

If you'd like to contribute to this project:

    Fork the repository.
    Create a new branch for your changes (git checkout -b feature-branch).
    Make your changes and commit them.
    Push your changes (git push origin feature-branch).
    Open a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.






   

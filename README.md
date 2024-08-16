# Network Anomaly Detection Using Hybrid Machine Learning Models in SDN Environments

## Project Overview

This project aims to enhance network security in Software-Defined Networking (SDN) environments by developing a Network Anomaly Detection System using hybrid machine learning models. By leveraging the centralized control and programmability of SDN, the project addresses the challenges posed by dynamic cyber threats.

### Problem Statement

Traditional network architectures struggle with detecting modern cyber threats. SDN provides a promising solution, but effective anomaly detection requires advanced analytical approaches. This project develops and compares machine learning models to detect network anomalies in SDN environments.

### Dataset

- Generated using the Mininet emulator, simulating 10 network topologies connected to a single Ryu controller.
- Includes 23 features, capturing both benign traffic (TCP, UDP, ICMP) and malicious traffic (TCP SYN flood, UDP flood, ICMP attack).
- Dataset consists of 1,04,345 entries collected over 250 minutes of network simulation.

### Models Used

- Logistic Regression
- Support Vector Classifier
- Random Forest Classifier
- XGBoost Classifier

## Project Workflow

1. **Data Preprocessing**: Feature engineering and dataset preparation.
2. **Model Development**: Training and evaluating the performance of four machine learning models.
3. **Comparison and Analysis**: Identifying the most effective model for real-time threat detection in SDN environments.

## Usage Instructions

- The project is documented in Jupyter notebooks, detailing data preprocessing, model development, and evaluation.
- Please refer to the provided notebooks for specific instructions.

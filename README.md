# Time Series Anomaly Detection and State Management for NCSU BTEC

## Overview
This repository houses a sophisticated Python-based analytical tool designed for the water treatment facility at North Carolina State University's Biomanufacturing Training and Education Center (BTEC). Using an LSTM (Long Short-Term Memory) neural network, the system monitors, detects anomalies, and manages states in time series data to ensure optimal operational performance and reliability.

## Features

### Secure Token Retrieval for GraphQL Authentication
Ensures secure access to operational data by handling authentication and token retrieval through a GraphQL endpoint, providing robust security measures for data interactions.

### Enhanced GraphQL Request Handling
Efficiently manages GraphQL requests, including handling token expiration and re-authentication, to maintain seamless data fetching operations.

### Data Preprocessing
Processes and normalizes incoming data to ensure compatibility with the LSTM model, preparing it for effective anomaly detection and analysis.

### Anomaly Detection with LSTM
Employs an LSTM model to analyze time series data and identify unusual patterns or anomalies, signaling potential operational issues that require attention.

### Dynamic Thresholding for Anomaly Detection
Implements dynamic thresholding techniques to accurately identify deviations based on historical data trends, enhancing the system’s sensitivity to operational anomalies.

### State Management
Automatically adjusts the operational states between "normal" and "high usage" based on detected anomalies, facilitating proactive management of system resources.

### Visualization of Data and Anomalies
Provides graphical representations of time series data, detected anomalies, and state changes, making the data intuitive and actionable for users.

### Automatic Email Notifications
Configured to send automated email alerts upon detection of significant anomalies or state changes, ensuring timely communication and response.

### Scheduled Monitoring
Supports the scheduling of monitoring tasks, allowing the system to perform regular checks and updates autonomously, enhancing the system’s reliability and performance.

## Usage
To employ this system:
1. Authenticate and retrieve data from the specified GraphQL endpoint.
2. Conduct necessary data preprocessing to ensure LSTM model compatibility.
3. Train the LSTM autoencoder with an appropriate subset of the data.
4. Deploy the model on new or ongoing data streams to detect anomalies.
5. Implement state management protocols based on detected anomalies.
6. Visualize results using matplotlib for clear, actionable insights.

## Technology Stack
- **Python**: Main programming language.
- **TensorFlow/Keras**: Frameworks for modeling and training the LSTM.
- **Pandas**: For efficient data manipulation.
- **Matplotlib**: For data visualization.
- **Requests**: For data fetching from the GraphQL API.

## Acknowledgments
- NCSU BTEC Department
- All project contributors and maintainers

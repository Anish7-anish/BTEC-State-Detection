# Time Series Anomaly Detection and State Management for NCSU BTEC

## Overview
This repository is dedicated to a Python-based analytical system developed for the water treatment facility at the North Carolina State University's Biomanufacturing Training and Education Center (BTEC). The system monitors time series data to detect anomalies and manage system states, ensuring optimal operational performance.

The core of the system is an LSTM (Long Short-Term Memory) neural network, which is employed to identify unusual operational patterns in real-time or historical data, signaling potential anomalies that may warrant further attention or immediate action.

## Features
- **Data Fetching**: Authenticate and retrieve time series data from a GraphQL endpoint securely.
- **Data Preprocessing**: Process and normalize data to prepare for LSTM model input.
- **Anomaly Detection**: Utilize an LSTM autoencoder to detect significant operational deviations, marking them as anomalies.
- **State Management**: Dynamically adjust operational states between "normal" and "high usage" based on anomaly detection and analysis.
- **Visualization**: Graphically represent time series data, anomalies, and state transitions for intuitive analysis and decision-making support.

## Usage
To employ this system:
1. Authenticate with the specified endpoint to fetch the required dataset.
2. Conduct necessary data preprocessing for LSTM model compatibility.
3. Train the LSTM autoencoder using a designated portion of the data.
4. Implement the model on new or ongoing data streams for anomaly detection.
5. Apply state management protocols to react to identified anomalies.
6. Visualize the results using matplotlib for clear and actionable insights.

Detailed setup, configuration, and operational instructions are available in the included documentation files.

## Technology Stack
- **Python**: The primary programming language used.
- **TensorFlow/Keras**: For building and training the LSTM model.
- **Pandas**: To handle data manipulation tasks.
- **Matplotlib**: For visualizing the data.
- **Requests**: To fetch data from the GraphQL API.


## Acknowledgments
- North Carolina State University BTEC Department
- Project contributors and maintainers

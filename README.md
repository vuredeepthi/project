This project focuses on Human Activity Recognition (HAR) using Long Short-Term Memory (LSTM) neural networks, a powerful type of recurrent neural network (RNN) designed for sequential data analysis. HAR is the process of identifying physical activities performed by individuals, such as walking, sitting, standing, or lying down, based on data collected from wearable motion sensors like accelerometers and gyroscopes.

In this project, time-series data from such sensors is processed and fed into an LSTM model. The model learns patterns and temporal dependencies in the data to accurately classify each activity. The dataset used (likely the UCI HAR dataset) contains multiple samples of labeled activities recorded from smartphones carried by users.

The notebook includes:

Data loading and preprocessing

One-hot encoding of activity labels

Construction of a deep LSTM-based neural network using TensorFlow/Keras

Model training, evaluation, and accuracy analysis

Visualization of performance metrics (e.g., training vs. validation accuracy and loss)

This approach demonstrates how deep learning can be applied to real-world problems involving sensor data and time-series classification. The final model can be used in mobile health monitoring, fitness tracking, smart environments, and interactive systems.

# Traffic Flow Prediction

# Traffic Sensor Classification using Deep Learning Models

This repository contains code examples for training and evaluating deep learning models on traffic sensor data. These models include LSTM, RNN, ResNet, GRU, and DRCNN.

## Models

1. Long Short-Term Memory (LSTM): A type of recurrent neural network (RNN) designed to learn long-term dependencies in sequential data.
2. Recurrent Neural Network (RNN): A type of neural network designed to process sequential data by maintaining an internal state that can capture information about previous time steps.
3. Residual Network (ResNet): A deep convolutional neural network architecture that uses residual connections (or skip connections) to address the vanishing gradient problem in deep networks.
4. Gated Recurrent Unit (GRU): A type of recurrent neural network that simplifies the LSTM architecture, combining the forget and input gates into a single "update gate."
5. Dilated Residual Convolutional Neural Network (DRCNN): A variant of the convolutional neural network architecture that uses dilated convolutions and residual connections to learn hierarchical representations of input data.

## Requirements

- Python 3.6 or higher
- TensorFlow 2.0 or higher
- Keras 2.3.1 or higher
- NumPy
- Scikit-learn

## Dataset

- Metr-La dataset can be downloaded from https://zenodo.org/record/5146275#.ZFhjwKDMK38 
- Download the sensor location(graph_sensor_location.csv) dataset from https://github.com/liyaguang/DCRNN/tree/master/data

## Usage


1. Prepare your traffic sensor data in a suitable format, such as CSV or NumPy arrays. Make sure to normalize and preprocess the data as needed.
2. There is a seperate jupyter notebook for each model
3. Choose the appropriate model architecture (LSTM, RNN, ResNet, GRU, or DRCNN) and run the file
4. Fine-tune the model if needed, and once satisfied with the performance, use it to make predictions on new, unseen data.



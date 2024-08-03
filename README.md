# Arrythmia-Detection-using-ECG-signals
This project focuses on detecting arrhythmias from ECG signals using a Convolutional Neural Network (CNN). The model is trained on preprocessed ECG data and evaluated to classify different types of arrhythmias.

<br/>

Introduction

Electrocardiogram (ECG) signals are essential for diagnosing heart conditions, including arrhythmias. This project uses deep learning to automatically classify different types of arrhythmias from ECG signals.

<br/>

Dataset

The dataset used in this project contains ECG signals that have been labeled with different types of arrhythmias. The data is split into training and testing sets to evaluate the model's performance.

<br/>

Preprocessing

The preprocessing steps include:

Resampling ECG signals to a consistent length.
Normalizing the data.
Converting labels to one-hot encoded vectors.

<br/>

Model Architecture

The model is a Convolutional Neural Network (CNN) designed to capture features from the ECG signals:

Input Layer: 1D convolutional layer for processing ECG signals.

Convolutional Layers: Three 1D convolutional layers with ReLU activation.

Pooling Layers: Average pooling layers to reduce dimensionality.

Flatten Layer: Flattens the output from the convolutional layers.

Dropout Layer: Dropout for regularization.

Dense Layers: Fully connected layers leading to a softmax output.

<br/>

Training

The model is trained using the Adam optimizer and categorical crossentropy loss function. The training is conducted over multiple epochs, and the performance is monitored using accuracy metrics.

<br/>

Results

The results section reports the accuracy and other metrics achieved by the model. Additionally, visualizations such as confusion matrices or ROC curves can be included here.

# CNN-for-MITBIH-
This repository contains the implementation of a Convolutional Neural Network (CNN) model for classifying ECG signals using the MIT-BIH Arrhythmia Dataset. The project is designed to identify arrhythmia types from pre-processed ECG signals and demonstrate the effectiveness of deep learning in cardiovascular signal analysis.
Features
Pre-Processing:
Normalization of features using StandardScaler.
Reshaping input for compatibility with Conv1D layers.
Conversion of labels into categorical format for multi-class classification.
Deep Learning Model:
Two Conv1D layers for feature extraction.
MaxPooling1D and Dropout layers for dimensionality reduction and overfitting prevention.
Dense layers for classification into multiple ECG classes.
Visualization:
Training and validation accuracy/loss plots.
Confusion matrix for performance evaluation.
Example ECG signal plot.
1. Clone the Repository
   git clone https://github.com/Akash-mojo/cnn-mitbih.git cd cnn-mitbih

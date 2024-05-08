# Audio Classification Project Report
## Overview:
This project aims to classify audio files into distinct categories using machine learning techniques, specifically focusing on Mel-Frequency Cepstral Coefficients (MFCC) as features.
## Audio Data Loading and Preprocessing:
Audio data is loaded using the librosa library, 
The audio files are preprocessed to ensure uniformity in features extraction.
Mel-Frequency Cepstral Coefficients (MFCC) are extracted from each audio sample.
MFCC summarises the frequency distribution across a window size, enabling analysis of  characteristics of the sound
### Model Training:
A Sequential model is created using TensorFlow Keras for training the classification model.

### Testing New Audio Data:
The trained model is used to predict classes for the new audio samples.


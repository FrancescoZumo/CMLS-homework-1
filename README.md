# CMLS-homework-1
# Assignement 2

Our assignment consisted in implementing a classifier able to pre-dict which digit is pronounced in a short audio excerpt. All the `wav` files were sampled at Fs = 8kHz and they were trimmed so that they have minimal silence at the beginnings and ends. Our task was to extract a set of features from each input signal, cluster them in the feature space in different classes and built a confusion matrix to analyze the performance of our model.


## Input data
- 6 speakers
- 3000 recordings (50 of each digit per speaker)
- English pronunciations

Files are named in the following format: {digitLabel}_{speakerName}_{index}.wav 
Example: `4_nicholas_26.wav`

## Features 
- Mel Frequency Cepstrum Coefficients (MFCC)

## Classification methods
- Gaussian Mixture Model (GMM)
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)

### Implementation 
The final code is `spoken_digit_classification_svm.ipynb`

### Info
More infomation about the implementation are inside the report



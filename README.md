# Accent Classification: American vs. British vs. Indian vs. Australian

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.6%2B-orange)
![Librosa](https://img.shields.io/badge/Librosa-0.9%2B-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A deep learning model to classify English speech samples into four regional accents (American, British, Indian, Australian) using MFCC features and a hybrid CNN-LSTM architecture.

## **Project Overview**
- **Objective**: Classify short speech clips (3-5 seconds) into one of four English accents.
- **Challenge**: Overlapping phonetic features between similar accents (e.g., British vs. Australian).
- **Solution**: A hybrid CNN-LSTM model that captures both spectral (MFCC) and temporal (LSTM) patterns.

## **Key Features**
- **Dataset**: Mozilla CommonVoice (12,000 labeled samples).
- **Preprocessing**: Audio resampling, silence trimming, MFCC feature extraction.
- **Model**: 1D CNN + LSTM hybrid for spectral-temporal learning.
- **Performance**: 35% accuracy (4-way classification), 85.4% F1-score for American English.

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/accent-classification.git
   cd accent-classification

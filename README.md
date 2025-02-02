## Age-Prediction-Based-on-Human-Voice

# Project Overview

This project utilizes machine learning to estimate a person's age based on their voice. The dataset used for training and evaluation is the Common Voice dataset. Various audio features are extracted using Librosa to facilitate learning and improve prediction accuracy.

# Dataset

The dataset consists of audio recordings of human voices along with their corresponding age labels. Feature extraction techniques are applied to convert raw audio signals into meaningful numerical representations for model training.

Dataset link "https://www.kaggle.com/datasets/mozillaorg/common-voice?select=README.txt"

# Project Files

Age Prediction Based on Voice.ipynb - Jupyter Notebook that includes converting MP3 files to WAV files, dataset analysis, feature extraction, model training, and evaluation.

# Dependencies

To run this project, install the following dependencies:

pip install numpy pandas librosa scikit-learn matplotlib seaborn tensorflow keras

# Steps to Run

Preprocess Audio Data

Convert MP3 files to WAV using converter.ipynb.

Extract features from WAV files using Librosa.

Train the Model

Load extracted features and corresponding labels.

Train machine learning models such as Random Forest, XGBoost, or Neural Networks.

Evaluate the Model

Use appropriate metrics (e.g., MAE, RMSE) to assess model performance.

Visualize feature importance and model predictions.

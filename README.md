# Emotion-Signal-Classification

This project involves training a machine learning model to classify emotions based on features extracted from an input dataset.

### Key Aspects:

## Dataset:
The dataset (emotions.csv) contains numerical features (fft_0_b to fft_749_b) and corresponding emotion labels (NEGATIVE, NEUTRAL, POSITIVE).
Data Processing: The dataset is loaded using Pandas, and key exploratory data analysis (EDA) techniques such as visualization and label distribution checks are performed.

## Modeling:
Data is split into training and testing sets.
A TensorFlow-based deep learning model is used for classification.

## Evaluation:
The trained model is evaluated using performance metrics like the classification report.
Visualizations such as line plots are used for feature analysis.

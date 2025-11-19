This project focuses on image classification of fruits using a combination of handcrafted image features and machine learning.
The goal is to classify different fruit types by extracting:

1. Hu moments (shape descriptors)
2. Average color features (RGB)
3. Texture features (grayscale variance)

These features are used to train a Random Forest model for multi-class classification.
The project uses the Fruits 360 dataset, available on Kaggle: https://www.kaggle.com/datasets/moltean/fruits/data


The workflow includes:
1. Loading and visualizing example images
2. Extracting shape, color, and texture features
3. Building and training a Random Forest classifier
4. Evaluating model performance with accuracy, classification report, and confusion matrix

# melanoma_detection
# Skin Cancer Detection using Convolutional Neural Networks (CNN)

## Overview
This project involves the development of a CNN model to accurately detect melanoma, a deadly form of skin cancer, from dermoscopic images. Utilizing TensorFlow, this model is trained on a dataset sourced from the International Skin Imaging Collaboration (ISIC) to classify skin lesions into various categories, including melanoma.

## Objective
The primary goal is to automate the detection of melanoma in its early stages, potentially reducing the manual effort needed for diagnosis by dermatologists and aiding in timely treatment.

## Dataset
The dataset contains 2357 images of benign and malignant skin diseases, categorized into 9 different classes. Melanomas and nevi have a slightly dominant representation in the dataset.

## Model Architecture
The CNN model is built from scratch, consisting of convolutional layers, max-pooling layers, and dense layers. It employs data augmentation strategies to combat overfitting and improve generalization.

## Methodology
1. Data Preprocessing: Resizing images to 180x180 and normalizing pixel values.
2. Data Augmentation: Applying transformations to artificially increase the diversity of the dataset.
3. Model Training: Employing a custom CNN architecture with class weights to address class imbalance.
4. Evaluation: Analyzing the model's performance using accuracy, loss, confusion matrix, and classification report.


## Dependencies
- Python 3.x
- TensorFlow 2.x
- Keras
- scikit-learn
- NumPy
- Matplotlib


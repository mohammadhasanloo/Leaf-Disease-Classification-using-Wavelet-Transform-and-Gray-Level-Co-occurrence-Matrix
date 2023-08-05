# Leaf Disease Classification using Wavelet Transform and Gray-Level Co-occurrence Matrix

This repository contains code for classifying leaf diseases using wavelet transform and gray-level co-occurrence matrix (GLCM) features. The dataset is downloaded from Kaggle and includes images of different leaf diseases. We will emphasize the usage of the `pywt` library and the `dwt2` method for wavelet transform, as well as extracting GLCM features like contrast, energy, dissimilarity, and homogeneity.

## Dataset Download and Setup

Before running the code, you need to have a Kaggle account and obtain the `kaggle.json` file. Then, upload the `kaggle.json` account information to download the dataset from Kaggle.

1. Upload `kaggle.json`: Place the `kaggle.json` file in the current directory by running the following code:

2. Download and Unzip the Dataset: Run the following code to download and unzip the leaf disease dataset.

## Data Preprocessing and Feature Extraction

The code performs data preprocessing and feature extraction before training the machine learning models. It uses wavelet transform to obtain different wavelet coefficients like approximation, horizontal detail, vertical detail, and diagonal detail. Then, it extracts GLCM features (contrast, energy, dissimilarity, and homogeneity) from the wavelet coefficients.

## Model Training and Evaluation

Two machine learning models, Perceptron and Logistic Regression, are used for classification. The models are trained and evaluated on the preprocessed dataset. The accuracy and other metrics are displayed to evaluate the performance of each model.

## Usage

To run the code, execute the notebook and follow the instructions provided in the cells. The steps include dataset download, data preprocessing, feature extraction, model training, and evaluation.

Feel free to experiment with different machine learning models and image processing techniques to improve the classification accuracy.

## Pywt Library and dwt2 Method

The main highlight of this code is the usage of the `pywt` library, specifically the `dwt2` method, for performing wavelet transform on the leaf images. The `dwt2` method allows us to obtain wavelet coefficients at different levels of detail, enabling better feature extraction for classification.

## GLCM Features

Another essential aspect is the extraction of GLCM features, including contrast, energy, dissimilarity, and homogeneity. These features provide valuable information about the textures present in the leaf images, which aids in distinguishing different leaf diseases.

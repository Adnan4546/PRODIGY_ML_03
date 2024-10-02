# PRODIGY_ML_03
Cat and Dog Image Classification using SVM
Project Overview
This project implements an SVM (Support Vector Machine) model to classify images of cats and dogs. The images are preprocessed, converted to grayscale, and resized before feeding them into the SVM classifier. The goal is to distinguish between the two classes: cats and dogs.

Dataset
The dataset used is the "Dogs vs. Cats" dataset from Kaggle, containing labeled images of cats and dogs stored in separate folders.

Project Steps
Load and Preprocess Images:

Images are converted to grayscale.
Resized to 64x64 pixels.
Flattened into 1D arrays.
Train-Test Split:

Dataset is split into training and test sets using train_test_split.
Model Training:

Trained an SVM classifier using a linear kernel.
Model Evaluation:

Evaluated using accuracy score on the test set.
Installation
Install required libraries:

pip install numpy opencv-python scikit-learn
Download the dataset from Kaggle Dogs vs. Cats.

Run the script:

python cat_dog_classification.py

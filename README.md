# cbis-ddsm-breast-cancer-classification-custom-cnn
Project Overview

This project implements a custom Convolutional Neural Network (CNN) from scratch using PyTorch to classify breast masses as benign or malignant from full mammogram images.

The model is developed and evaluated using the CBIS-DDSM (Curated Breast Imaging Subset of Digital Database for Screening Mammography) dataset. It focuses on binary classification of mammograms containing breast masses, distinguishing between benign and malignant cases.

Unlike transfer learning approaches that use pretrained architectures, this project explores a custom CNN architecture designed and trained from scratch to learn relevant image features directly from mammography data.

Model training and evaluation leverage GPU acceleration to improve computational efficiency.

Dataset

CBIS-DDSM – Curated Breast Imaging Subset of Digital Database for Screening Mammography

Mammography images containing breast masses.

Binary classification: Benign (0) and Malignant (1).

Full mammogram images used as model input.

DICOM image format.

The dataset is not included in this repository. Users must obtain the dataset separately and configure the appropriate dataset path.

Technologies Used

Python

PyTorch

Torchvision

Custom Convolutional Neural Network (CNN)

CUDA – GPU Acceleration

NumPy

Matplotlib

Scikit-learn

Pydicom

Model Architecture

A custom CNN architecture developed using PyTorch, with convolutional layers for feature extraction and fully connected classification layers for binary prediction.

The network is trained from scratch rather than using pretrained weights.

Model Training

The model is trained using labelled mammography images, with the following classification targets:

Class

Label

Benign

0

Malignant

1

GPU acceleration is used during training to improve computational performance.

Model Evaluation

Model performance is evaluated using:

Training and validation accuracy.

Training and validation loss.

Confusion matrix.

Classification report.

Precision, recall and F1-score.

Repository Contents

Jupyter Notebook – Data preprocessing, model development, training and evaluation.

README.md – Project documentation.

Disclaimer

This project is developed for academic and research purposes. It is not intended for clinical diagnosis or to replace professional medical assessment.

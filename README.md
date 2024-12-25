

### Overview

# This repository provides a framework for classifying Electrocardiogram (ECG) signals into two categories:

# Normal: Indicates a healthy heart rhythm.

# Left Bundle Branch Block (LBBB): A type of heart block affecting the left bundle branch.

# The project leverages signal processing techniques and machine learning to achieve accurate classification. It includes tools for preprocessing ECG data, feature extraction, model training, and evaluation.

### Features

# Data Preprocessing: Includes the following steps:

# Mean removal.

# Bandpass filter using a Butterworth filter (0.5 to 40 Hz).

# Normalization to the range [-1, 1].

# Feature Extraction: Wavelet transform with level 2 decomposition using Daubechies (DB3) wavelets.

# Machine Learning Models: Supports training and evaluation of classifiers such as:

# Support Vector Machines (SVM).

# k-Nearest Neighbors (KNN).

# Random Forest.

# Visualization: Provides plots of ECG signals and classification results.

# User-Friendly Interface: Built with streamlit for an interactive and easy-to-use UI.

### Installation

# Prerequisites

# Ensure you have the following installed:

# Python 3.12+

# pip

## Clone the Repository
# $ git clone (https://github.com/Mohammed-Gadd/ECG-Normal-LBBB-classification.git)




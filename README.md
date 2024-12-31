# Multi-Class and Multi-Label Classification & Clustering Analysis

## Project Overview
This project implements multi-class and multi-label classification on the Anuran Calls (MFCCs) dataset using Support Vector Machines (SVMs) and explores K-means clustering techniques. The analysis includes evaluation metrics specific to multi-label classification problems and addresses class imbalance issues.

## Key Features
- Implementation of SVMs with Gaussian and L1-penalized kernels for multi-label classification
- SMOTE implementation for handling class imbalance  
- K-means clustering analysis with automatic k selection
- Comprehensive evaluation using:
 - Exact match score
 - Hamming score/loss
 - Confusion matrices
 - Precision, recall, ROC, and AUC metrics

## Technical Implementation
- **Data Processing**: Random 70-30 train-test split
- **SVM Implementation**: 
 - Gaussian kernel with optimized parameters using 10-fold cross-validation
 - L1-penalized SVMs with standardized attributes
- **Clustering Analysis**:
 - K-means implementation with automated k selection
 - Majority label assignment for clusters
 - Hamming distance calculation between true and assigned labels

## Technologies Used
- Python
- Scikit-learn
- NumPy
- Pandas 
- Matplotlib/Seaborn for visualization

## Dataset
The Anuran Calls (MFCCs) Dataset from UCI Machine Learning Repository, featuring:
- Multiple audio features
- Three label categories: Families, Genus, and Species
- Multi-class and multi-label classification structure

## Results
- Detailed performance metrics for different SVM implementations
- Comparative analysis of models with and without SMOTE
- Clustering effectiveness evaluation using Hamming metrics

This project was completed as part of USC's DSCI 552 course under the guidance of Professor Mohammad Reza Rajati.

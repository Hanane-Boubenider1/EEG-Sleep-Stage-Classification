# # EEG Sleep Stage Classification using Time Series Analysis

## Overview

This project presents an intelligent sleep stage classification system based on electroencephalogram (EEG) signals. Using time series analysis and machine learning techniques, the system classifies EEG recordings into different sleep stages through signal preprocessing, feature engineering, dimensionality reduction, and supervised learning models.

The project demonstrates a complete machine learning workflow for biomedical time-series data, from exploratory analysis to model evaluation.

---

# Project Objectives

* Analyze EEG time-series signals
* Apply preprocessing and feature engineering techniques
* Extract meaningful statistical and frequency-domain features
* Compare multiple machine learning classification models
* Evaluate model performance using classification metrics

---

## Dataset

The dataset consists of EEG recordings collected for sleep stage analysis.

- **Training set:** 5000 labeled EEG samples
- **Test set:** 1000 unlabeled EEG samples
- **Target classes:**
  - Wake
  - E1
  - E2
  - E3
  - REM

Each sample represents an EEG signal corresponding to one sleep stage.
---

# Methodology

## Data Analysis

The project includes:

* Exploratory Data Analysis (EDA)
* Correlation analysis
* Data visualization
* Class distribution analysis

## Feature Engineering

Features were extracted using:

* Time-domain analysis
* Frequency-domain analysis
* Nonlinear signal analysis

A total of 29 engineered features were generated for each EEG sample.

## Dimensionality Reduction

Principal Component Analysis (PCA) was applied to reduce dimensionality while preserving important variance.

## Machine Learning Models

Several models and techniques were explored, including:

* Random Forest
* Support Vector Machine (SVM)
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Neural Networks

---

# Technologies and Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow
* Matplotlib
* Seaborn
* AntroPy
* Jupyter Notebook

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
```

Navigate to the project directory:

```bash
cd your-repository-name
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
TSA_Group_Project.ipynb
```

Run the notebook cells sequentially to reproduce the experiments and results.

---

# Results

The project demonstrates the effectiveness of machine learning techniques for EEG sleep stage classification and highlights the importance of feature extraction and preprocessing in time-series analysis.

---

# Team Members

* Dhikra Maram Latreche
* Hana Saadi
* Hanane Boubenider
* Maroua Bouzira

---

# Academic Context

This project was developed as part of the Time Series Analysis and Classification (TSAC) course.

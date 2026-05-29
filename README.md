# 🎙️ Speech Authentication & Gender Classification System

A machine learning pipeline for speaker identification and gender classification using audio signal processing, feature extraction, and classical machine learning techniques.

This project explores speech authentication and audio classification using real-world voice datasets and multiple ML models.

---

# Features

## ✅ Audio Preprocessing

Implemented several preprocessing techniques for speech signals:

* Noise reduction
* Audio normalization
* Resampling
* Signal windowing
* Spectral analysis

The preprocessing pipeline ensures consistent and high-quality audio features for downstream learning tasks.

---

# Feature Extraction

Extracted both frequency-domain and time-domain audio features including:

* MFCC (Mel Frequency Cepstral Coefficients)
* Log-Mel Spectrogram
* FFT-based features
* Spectral Contrast
* Spectral Centroid
* Zero-Crossing Rate
* Energy-based features

These features were used for both speaker authentication and gender classification tasks.

---

# Machine Learning Tasks

## 1. Gender Classification

Classified speaker gender using supervised machine learning models trained on extracted speech features.

## 2. Closed-set Speaker Authentication

Implemented speaker identification in a closed-set setting where the system predicts the identity of a speaker among known individuals.

---

# Models Used

Multiple machine learning models were trained and compared:

* SVM (Support Vector Machine)
* KNN (K-Nearest Neighbors)
* Logistic Regression
* MLP (Multi-Layer Perceptron)
* XGBoost

Model performance was evaluated and compared using multiple metrics.

---

# Evaluation Metrics

The project includes detailed evaluation and analysis using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC Curves
* Confusion Matrices

---

# Clustering & Visualization

Applied dimensionality reduction and clustering methods for feature-space analysis and visualization.

## Techniques Used

* PCA
* t-SNE
* K-Means Clustering
* Silhouette Analysis

These methods helped analyze speaker separability and clustering structure in the extracted feature space.

---

# Tech Stack

## Libraries & Tools

* Python
* NumPy
* Pandas
* Scikit-learn
* Librosa
* SciPy
* Matplotlib

---

# Project Structure

```text id="v9t1hb"
2_1+2_2.ipynb   → preprocessing + feature extraction
2_3.ipynb       → classification models
2_4.ipynb       → clustering and visualization
```

---

# Example Pipeline

```text id="opjlwm"
Raw Audio
   ↓
Preprocessing
   ↓
Feature Extraction
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Evaluation & Visualization
```

---

# Running the Project

## Install Dependencies

```bash id="crmg2e"
pip install -r requirements.txt
```

## Run the notebooks

```bash id="o4z3n8"
jupyter notebook
```

Open and run:

* `2_1+2_2.ipynb`
* `2_3.ipynb`
* `2_4.ipynb`

---

# Learning Objectives

This project explores:

* Speech signal processing
* Audio feature engineering
* Machine learning for speech tasks
* Speaker authentication systems
* Audio classification pipelines
* Clustering and representation learning

---

# Disclaimer

This project was developed for educational and research purposes as part of a machine learning/audio processing course project.

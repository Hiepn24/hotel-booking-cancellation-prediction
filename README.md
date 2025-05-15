# hotel-booking-cancellation-prediction

## 🏨 Hotel Booking Cancellation Prediction
This project focuses on analyzing and predicting hotel booking cancellations using various machine learning approaches. The goal is to explore multiple data processing pipelines and identify the optimal modeling strategy for classification.

## 📌 Objective
To predict whether a hotel booking will be canceled based on historical booking data, by experimenting with five distinct machine learning pipelines combining supervised learning, unsupervised learning (clustering), and dimensionality reduction techniques (PCA).

## 🧪 ML Pipelines
### 🔁 Pipeline 1: Baseline Supervised Learning
+ Original data → Supervised Learning
### 🔁 Pipeline 2: Dimensionality Reduction
+ Original data → Dimensionality Reduction (PCA) → Supervised Learning
### 🔁 Pipeline 3: Clustering Feature Augmentation
+ Original data → Unsupervised Learning (Clustering) → Augment data with cluster labels as new features → Supervised Learning
### 🔁 Pipeline 4: Clustering + Dimensionality Reduction
+ Original data → Unsupervised Learning (Clustering) → Augment data with cluster labels → Dimensionality Reduction (PCA) → Supervised Learning
### 🔁 Pipeline 5: Dimensionality Reduction + Clustering
+ Original data → Dimensionality Reduction (PCA) → Unsupervised Learning (Clustering) → Augment data with cluster labels → Supervised Learning

## 🛠️ Technologies Used
+ Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
+ PCA for dimensionality reduction
+ DBSCAN, GMM for unsupervised learning
+ Various classifiers (e.g., SVM, Decision Trees, Random Forests)

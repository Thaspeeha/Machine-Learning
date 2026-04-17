# Machine-Learning

# 📘 Machine Learning Assignment 1 – Weekly Progress (W3–W11)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN-red)
![Status](https://img.shields.io/badge/Status-Completed-green)


## 📌 Table of Contents
- [🧠 Week 3 – K-Means Clustering](#-week-3--k-means-clustering)
- [📊 Week 4 – Model Evaluation](#-week-4--model-evaluation-knn--classification-metrics)
- [🌳 Week 5 – Decision Trees](#-week-5--decision-trees-iris-dataset)
- [⚙️ Week 6 – Perceptron Model](#-week-6--perceptron-model)
- [🧩 Week 7 – SVM Classification](#-week-7--svm-classification)
- [🧠 Week 8 – Multi-Layer Perceptron](#-week-8--multi-layer-perceptron-mlp)
- [🔍 Week 9 – KNN Hyperparameter Tuning](#-week-9--knn-hyperparameter-tuning)
- [🧮 Week 10 – CNN & Deep Learning](#-week-10--cnn--deep-learning)
- [📈 Week 11 – Regression Analysis](#-week-11--regression-analysis--model-comparison)
- [📌 Summary](#-summary)


## 🧠 Week 3 – K-Means Clustering
- Optimal cluster value determined using the Elbow Method was **K = 3**.  
- Data was grouped into three clusters with balanced distribution.  
- Clusters showed clear separation, indicating effective clustering.


## 📊 Week 4 – Model Evaluation (KNN / Classification Metrics)
- K = 7 achieved better performance with **AUC = 0.948 vs 0.923 for K = 3**.  
- F1-score improved, showing better precision-recall balance.  
- Final conclusion: **K = 7 is the best-performing model**.


## 🌳 Week 5 – Decision Trees (Iris Dataset)
- Using all 4 features gave the best or near-best accuracy.  
- Feature reduction had minimal impact on performance.  
- All features contribute meaningfully to classification.


## ⚙️ Week 6 – Perceptron Model
- Misclassification rate: **~5.90%**.  
- Indicates linear inseparability in the dataset.  
- Perceptron struggled with overlapping classes.


## 🧩 Week 7 – SVM Classification
- Misclassification reduced to **~4–4.6% depending on C**.  
- Higher C improved training accuracy slightly.  
- SVM outperformed perceptron using margin optimization.


## 🧠 Week 8 – Multi-Layer Perceptron (MLP)
- MLP learned non-linear decision boundaries using hidden layers.  
- Increasing neurons improved performance significantly.  
- Best model achieved **up to 100% accuracy (Iris dataset)**.


## 🔍 Week 9 – KNN Hyperparameter Tuning
- Best K selected: **K = 11** via cross-validation.  
- Despite low accuracy, it was the most stable configuration.  
- Final test accuracy: **~32.4%**.


## 🧮 Week 10 – CNN & Deep Learning
- Demonstrated convolution-based feature extraction.  
- More epochs improved training accuracy but caused overfitting.  
- Kernel size 3×3 performed better than 5×5.


## 📈 Week 11 – Regression Analysis & Model Comparison
- Best model: **Sales = 23.42 × Advertising + 167.7**.  
- Selected based on lowest SSE (least squares error).  
- Regression models compared for best fit.


## 📌 Summary
This assignment demonstrates core Machine Learning concepts including clustering, classification, regression, neural networks, and deep learning. It highlights model evaluation, hyperparameter tuning, and performance comparison across algorithms.


## 🚀 Tools & Technologies
- Python  
- Scikit-learn  
- Pandas & NumPy  
- TensorFlow / CNN concepts  
- Google Collab

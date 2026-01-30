# Artificial Intelligence Fundamentals - Laboratory Course

This repository contains a series of Jupyter Notebooks developed as part of the "Artificial Intelligence Fundamentals" course from AGH UST 2026. The laboratories cover a wide range of topics in Machine Learning, from basic regression models to advanced recommendation systems.

## Project Structure

The project is organized into several laboratory exercises, each focusing on specific AI/ML concepts:

### [Lab 1: Linear and Logistic Regression](./lab1.ipynb)
- **Objective**: Implementation of fundamental regression and classification models.
- **Key Concepts**: 
  - Data preprocessing (cleaning, handling missing values, scaling, categorical encoding).
  - Linear Regression for predicting property prices (Ames Housing dataset).
  - Logistic Regression for binary classification (Bank Marketing dataset).
  - Model evaluation using metrics like RMSE, MAE, Accuracy, Precision, and Recall.
  - Regularization techniques (L1/L2) and Cross-Validation.

### [Lab 2: Decision Trees and Ensemble Methods](./lab2.ipynb)
- **Objective**: Exploring non-linear models and ensemble techniques.
- **Key Concepts**:
  - Construction and tuning of Decision Trees.
  - Random Forests and Gradient Boosting.
  - Importance of feature selection and hyperparameter optimization using `GridSearchCV`.

### [Lab 3: Support Vector Machines (SVM)](./lab3.ipynb)
- **Objective**: Understanding margin-based classification and kernel tricks.
- **Key Concepts**:
  - Linear and non-linear SVMs.
  - Kernel functions (RBF, Polynomial).
  - Impact of the cost parameter (C) and gamma on model generalization.

### [Lab 4: Basic Neural Networks](./lab4.ipynb)
- **Objective**: Introduction to Multi-Layer Perceptrons (MLP).
- **Key Concepts**:
  - Architecture of shallow neural networks.
  - Backpropagation and optimization algorithms (SGD, Adam).
  - Activation functions (ReLU, Sigmoid, Tanh).

### [Lab 5: Convolutional Neural Networks (CNN)](./lab5bylejakaledziala.ipynb)
- **Objective**: Deep Learning for Computer Vision.
- **Key Concepts**:
  - Convolutional layers, pooling layers, and dropout.
  - Image classification tasks.
  - Usage of deep learning frameworks (e.g., PyTorch or TensorFlow/Keras).

### [Lab 6: Unsupervised Learning](./lab6.ipynb)
- **Objective**: Finding patterns in unlabeled data.
- **Key Concepts**:
  - Clustering using K-Means and Hierarchical methods.
  - Dimensionality reduction using Principal Component Analysis (PCA) and t-SNE.
  - Evaluating clusters using the Silhouette Score.

### [Lab 7: Recommender Systems](./lab7.ipynb)
- **Objective**: Building systems to predict user preferences.
- **Key Concepts**:
  - Baseline models (Item Average, Bayesian Average).
  - Collaborative Filtering: User-based and Item-based K-Nearest Neighbors (KNN).
  - Matrix Factorization: Singular Value Decomposition (SVD) and FunkSVD.
  - Evaluation metrics: RMSE, MAE, MAP@k, and FCP.

## Technologies Used

- **Language**: Python 3.11+
- **Libraries**:
  - `pandas`, `numpy`: Data manipulation and numerical computation.
  - `scikit-learn`: Implementation of most ML algorithms and preprocessing.
  - `scikit-surprise`: Specialized library for Recommender Systems.
  - `matplotlib`, `seaborn`: Data visualization.
  - `jupyter`: Interactive development environment.

## How to Run

1. **Environment Setup**:
   It is recommended to use `uv` or `venv` to manage dependencies.
   ```bash
   # Using uv:
   uv venv
   source .venv/bin/activate  # or .venv\Scripts\activate on Windows
   uv sync
   ```

2. **Launch Notebooks**:
   ```bash
   jupyter lab
   ```

3. **Dependencies**:
   Ensure you have the required packages installed as listed in the `requirements.txt` or `pyproject.toml` (if present).

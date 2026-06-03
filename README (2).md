# Deep Learning, Machine Learning & Data Analytics Sandbox

This repository is a structured Data Science portfolio covering the full analytical pipeline — from NumPy foundations and data cleaning through classical ML, unsupervised learning, and deep learning architectures.

---

## 📁 Repository Structure

```
ds-analytics-sandbox/
├── data/               ← Raw .csv datasets used across notebooks
├── notebooks/          ← All Jupyter notebooks (see modules below)
├── pyproject.toml
├── poetry.lock
└── README.md
```

---

## 🔹 Module 1: Foundations — NumPy & EDA

*Core mathematical tools and exploratory data analysis.*

| File | Description |
|------|-------------|
| `numpy_foundations.ipynb` | NumPy basics — vectors, matrices, array operations |
| `eda_bestsellers_analysis.ipynb` | Exploratory data analysis on Amazon bestsellers dataset |

---

## 🔹 Module 2: Data Engineering — Pandas & SQL

*Data cleaning, transformation, and aggregation pipelines.*

| File | Description |
|------|-------------|
| `pandas_data_cleaning.ipynb` | Data ingestion, missing value imputation, type casting |
| `pandas_dataframe_transformations.ipynb` | Table reshaping, merging, joining strategies |
| `pandas_metrics_aggregation.ipynb` | Multi-source analytics, grouping, pivoting, statistical summaries |

---

## 🔹 Module 3: Classical Machine Learning

*Supervised and unsupervised learning pipelines.*

| File | Description |
|------|-------------|
| `linear_regression_from_scratch.ipynb` | Vectorized linear regression with gradient descent from scratch (NumPy) |
| `ml_regularization_and_tuning.ipynb` | Overfitting diagnostics, L1/L2 regularization, bias-variance tradeoff |
| `ml_classification_models.ipynb` | Supervised classifiers (activity recognition dataset), feature scaling, confusion matrices |
| `ml_unsupervised_clustering.ipynb` | KMeans clustering, Elbow method, market segmentation |

---

## 🔹 Module 4: Deep Learning

*Neural network architectures built with TensorFlow/Keras.*

| File | Description |
|------|-------------|
| `mlp_low_level_tensorflow_mnist_colab.ipynb` | Low-level TensorFlow MLP on MNIST (manual training loop, GradientTape) |
| `dense_network_fashion_mnist_colab.ipynb` | Fully-connected network on Fashion MNIST — hyperparameter experiments, Dropout, BatchNorm |
| `cnn_vgg16_fashion_mnist_colab.ipynb` | CNN + Transfer Learning (VGG16) on Fashion MNIST — feature extraction & fine-tuning |
| `rnn_lstm_imdb_sentiment_colab.ipynb` | RNN/LSTM/Bidirectional architectures on IMDB sentiment classification |

---

## 🔹 Module 5: NLP & Recommendation Systems

*Text processing and collaborative filtering.*

| File | Description |
|------|-------------|
| `nlp_text_summarization_spacy.ipynb` | Text summarization with spaCy and NLTK (extractive, frequency-based) |
| `recommendation_systems_movielens.ipynb` | Collaborative filtering with SVD, SVD++, NMF on MovieLens 100k |

---

## 🛠️ Tech Stack

- **Languages:** Python
- **Deep Learning:** TensorFlow, Keras
- **ML:** Scikit-Learn
- **NLP:** spaCy, NLTK
- **Recommendation Systems:** Surprise
- **Data:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Poetry, Jupyter Notebook, Google Colab
- **Version Control:** Git, GitHub

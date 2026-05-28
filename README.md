# Deep Learning, Machine Learning Engineering & SQL Analytics Sandbox

This repository serves as an advanced production-ready portfolio showcasing end-to-end capabilities in Deep Learning architecture, Classical Machine Learning algorithms built from scratch, Natural Language Processing (NLP), and Complex Relational Database Engineering. 

---

## 📁 Repository Structure & Deep Technical Guide

### 🔹 Module 1: Deep Learning & Computer Vision
* **`notebooks/1_mlp_backpropagation_from_scratch.ipynb`** — **Neural Networks from Scratch.** Full mathematical implementation of a Multi-Layer Perceptron (MLP) using NumPy. Features explicit forward propagation, custom activation derivatives, and manually coded **backpropagation** algorithms for gradient descent optimization.
* **`notebooks/2_mnist_digit_classification.ipynb`** — **Deep Learning Core.** Architecture of fully-connected deep neural networks for MNIST handwritten digit recognition. Includes implementation of Softmax layers, Cross-Entropy loss computation, and iterative batch optimization loops.
* **`notebooks/4_cnn_computer_vision.ipynb`** — **Computer Vision (CNN).** Implementation of Convolutional Neural Networks for image features extraction. Showcases explicit usage of convolutional layers, spatial downsampling via **MaxPooling**, and structural flattening for dense classification.

### 🔹 Module 2: Classical Machine Learning & NLP
* **`notebooks/3_nlp_tfidf_text_classification.ipynb`** — **Natural Language Processing (NLP).** Text analytics pipeline focused on tokenization, lexical normalization, and text embedding vectorization using **TF-IDF**. Features document classification and semantic categorization workflows.
* **`notebooks/5_linear_and_logistic_regression_from_scratch.ipynb`** — **Mathematical Modeling from Scratch.** Explicit implementation of Linear and Logistic Regression frameworks using NumPy. Features vectorized gradient descent execution, custom loss function optimization, and binary classification log-odds transformations.
* **`notebooks/6_model_regularization_and_tuning.ipynb`** — **Model Optimization & Validation.** Practical framework for combating overfitting using Ridge and Lasso regularization techniques. Includes residual analysis, hyperparameter tuning, and advanced model evaluation using MSE, RMSE, and R² metrics.

### 🔹 Module 3: Relational Data Engineering & BI (`SQL / PostgreSQL`)
* **`create_db.sql`** — **Database Schema Architecture.** Full relational database design with complex tables modeling, strict type-casting, and relational integrity constraints (`PRIMARY KEY`, `FOREIGN KEY`).
* **`seed.py`** — **Automated ETL Automation.** A high-performance database population pipeline utilizing the `Faker` library to programmatically generate and inject thousands of structured, production-ready records.
* **`main.py`** — **Database Session Manager.** Core orchestration script handling secure connection pooling, transactional operations, and exception wrappers.
* **`select.sql`** — **Business Intelligence (BI) Query Suite.** Advanced analytical script collection executing multi-table **`JOIN`** operations, aggregations (`SUM`, `AVG`, `COUNT`), and conditional filtering utilizing **`GROUP BY`** and **`HAVING`** clauses.

---

## 🚀 Core Technical Competencies Demonstrated

* **Algorithmic Rigor:** Explicitly scripting backpropagation, gradient calculation, and regression optimization loops without relying on abstract high-level libraries.
* **Model Optimization:** Diagnosing machine learning system behaviors, implementing regularization penalties, and tuning hyperparameters to prevent variance issues.
* **Natural Language Processing (NLP):** Engineering text preprocessing pipelines, constructing high-dimensional feature spaces, and performing document clustering/classification.
* **Data Platform Architecture:** Building solid relational database foundations, structural normalization, and optimizing heavy analytical query scripts.

---

## 🛠️ Tech Stack & Advanced Tools

- **Programming Languages:** Python, SQL
- **Deep Learning & ML:** Applied Neural Networks, Regression Analysis, Regularization (Lasso/Ridge), NumPy
- **Natural Language Processing:** TF-IDF Vectorization, Text Tokenization
- **Database Engineering:** SQL, PostgreSQL, SQLite
- **Environments & Automation:** Jupyter Notebook, Google Colab, VS Code, Git, GitHub, Faker

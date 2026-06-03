Deep Learning, Machine Learning & Data Analytics Sandbox
This repository is a structured Data Science portfolio covering the full analytical pipeline — from NumPy foundations and data cleaning through classical ML, unsupervised learning, and deep learning architectures.

📁 Repository Structure
ds-analytics-sandbox/
├── data/               ← Raw .csv datasets used across notebooks
├── notebooks/          ← All Jupyter notebooks (see modules below)
├── pyproject.toml
├── poetry.lock
└── README.md

🔹 Module 1: Foundations — NumPy & EDA
Core mathematical tools and exploratory data analysis.
FileDescriptionnumpy_foundations.ipynbNumPy basics — vectors, matrices, array operationseda_bestsellers_analysis.ipynbExploratory data analysis on Amazon bestsellers dataset

🔹 Module 2: Data Engineering — Pandas & SQL
Data cleaning, transformation, and aggregation pipelines.
FileDescriptionpandas_data_cleaning.ipynbData ingestion, missing value imputation, type castingpandas_dataframe_transformations.ipynbTable reshaping, merging, joining strategiespandas_metrics_aggregation.ipynbMulti-source analytics, grouping, pivoting, statistical summaries

🔹 Module 3: Classical Machine Learning
Supervised and unsupervised learning pipelines.
FileDescriptionlinear_regression_from_scratch.ipynbVectorized linear regression with gradient descent from scratch (NumPy)ml_regularization_and_tuning.ipynbOverfitting diagnostics, L1/L2 regularization, bias-variance tradeoffml_classification_models.ipynbSupervised classifiers (activity recognition dataset), feature scaling, confusion matricesml_unsupervised_clustering.ipynbKMeans clustering, Elbow method, market segmentation

🔹 Module 4: Deep Learning
Neural network architectures built with TensorFlow/Keras.
FileDescriptionmlp_low_level_tensorflow_mnist_colab.ipynbLow-level TensorFlow MLP on MNIST (manual training loop, GradientTape)dense_network_fashion_mnist_colab.ipynbFully-connected network on Fashion MNIST — hyperparameter experiments, Dropout, BatchNormcnn_vgg16_fashion_mnist_colab.ipynbCNN + Transfer Learning (VGG16) on Fashion MNIST — feature extraction & fine-tuningrnn_lstm_imdb_sentiment_colab.ipynbRNN/LSTM/Bidirectional architectures on IMDB sentiment classification

🔹 Module 5: NLP & Recommendation Systems
Text processing and collaborative filtering.
FileDescriptionnlp_text_summarization_spacy_colab.ipynbText summarization with spaCy and NLTK (extractive, frequency-based)recommendation_systems_movielens_colab.ipynbCollaborative filtering with SVD, SVD++, NMF on MovieLens 100k

🛠️ Tech Stack

Languages: Python
Deep Learning: TensorFlow, Keras
ML: Scikit-Learn
NLP: spaCy, NLTK
Recommendation Systems: Surprise
Data: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Environment: Poetry, Jupyter Notebook, Google Colab
Version Control: Git, GitHub

# icml-topic-modelling-analysis
Machine learning research trend analysis using LDA topic modelling, NLP, and Python on 29 years of ICML publications.
Project Overview
This project explores nearly three decades of machine learning research by applying Latent Dirichlet Allocation (LDA) to papers published at the International Conference on Machine Learning (ICML) between 1987 and 2016.
The objective was to discover hidden research themes and analyse how these topics evolved over time.

Objectives
Clean and preprocess academic text data
Perform exploratory data analysis
Train an LDA topic model
Tune the optimal number of topics using coherence scores
Visualize discovered topics using pyLDAvis
Analyse topic popularity across time

Dataset
The dataset contains ICML research papers with the following fields:

Paper ID
Title
Abstract
Publication Year
Full Paper Text
PDF Filename

Technologies Used
Python
Pandas
NumPy
NLTK
Gensim
Matplotlib
Seaborn
pyLDAvis

Workflow
1. Data Cleaning
Removed duplicate papers
Removed missing values
Prepared publication years

2. Exploratory Data Analysis
Papers published per year
Abstract length distribution

3. NLP Preprocessing
Tokenization
Stop-word removal
Lemmatization
Vocabulary filtering

4. Topic Modelling
Dictionary creation
Bag-of-Words representation
LDA Model Training
Coherence Score Evaluation

5. Topic Interpretation
Five major research topics were identified, including:
Deep Learning & Computer Vision
Probabilistic Modelling
Machine Learning Optimization
Reinforcement Learning
Neural Systems

6. Research Trend Analysis
Topic distributions were analysed across publication years to identify changing research interests.

Results
The analysis showed that:
Deep learning became increasingly important during later years.
Optimization techniques remained consistently important.
Reinforcement learning gained popularity over time.
Probabilistic modelling continued to be an important research area.

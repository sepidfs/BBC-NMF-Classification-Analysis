# 📘 BBC-NMF-Classification-Analysis

This repository provides a comprehensive analysis of the BBC News dataset, combining topic modeling, text classification, and a detailed evaluation of NMF (Non-Negative Matrix Factorization) in different machine-learning contexts. The goal is to understand both the strengths and limitations of NMF and compare it with modern text-classification models.

📊 Project Overview

This project explores three major components:

NMF for topic extraction from textual data

Supervised text classification of BBC news articles

Analytical evaluation of sklearn’s NMF limitations, especially in rating-prediction tasks

The work integrates exploratory analysis, NLP preprocessing, classical ML models, and methodological critique.

🧠 Main Components
1️⃣ BBC News Text Classification

A full machine-learning pipeline was implemented to classify news articles into their correct categories:

Exploratory Data Analysis (EDA)

Text cleaning and preprocessing

Feature extraction with TF-IDF

Supervised models:

Logistic Regression

Linear SVM

Performance comparison and evaluation

Final classification outputs (labels/predictions)

2️⃣ Topic Modeling with NMF

The project applies Non-Negative Matrix Factorization to reveal latent topics in the BBC corpus:

TF-IDF matrix construction

Dimensionality reduction with NMF

Interpreting topic components

Visualization of learned topics and top keywords

3️⃣ Analysis of NMF Limitations

A deeper investigation into why sklearn’s standard NMF is often insufficient for recommendation-style problems:

Comparison with simple predictors (global mean, user mean, item mean)

RMSE evaluation on the ratings dataset

Discussion of structural limitations:

No user/item bias terms

Equal weighting of missing entries

Sensitivity to initialization

Poor performance on sparse matrices

Suggested improvements and alternative MF algorithms

📁 Deliverables

A single Jupyter Notebook containing:

All code

Visualizations

Analysis and explanations

Model results

Classification outputs for BBC News

NMF topic modeling results

Discussion of NMF limitations and potential enhancements

📚 References

Salton & Buckley — Term-Weighting Approaches

Lee & Seung — NMF Algorithms

Pedregosa et al. — Scikit-learn

BBC Dataset Documentation

Kaggle Discussions (for classification insights)

<img width="533" height="300" alt="image" src="https://github.com/user-attachments/assets/473c68ae-e7c3-46a8-84c3-8f8371afd6b8" />

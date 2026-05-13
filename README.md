# [Your Chosen Repository Name]

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> CSE 476 Data Mining Final Project - Spring 2026  
> Alexandria University, Faculty of Engineering

## 📖 Overview

Complete implementation of recommendation system algorithms from scratch using the 
MovieLens dataset. This project compares three fundamental approaches to recommendation 
systems with rigorous evaluation.

## 🎯 Implemented Algorithms

- **Content-Based Filtering**: TF-IDF on genres/tags, cosine similarity
- **Collaborative Filtering**: User-User and Item-Item with mean-centering
- **Matrix Factorization**: SGD-based latent factor model with regularization
- **Bonus**: Hybrid recommendation system

## 📊 Dataset

MovieLens ml-latest-small (100,000 ratings, 600 users, 9,000 movies)

## 🚀 Features

- Comprehensive EDA with power-law analysis
- Cold-start problem identification and discussion
- Mean-centering for user bias removal
- Systematic evaluation (RMSE, MAE, Precision@10, Recall@10)
- Visualization of all key metrics and distributions

## 📁 Project Structure

├── Part1_DataLoading.ipynb       # Data preprocessing & utility matrix
├── Part1_2_EDA.ipynb             # Exploratory data analysis
├── Part2_ContentBased.ipynb      # Content-based filtering
├── Part3_CollaborativeFiltering.ipynb  # CF implementation
├── Part4_MatrixFactorization.ipynb     # MF with SGD
├── Part5_Evaluation.ipynb        # Comparison & evaluation
├── data/
│   ├── ml-latest-small/          # MovieLens dataset
│   └── processed/                # Cleaned datasets
├── visualizations/               # All generated plots
└── report.pdf                    # Final project report|
## 🛠️ Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## 👥 Team Members

Yaseen Islam - Nadine Emad

## 📄 License

MIT License - see LICENSE file for details

## 🙏 Acknowledgments

- MovieLens dataset by GroupLens Research
- CSE 476 course staff: Dr. Nada Salah, Eng. Nabeel Zamel, Eng. Aya Ragaa

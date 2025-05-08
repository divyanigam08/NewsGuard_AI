# 📰 NewsGuard AI - Fake News Detection with Machine Learning

**NewsGuard AI** is a machine learning-based project designed to classify news articles as **Fake** or **Real** using natural language processing and traditional machine learning algorithms.

## 📌 Project Overview

With the rise of misinformation, it's crucial to have automated systems that help detect fake news. This project processes real and fake news datasets, cleans and prepares the text, and then trains models to accurately classify articles.

## 📂 Dataset

The project uses two CSV files:
- `Fake.csv`: Contains fake news articles.
- `True.csv`: Contains real news articles.

Each dataset includes the title, text, subject, and date.

## 🛠️ Technologies Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (for ML models and metrics)

## 📊 ML Techniques

The project involves:
- Text preprocessing (removing punctuation, lowercasing, etc.)
- Data labeling and merging
- Train-test split
- Feature extraction using TF-IDF
- Model training (e.g., Logistic Regression)
- Evaluation with accuracy score and classification report

## 🧪 How to Run

1. Clone this repository.
2. Install required packages:
   ```bash
   pip install -r requirements.txt

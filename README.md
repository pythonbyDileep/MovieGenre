# MovieGenre
# 🎬 Movie Genre Classification using Machine Learning & NLP

## 📌 Project Overview
This project focuses on building a multi-class classification model that classifies movies into one of seven genres:
- Action
- Comedy
- Drama
- Romance
- Thriller
- Horror
- Fantasy

We explore both **Machine Learning** and **Deep Learning** approaches using textual data (movie descriptions).

---

## 📁 Dataset
- **File Name**: `movie_genre_classification_final.csv`
- Contains movie descriptions and corresponding genre labels.

---

## 🔍 Steps Covered

### 1. Exploratory Data Analysis (EDA)
- Genre distribution
- Missing value checks
- Description length

### 2. Text Preprocessing
- Lowercasing, punctuation removal
- Stopword removal
- Tokenization

### 3. Feature Engineering
- **TF-IDF Vectorization** (for ML models)
- **Tokenizer + Padding** (for LSTM model)

### 4. Model Building

#### ✅ Traditional ML
- `RandomForestClassifier`
- `XGBoost` (optional)
- GridSearchCV for tuning

#### ✅ Deep Learning
- `Bidirectional LSTM` using Keras
- Embedding Layer + Dropout + Softmax

### 5. Evaluation
- Accuracy
- Classification Report
- Confusion Matrix (Seaborn heatmap)

---

## 📦 Libraries Used

- pandas
- numpy
- seaborn, matplotlib
- scikit-learn
- nltk
- tensorflow / keras

---

## 🚀 How to Run

```bash
pip install -r requirements.txt

# 📚 Deepfake Research Analysis & Citation Prediction using Machine Learning

A machine learning and bibliometric analysis project that explores global research trends in **Deepfake Technology** and predicts research paper citation counts using publication metadata and text-based features.

The project combines **Exploratory Data Analysis (EDA)**, **Natural Language Processing (TF-IDF)**, **Feature Engineering**, and **Machine Learning Regression Models** to analyze research impact.

---

## 📌 Project Overview

This project analyzes a dataset containing published research papers on Deepfake technology. The objective is to:

- Clean and preprocess bibliographic data
- Analyze publication trends
- Study author collaboration and keyword evolution
- Identify influential journals and countries
- Predict the number of citations received by research papers using machine learning

---

## 📂 Dataset

The dataset contains metadata of Deepfake-related research papers, including:

- Paper Title
- Authors
- Keywords
- Source Title (Journal)
- Publication Year
- Country
- H-index
- Quartile Ranking
- Citation Count
- Abstract
- DOI
- Publisher
- Other bibliometric information

---

## ✨ Features

### Data Preprocessing
- Removal of duplicate records
- Handling missing values
- Cleaning author names
- Keyword preprocessing
- Column rearrangement
- Data normalization

### Exploratory Data Analysis
- Publication trend analysis
- Country-wise research distribution
- Top keywords analysis
- Keyword evolution over years
- Journal quartile analysis
- H-index analysis
- Citation distribution
- Correlation analysis

### Feature Engineering
- TF-IDF vectorization
- Text preprocessing
- Numerical feature scaling
- Missing value imputation

### Machine Learning
- Random Forest Regressor
- Support Vector Regressor (SVR)
- Gradient Boosting Regressor
- K-Fold Cross Validation
- Hyperparameter tuning using GridSearchCV

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

---

## 📁 Project Structure

```
├── Deepfake data.csv          # Dataset
├── ML_model.ipynb             # Complete analysis notebook
├── README.md
```

---

## 📊 Workflow

1. Load dataset
2. Data cleaning
3. Exploratory Data Analysis
4. Feature engineering
5. TF-IDF vectorization
6. Train-test split
7. Model training
8. Cross-validation
9. Performance evaluation
10. Citation prediction

---

## 📈 Machine Learning Pipeline

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Feature Engineering
    │
    ▼
TF-IDF Vectorization
    │
    ▼
Train/Test Split
    │
    ▼
Regression Models
    ├── Random Forest
    ├── Gradient Boosting
    └── Support Vector Regression
    │
    ▼
Evaluation Metrics
```

---

## 📊 Evaluation Metrics

The models are evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score
- Cross Validation Score

---

## 📌 Key Insights

- Analysis of global Deepfake research trends.
- Identification of frequently used research keywords.
- Study of publication growth over time.
- Comparison of journal quality using quartile rankings.
- Examination of research impact through citation analysis.
- Machine learning models predict citation counts using publication metadata and textual features.

---

## 🚀 Future Improvements

- Deep Learning-based citation prediction
- Interactive dashboard using Streamlit
- Real-time publication analysis
- Topic modeling with LDA/BERT
- Research recommendation system
- Citation network visualization

---

## 👩‍💻 Author

**Shubhi Garg**

GitHub: https://github.com/ShubhiGarg0026

LinkedIn: https://www.linkedin.com/in/shubhi-garg-80297128b

---

## ⭐ If you found this project useful, consider giving it a star!

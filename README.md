# Wine Quality Prediction (Red Wine)

This project involves the application of machine learning techniques to predict the quality of red wine based on its physicochemical properties. The primary objective is to develop a classification model that accurately determines whether a given wine sample is of good quality.

---

## Problem Statement

The quality of wine is influenced by various chemical properties. This project aims to predict wine quality using a binary classification approach:
- Wines with quality scores **≥ 7** are classified as **Good (1)**
- Wines with quality scores **< 7** are classified as **Not Good (0)**

The project includes data analysis, preprocessing, model building, evaluation, and interpretation.

---

## Dataset

- **Source**: UCI Machine Learning Repository  
- **File**: `winequality-red.csv`
- **Records**: 1,599 red wine samples  
- **Features**: 11 physicochemical properties and 1 target variable (`quality`)

---

## Features Used

| Feature               | Description                          |
|-----------------------|--------------------------------------|
| fixed acidity         | Tartaric acid content                |
| volatile acidity      | Acetic acid content                  |
| citric acid           | Citric acid concentration            |
| residual sugar        | Sugar content after fermentation     |
| chlorides             | Salt content                         |
| free sulfur dioxide   | SO₂ not bound to other molecules     |
| total sulfur dioxide  | Total SO₂ content                    |
| density               | Density of the wine                  |
| pH                    | Acidity level                        |
| sulphates             | Sulfate content                      |
| alcohol               | Alcohol concentration                |

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**: 
  - Pandas
  - NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
- **Development Environment**: Jupyter Notebook

---

## Machine Learning Models

The following classification models were implemented and compared:
- Random Forest Classifier
- Support Vector Machine (SVM)

---

## Model Performance

| Model                 | Accuracy |
|----------------------|----------|
| Random Forest         | 88.1%    |
| Support Vector Machine| 85.6%    |

The Random Forest classifier yielded the best performance and was selected as the final model.

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Akshitha2107/wine-quality-prediction.git

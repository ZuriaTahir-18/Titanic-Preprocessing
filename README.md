# Titanic Dataset Preprocessing

This repository contains data preprocessing and cleaning steps applied to the Titanic dataset. The goal is to prepare the dataset for machine learning models by handling missing values, encoding categorical features, and performing feature engineering.

## 📁 Project Files

- `DS Project.ipynb`: Jupyter Notebook with all preprocessing steps.
- `README.md`: Project overview and documentation.

## 📊 Dataset

The Titanic dataset is a classic dataset for binary classification tasks and is available on [Kaggle](https://www.kaggle.com/c/titanic/data).

## ⚙️ Preprocessing Steps

The notebook includes:

- Loading and inspecting the dataset
- Handling missing values (e.g., Age, Cabin, Embarked)
- Encoding categorical variables (Label Encoding / One-Hot Encoding)
- Feature engineering (e.g., creating 'FamilySize', extracting 'Title' from names)
- Dropping unnecessary columns


## 📌 Requirements

- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn

Install requirements:
```bash
pip install pandas numpy matplotlib seaborn

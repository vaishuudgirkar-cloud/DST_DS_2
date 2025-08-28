# SCT_DS_2 — Titanic Dataset: Data Cleaning & Exploratory Data Analysis (EDA)

This repository contains a Jupyter Notebook to perform **data cleaning** and **exploratory data analysis (EDA)** on the Titanic dataset (e.g., from Kaggle).

## 📦 Contents
- `Titanic_EDA.ipynb` — Notebook with step-by-step data cleaning and EDA.
- `requirements.txt` — Minimal dependencies to run the notebook locally.

## 🚀 How to Use (Google Colab)
1. Open **Google Colab** → Upload `Titanic_EDA.ipynb`.
2. Run the first cell to upload your `titanic.csv` file (download from Kaggle).
3. Run all cells, view charts and analysis.

## 💻 How to Use (VS Code / Jupyter)
1. Make sure you have Python 3.9+ installed.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Titanic_EDA.ipynb` in Jupyter/VS Code and run.

## 🗂️ Expected CSV format
The notebook expects a file named `titanic.csv` with columns similar to the Kaggle Titanic training set, including:
`PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked`

> If your file has a different name/path, edit the load section in the notebook accordingly.

## ✍️ Notes
- The notebook includes: missing value handling, basic cleaning, distributions, and relationships (e.g., Survival vs Sex, Pclass, Age).
- All plots are done using **matplotlib** to keep dependencies simple.

---
Made for quick submission and easy GitHub upload.

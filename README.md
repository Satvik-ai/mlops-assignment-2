# 🌸 Iris Classification ML Project with DVC Tracking

This project demonstrates an **end-to-end machine learning workflow with data and model versioning using DVC (Data Version Control)**.  
It showcases how to track dataset changes, reproduce experiments, and manage model artifacts while using **Google Cloud Storage (GCS)** as remote storage.

The repository highlights best practices for **ML experiment tracking, reproducibility, and version control**.

---

## 📌 Project Overview

The goal of this project is to build and compare Iris classification models trained on **multiple dataset versions** while tracking changes using DVC.

The workflow includes:

1. Dataset versioning  
2. Experiment tracking  
3. Model training on multiple data versions  
4. Remote storage configuration  
5. Reproducible pipeline with DVC  

---

## 🗂️ Repository Structure

```
├── Iris_Classification_ML_Training_Pipeline.ipynb # Training + DVC workflow
└── README.md # Project documentation
```

---

## 📁 File Description

### Iris_Classification_ML_Training_Pipeline.ipynb

**Purpose:**  
Implements the training pipeline with DVC integration.

**Key Steps:**

- Initializes Git repository  
- Uses the original Iris dataset (Version 1 — 150 rows)  
- Creates Version 2 dataset by adding noise to `sepal_length` and appending to original data (300 rows)  
- Trains classification models on both dataset versions  
- Tracks datasets and model artifacts using DVC  
- Configures Google Cloud Storage as DVC remote  
- Demonstrates version switching using `dvc checkout`  

---

## ⚙️ Tech Stack

- Python  
- Jupyter Notebook  
- Scikit-learn  
- DVC (Data Version Control)  
- Git  
- Google Cloud Storage (GCS)  

---

## 🎥 Video Presentation  
[▶️ Click Here](https://drive.google.com/file/d/18pNgKGd90F2eTX2vZBCy-VLz8O0yD1jH/view?usp=drive_link)

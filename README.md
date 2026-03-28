# HumanDataset_EDA

# 🧑‍🤝‍🧑 Human Dataset Preprocessing Project

## 📌 Overview

This project focuses on preprocessing a human dataset by cleaning the data and converting all features into numerical format.
Data preprocessing is an essential step in machine learning, as algorithms require structured and numeric input to function effectively.

The project ensures that the dataset is properly prepared for further analysis and model building.

---

## 🎯 Objectives

* Handle missing (null) values in the dataset
* Clean and standardize raw data
* Convert categorical features into numerical values
* Prepare a structured dataset for machine learning

---

## 📂 Dataset Description

The dataset consists of human-related attributes such as:

* Age
* Gender
* Education Level
* Occupation
* Income
* Marital Status
* Working Hours per Week
* Country

These attributes include both numerical and categorical data, which require preprocessing before use in machine learning models.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Collection

The dataset is loaded from a CSV file and stored in a structured format for processing.

---

### 2. Data Cleaning

* Missing values are handled using statistical methods such as mean, median, and mode
* Duplicate records are removed to maintain data consistency
* Data types are verified and corrected

---

### 3. Handling Missing Values

* Numerical columns are filled using mean or median values
* Categorical columns are filled using the most frequent value (mode)

---

### 4. Encoding Categorical Data

Categorical features are converted into numerical format using:

* Label Encoding for ordinal data
* One-Hot Encoding for nominal data

This ensures that all features are compatible with machine learning algorithms.

---

### 5. Final Dataset

After preprocessing:

* All columns are in numerical format
* No missing values remain
* The dataset is clean and structured

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries
3. Run the preprocessing script

---

## 📁 Project Structure

human-dataset-preprocessing/
│── data/
│   └── human_data.csv
│── src/
│   └── preprocessing.py
│── README.md

---

## 🧠 Key Learnings

* Understanding the importance of data preprocessing
* Handling missing values effectively
* Converting categorical data into numerical format
* Preparing datasets for real-world machine learning applications

---

## 🔮 Future Scope

* Apply machine learning models for prediction
* Perform exploratory data analysis and visualization
* Implement feature scaling and selection techniques

---



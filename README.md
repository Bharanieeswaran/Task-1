# 🧹 Task 1: Data Cleaning & Preprocessing

## 📌 Objective
The goal of this task is to clean and prepare raw data for Machine Learning using essential preprocessing steps.

---

## 🛠 Tools & Libraries Used
- Python 🐍
- Pandas 📊
- NumPy 🔢
- Matplotlib 📉
- Seaborn 📌

---

## 📁 Dataset Used
**Titanic Dataset**  
- Contains data about passengers on the Titanic.
- Features include age, sex, fare, passenger class, survival status, etc.

---

## 🔄 Steps Performed

### 1. **Imported and Explored the Dataset**
- Loaded the CSV file using `pandas`.
- Viewed column types, null values, and summary statistics.

### 2. **Handled Missing Values**
- Filled missing numerical values (like `Age`) with **mean**.
- Filled missing categorical values (like `Embarked`) with **mode**.

### 3. **Encoded Categorical Variables**
- Applied **Label Encoding** and **One-Hot Encoding** to convert text to numbers.

### 4. **Feature Scaling**
- Used **Standardization (Z-score)** and **Normalization (Min-Max)** on numeric features like `Fare` and `Age`.

### 5. **Detected and Removed Outliers**
- Used **boxplots** to visualize outliers.
- Removed extreme values using IQR (Interquartile Range) method.

### 6. **Visualized Key Features**
- Plotted correlations and distributions using Seaborn and Matplotlib.

---

## 📈 What I Learned
- How to handle missing data
- How to encode categorical variables
- How to scale features for ML
- How to visualize and remove outliers
- Importance of clean data before applying ML models

---

## ❓ Interview Questions Answered

1. **What are the different types of missing data?**  
   - MCAR, MAR, MNAR

2. **How do you handle categorical variables?**  
   - Using Label Encoding or One-Hot Encoding

3. **Normalization vs Standardization?**  
   - Normalization scales to [0, 1]; Standardization centers data around mean (0) with std deviation 1.

4. **How to detect outliers?**  
   - Boxplots, Z-score, or IQR methods

5. **Why is preprocessing important?**  
   - It ensures better model performance and reduces bias/noise.

6. **One-hot vs Label Encoding?**  
   - One-hot creates binary columns; Label assigns numeric values.

7. **How do you handle data imbalance?**  
   - SMOTE, resampling, using proper evaluation metrics

8. **Does preprocessing affect model accuracy?**  
   - Yes, significantly! Clean and scaled data leads to better models.

---

## 🔗 GitHub Repository
📂 [Repository Link](https://github.com/Bharanieeswaran/Task-1.git)

---

## 📤 Submission
✅ Completed and submitted via the provided submission link.


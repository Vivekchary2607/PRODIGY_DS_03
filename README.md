# 🧠 PRODIGY_DS_02 – Task 03: Predicting Client Subscription Using Decision Tree

## 📌 Task Description  
**Objective:**  
Build a Decision Tree Classifier to predict whether a client will subscribe to a term deposit using demographic and behavioral data. This task involves comprehensive data preprocessing and exploratory data analysis (EDA) on the **Bank Marketing Dataset**.

---

## 📁 Dataset Used  

- **Dataset:** `bank.csv` (Bank Marketing Dataset)
- **Records:** 4521 entries
- **Features:**
  - **Target:** `y` – Client subscribed to term deposit (`yes` or `no`)
  - **Categorical:** `job`, `marital`, `education`, `default`, `housing`, `loan`, `contact`, `month`, `poutcome`
  - **Numerical:** `age`, `balance`, `day`, `duration`, `campaign`, `pdays`, `previous`

---

## 🧹 Data Cleaning Steps  

- ✅ Verified no missing values in any columns
- ✅ Converted categorical columns into numeric using **Label Encoding**
- ✅ Transformed target column `y`:  
  - `no` → `0`  
  - `yes` → `1`
- ✅ Ensured correct data types for all columns
- ✅ Finalized clean dataset for analysis

---

## 📊 Exploratory Data Analysis (EDA)

The following visual analyses were performed to understand the factors influencing client subscription:

### 🔹 Education vs Subscription  
Bar plot showing how education level affects term deposit subscription.  
Clients with **tertiary education** showed higher subscription rates.

### 🔹 Housing Loan vs Subscription  
Bar plot comparing clients with and without housing loans.  
Clients **without housing loans** tend to subscribe more.

### 🔹 Personal Loan vs Subscription  
Comparison of subscription status among clients with/without personal loans.  
Clients **without personal loans** are more likely to subscribe.

### 🔹 Job vs Subscription  
Job-wise subscription distribution.  
**Students**, **retired**, and **management** job roles showed better subscription rates.

---

## 📷 Visual Outputs

- 📊 **Education vs Subscription** (Bar plot)  
- 🏠 **Housing Loan vs Subscription** (Bar plot)  
- 💳 **Personal Loan vs Subscription** (Bar plot)  
- 👔 **Job vs Subscription** (Bar plot)

---

## 🛠️ Libraries Used

- `pandas` – Data handling and wrangling  
- `numpy` – Numerical operations  
- `matplotlib.pyplot` & `seaborn` – Visualization  
- `sklearn.preprocessing` – Label Encoding  
- `sklearn.model_selection` – Train-test splitting  
- `sklearn.tree` – Decision Tree Classifier

---

## ✅ Outcome

- Successfully cleaned and structured dataset  
- Performed visual EDA to uncover key relationships  
- Identified key influencing features for client subscription:
  - **Education**
  - **Job**
  - **Housing Loan**
  - **Personal Loan**
- Prepared the dataset for future modeling and evaluation tasks

---

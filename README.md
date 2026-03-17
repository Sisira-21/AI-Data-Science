# 📊 AI & Data Science Job Market Analysis (2020–2026)

## 📌 Project Overview

This project analyzes the **AI and Data Science Job Market Dataset (2020–2026)** to extract meaningful insights about job trends, salary distribution, required skills, and hiring patterns.

The goal is to understand:

* Which roles are most in demand
* What skills are required
* Salary trends across roles and countries
* Hiring patterns in AI/Data Science

---

## 📂 Dataset Information

* **Dataset Name:** AI Job Market Dataset
* **Source:** Kaggle
* **Format:** CSV
* **Total Features:** 19

### 🔑 Key Columns

* `job_title` – Job role (Data Scientist, ML Engineer, etc.)
* `company_size` – Size of the company
* `company_industry` – Industry type
* `country` – Job location
* `remote_type` – Remote / Hybrid / Onsite
* `experience_level` – Entry, Mid, Senior
* `years_experience` – Experience required
* `salary` – Salary offered
* `skills_python`, `skills_sql`, `skills_ml`, etc. – Required skills

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas 📊
* NumPy 🔢
* Matplotlib / Seaborn 📈 *(optional for visualization)*

---

## 🧹 Data Preprocessing

* Loaded dataset using `pandas.read_csv()`
* Checked missing values using `df.isnull()`
* Removed null values using `df.dropna()`
* Verified data types using `df.info()`

---

## 📊 Analysis Performed

### 1. Salary Analysis

* Average Salary
* Maximum Salary
* Minimum Salary

### 2. Job Role Analysis

* Most common job titles
* Demand for AI/Data roles

### 3. Skill Demand Analysis

* Python, SQL, ML, Deep Learning, Cloud usage

### 4. Country-wise Analysis

* Top hiring countries
* Job distribution by location

### 5. Work Type Analysis

* Remote vs Hybrid vs Onsite jobs

---

## 📈 Sample Code

```python
import pandas as pd

file_path = "/kaggle/input/datasets/shree0910/ai-and-data-science-job-market-dataset-20202026/AI Job Market Dataset.csv"
df = pd.read_csv(file_path)

print(df.head())
print("Average Salary:", df['salary'].mean())
print("Top Job Titles:")
print(df['job_title'].value_counts().head())
```

---

## 🔍 Key Insights

* 📌 Python is the most in-demand skill
* 📌 Data Scientist is the most common job role
* 📌 Remote jobs are increasing significantly
* 📌 Salaries vary based on experience and skills
* 📌 High demand for Machine Learning and Cloud skills

---

## 🚀 Future Improvements

* Add data visualization (graphs & charts)
* Build salary prediction model (ML)
* Deploy as web dashboard (using Django/Flask)
* Integrate real-time job data

---

## 👩‍💻 Author

**Sisira K**
Electronics & Communication Engineering Student

---

## 📜 License

This project is for educational and academic purposes.

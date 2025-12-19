# Big Data Job Description Analysis using PySpark

## 📌 Overview
This project analyzes large-scale job description data to uncover trends in:
- In-demand job roles
- Skills and qualifications
- Salary patterns
- Geographic hiring trends

The analysis was performed using **Apache Spark (PySpark)** on **Google Colab**, enabling scalable processing of a ~1.5GB dataset.

---

## 🎯 Objectives
- Identify high-demand job titles, skills, and qualifications
- Perform exploratory data analysis on global job postings
- Execute analytical queries using PySpark
- Explore salary prediction using machine learning models

---

## 📊 Dataset
- **Source:** Kaggle – Job Description Dataset  
- **Size:** ~1.5 GB  
- **Records:** 13,000+ job postings  
- **Fields:** Job title, skills, experience, salary, location, company, etc.

🔗 Dataset link:  
https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset


## 🛠 Tools & Technologies
- Apache Spark (PySpark)
- Python
- Google Colab
- Scikit-learn
- Matplotlib & Seaborn

---

## 🔍 Key Analysis Performed
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Skill frequency and qualification analysis
- Country, company, and job title trends
- Temporal analysis (daily, weekly, monthly trends)
- Analytical queries (simple, moderate, complex)
- Salary prediction using:
  - Linear Regression
  - Lasso & Ridge Regression
  - Decision Tree
  - Random Forest
  - XGBoost

---

## 📈 Results & Insights
- UX/UI Designer, Software Engineer, and Digital Marketing roles are most in demand
- Python, AWS, Tableau, and SQL are top skills
- BA, MBA, and B.Tech are most requested qualifications
- Random Forest performed best for salary prediction, though overall R² scores were low due to limited features

---

## ▶️ How to Run
Step-by-step instructions are available here:  
📄 `docs/Instructions_to_Run.pdf`

---

## 🚀 Future Work
- NLP-based analysis of job descriptions
- Interactive dashboards (Streamlit / Dash)
- Improved salary prediction using external company data

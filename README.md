
🚢 Titanic Survival Insights – Exploratory Data Analysis (EDA) | Internship Task 5
--

## 📍 Context

This repository is part of my Data Analyst Internship with a focus on applying real-world analytical techniques to classic datasets.  
**Task 5** was to perform a **detailed Exploratory Data Analysis (EDA)** using the **Titanic dataset** to uncover patterns and insights that influenced passenger survival.

---

## 🧠 Problem Statement

> "What factors contributed to a passenger's likelihood of survival on the Titanic?"

The Titanic dataset is not just about numbers—it's a historic tragedy with real people, and behind every row is a story. This EDA aims to dive into those stories, using data to explore **age**, **gender**, **class**, **embarkation**, and other factors that played a role in who lived and who didn’t.

---

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Python** | Core analysis |
| **Pandas** | Data manipulation |
| **NumPy** | Numeric operations |
| **Matplotlib & Seaborn** | Data visualization |
| **Google Colab** | Cloud-based coding |
| **Markdown & GitHub** | Documentation & versioning |

---

## 📂 Project Structure


│
├── Titanic Dataset.csv        # Dataset used for analysis
├── titanic.py                 #Contain the python code used for the process
├── Exploratory Data Analysis on Titanic Dataset.pdf  # PDF report of findings
└── README.md                 # Project documentation

---

## 📊 What I Did – Step-by-Step Walkthrough

### 1. 📥 Data Loading & Initial Exploration
- Loaded data and explored structure, shape, and summary stats
- Understood feature descriptions and distribution of target variable `Survived`

### 2. 🧹 Data Cleaning & Preprocessing
- Identified and handled missing values:
  - Filled `Embarked` using mode
  - Dropped `Cabin` due to excessive nulls
  - Imputed `Age` using median
- Converted categorical data to numeric where necessary

### 3. 🔍 Univariate Analysis
- Studied distributions of single features like `Age`, `Sex`, `Fare`, and `Pclass`
- Used histograms, bar plots, and KDE plots

### 4. 🧩 Bivariate & Multivariate Analysis
- Explored relationships between multiple variables and survival
- Key Findings:
  - Women had a higher survival rate than men
  - Higher class passengers (`Pclass = 1`) had better survival odds
  - Children (<10 years) also had higher survival chances

### 5. 💡 Key Insights

| Factor |Influence on Survival |
|--------|------------------------|
| **Gender** | Female passengers had significantly higher survival |
| **Class** | First-class passengers had a survival advantage |
| **Age** | Children and young adults had a slightly better chance |
| **Embarked** | Port 'C' (Cherbourg) had more survivors proportionally |
| **Family Size** | Traveling with 1–3 relatives increased chances of survival |

---

## 📌 Internship Reflection

> ✅ Applied critical thinking to historical data  
> ✅ Strengthened real-world EDA skills under internship pressure  
> ✅ Learned the importance of storytelling through visuals and insights  
> ✅ Improved speed and structure for data cleaning and visualization tasks

---

## 🌐 Live Preview

> 🔗 **Notebook on Google Colab:**   
> https://colab.research.google.com/drive/1ca5TwofubXd_vSNIzdJ_6Bh9nXdn1EJy#scrollTo=Cqg7M3LsxEEQ

---

## 📞 Let's connect

- 📧 Email ID : sirishadsirishad6@gmail.com
- 💼 LinkedIn : https://www.linkedin.com/in/sirisha-d-064b69278/
  

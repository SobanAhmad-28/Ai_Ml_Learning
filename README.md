# AI & Machine Learning Learning Repository 🚀

> **Course Track:** Apna College — Prime: AI/ML Batch  
> **Student & Developer:** Soban Ahmad ([@SobanAhmad-28](https://github.com/SobanAhmad-28))  
> **Goal:** Build foundational to advanced practical expertise in Data Science, Machine Learning, and Deep Learning.

---

## 📌 Overview

This repository is a structured, production-grade learning archive containing modular practical implementations, tutorial notebooks, and assignment solutions from the **Apna College Prime: AI/ML Batch**.

Every topic is isolated into dedicated modules featuring:
1. **Mathematical & theoretical foundations** explained in clear, intuitive Hinglish directly above each concept.
2. **Clean, documented Python implementations** directly underneath the explanations.
3. **Full assignment worksheets** with verified solutions.

---

## 🗂️ Repository Structure

```text
Ai_Ml_Learning/
├── notebooks/
│   ├── python_fundamentals_part1/
│   │   ├── lec_1_python_fundamentals_part1.ipynb    # Print, Input, Variables, Data Types & Operators
│   │   └── assignment_1_python_fundamentals.ipynb   # 10 Solved Assignment 1 Problems
│   ├── python_fundamentals_part2/
│   │   ├── lec_2_python_fundamentals_part2.ipynb    # Conditionals, Loops, Controls, Range & Functions
│   │   └── assignment_2_python_fundamentals.ipynb   # 10 Solved Assignment 2 Problems
│   ├── python_fundamentals_part3/
│   │   ├── lec_3_python_fundamentals_part3.ipynb    # Strings, Lists, Tuples, Dictionaries & Sets
│   │   └── assignment_3_python_fundamentals.ipynb   # 10 Solved Assignment 3 Problems
│   ├── python_fundamentals_part4/
│   │   ├── lec_4_python_fundamentals_part4.ipynb    # OOPs: Classes, Objects, Constructors & 4 Pillars
│   │   └── assignment_4_python_fundamentals.ipynb   # 10 Solved OOP Problems & Chat Mini-Project
│   ├── python_fundamentals_part5/
│   │   ├── lec_5_python_fundamentals_part5.ipynb    # File I/O, Exceptions, List Comprehensions & JSON
│   │   └── assignment_5_python_fundamentals.ipynb   # 5 Solved File & Exception Handling Problems
│   ├── numpy_fundamentals/
│   │   ├── lec_1_numpy_fundamentals.ipynb           # ndarray, Memory, Reshape, Indexing, Axes, Broadcasting & Math
│   │   └── practice_numpy_fundamentals.ipynb        # 5 Solved Exercises (Downcasting, Z-Score, Softmax Argmax)
│   ├── pandas_part1/
│   │   ├── lec_1_pandas_fundamentals.ipynb          # Series, DataFrame, loc/iloc, Filtering, Query & Data Cleaning
│   │   ├── practice_pandas_part1.ipynb              # 5 Hands-on Wrangling & Imputation Pipeline Exercises
│   │   ├── employee_data.csv                        # Clean sample employee dataset
│   │   └── raw_data.csv                             # Dirty raw dataset with missing values & duplicates
│   ├── pandas_part2/
│   │   ├── lec_2_pandas_advanced.ipynb              # Transformation, GroupBy, Melt/Pivot, Joins, Concat & Plots
│   │   └── assignment_pandas_part2.ipynb            # Solved IRIS Flower & Titanic Passenger EDA Problems
│   ├── sql_fundamentals/
│   │   ├── lec_1_sql_fundamentals.ipynb             # DDL, DQL, DML, TCL, Joins, Group By, Having & Subqueries
│   │   ├── assignment_sql_fundamentals.ipynb        # 10 Solved SQL Problems on Employee Schema (Interactive)
│   │   ├── Sql_Assignment.sql                       # Clean MySQL Workbench / CLI Executable Script
│   │   └── SQL_CheatSheet.pdf                       # Quick Reference Syntax CheatSheet
│   ├── data_collection_web_scraping/
│   │   ├── lec_1_data_collection_and_web_scraping.ipynb  # HTML, Requests, REST APIs, JSON Normalization, BeautifulSoup & CSV Pipeline
│   │   ├── practice_web_scraping_and_apis.ipynb     # 5 Solved Hands-on Exercises (API, Tables, Links, Rate Limiting, Catalog)
│   │   └── Web_Scraping_Reference.pdf               # Quick Reference Guide for Web Scraping
│   ├── data_visualization/
│   │   ├── lec_1_matplotlib_fundamentals.ipynb      # Line, Grouped Bar, Horizontal, Colormaps, Pie Explode & Subplots
│   │   ├── lec_2_seaborn_statistical_visualization.ipynb # Themes, Relational, Categorical, Boxplots, Outliers & Heatmaps
│   │   ├── assignment_data_visualization.ipynb      # 5 Solved Comprehensive Assignment Problems (Penguins, Tips, Normal Dist)
│   │   ├── Matplotlib_Reference.pdf                 # Matplotlib CheatSheet & Reference Notes
│   │   └── Seaborn_Reference.pdf                    # Seaborn Statistical Visualization Notes
│   └── ...                                          # Future topic notebooks (Machine Learning, Scikit-Learn, etc.)
├── scripts/
│   └── sync.ps1                                     # 1-click Git sync automation script
├── .gitignore                                       # Git ignore rules for checkpoints, virtualenvs, and system files
└── README.md                                        # Repository documentation & syllabus tracker
```

---

## 🛠️ Tech Stack & Environment

- **Language:** Python (3.11+)
- **Environment:** JupyterLab / Jupyter Notebook (Anaconda Distribution)
- **Core Libraries (Active & Upcoming):**
  - Data Manipulation: `NumPy`, `Pandas`
  - Visualization: `Matplotlib`, `Seaborn`
  - Machine Learning: `Scikit-Learn`
  - Deep Learning: `PyTorch`, `TensorFlow`
  - Version Control: `Git`, `GitHub CLI`

---

## 🚀 Quick Start Guide

### 1. Clone the Repository
```bash
git clone https://github.com/SobanAhmad-28/Ai_Ml_Learning.git
cd Ai_Ml_Learning
```

### 2. Launch JupyterLab
If using Windows with Anaconda installed:
- Simply double-click `start_jupyter.bat` inside the root directory.

Or run manually via terminal:
```bash
jupyter lab
```

### 3. Sync Daily Work to GitHub
To automatically stage, commit, and push your daily progress with an automated timestamped message, run:
```powershell
powershell -ExecutionPolicy Bypass -File scripts/sync.ps1
```

---

## 📈 Learning Syllabus & Milestones

| Module / Topic | Lecture Topics | Status | Notebook Links |
| :--- | :--- | :---: | :--- |
| **Python Fundamentals (Part 1)** | Core Syntax, I/O, Data Types & Operators | ✅ Completed | [`lec_1_python_fundamentals_part1.ipynb`](notebooks/python_fundamentals_part1/lec_1_python_fundamentals_part1.ipynb) |
| **Python Fundamentals (Assignment 1)** | 10 Practical Problems Solved | ✅ Completed | [`assignment_1_python_fundamentals.ipynb`](notebooks/python_fundamentals_part1/assignment_1_python_fundamentals.ipynb) |
| **Python Fundamentals (Part 2)** | Conditionals, Loops, Controls, Range & Functions | ✅ Completed | [`lec_2_python_fundamentals_part2.ipynb`](notebooks/python_fundamentals_part2/lec_2_python_fundamentals_part2.ipynb) |
| **Python Fundamentals (Assignment 2)** | 10 Logic & Function Problems Solved | ✅ Completed | [`assignment_2_python_fundamentals.ipynb`](notebooks/python_fundamentals_part2/assignment_2_python_fundamentals.ipynb) |
| **Python Fundamentals (Part 3)** | Data Structures: Strings, Lists, Tuples, Dicts & Sets | ✅ Completed | [`lec_3_python_fundamentals_part3.ipynb`](notebooks/python_fundamentals_part3/lec_3_python_fundamentals_part3.ipynb) |
| **Python Fundamentals (Assignment 3)** | 10 Data Structure Problems Solved | ✅ Completed | [`assignment_3_python_fundamentals.ipynb`](notebooks/python_fundamentals_part3/assignment_3_python_fundamentals.ipynb) |
| **Python Fundamentals (Part 4)** | OOP: Classes, Objects, Constructors & 4 Pillars | ✅ Completed | [`lec_4_python_fundamentals_part4.ipynb`](notebooks/python_fundamentals_part4/lec_4_python_fundamentals_part4.ipynb) |
| **Python Fundamentals (Assignment 4)** | 10 OOP Problems & Chat System Mini-Project | ✅ Completed | [`assignment_4_python_fundamentals.ipynb`](notebooks/python_fundamentals_part4/assignment_4_python_fundamentals.ipynb) |
| **Python Fundamentals (Part 5)** | File I/O, Exceptions, List Comprehensions & JSON | ✅ Completed | [`lec_5_python_fundamentals_part5.ipynb`](notebooks/python_fundamentals_part5/lec_5_python_fundamentals_part5.ipynb) |
| **Python Fundamentals (Assignment 5)** | 5 File & Exception Handling Problems Solved | ✅ Completed | [`assignment_5_python_fundamentals.ipynb`](notebooks/python_fundamentals_part5/assignment_5_python_fundamentals.ipynb) |
| **NumPy Fundamentals (Masterclass)** | ndarray, Memory Architecture, Reshaping, Axes, Slicing & Broadcasting | ✅ Completed | [`lec_1_numpy_fundamentals.ipynb`](notebooks/numpy_fundamentals/lec_1_numpy_fundamentals.ipynb) |
| **NumPy Fundamentals (Practice & Assignment)** | 5 Practical Exercises (Downcasting, Z-Score Scaling, Argmax) | ✅ Completed | [`practice_numpy_fundamentals.ipynb`](notebooks/numpy_fundamentals/practice_numpy_fundamentals.ipynb) |
| **Pandas (Part 1: Fundamentals & Cleaning)** | Series, DataFrames, `loc`/`iloc`, Query, Missing Values & String Cleaning | ✅ Completed | [`lec_1_pandas_fundamentals.ipynb`](notebooks/pandas_part1/lec_1_pandas_fundamentals.ipynb) |
| **Pandas (Part 1: Practice Exercises)** | 5 Data Wrangling & Production Imputation Pipeline Exercises | ✅ Completed | [`practice_pandas_part1.ipynb`](notebooks/pandas_part1/practice_pandas_part1.ipynb) |
| **Pandas (Part 2: Advanced Transformations)** | Transformations, GroupBy Aggregations, Melt/Pivot, Joins, Concat & Plots | ✅ Completed | [`lec_2_pandas_advanced.ipynb`](notebooks/pandas_part2/lec_2_pandas_advanced.ipynb) |
| **Pandas (Part 2: Solved Assignments)** | Iris Flower & Titanic Passenger EDA Analysis Solved | ✅ Completed | [`assignment_pandas_part2.ipynb`](notebooks/pandas_part2/assignment_pandas_part2.ipynb) |
| **SQL Fundamentals (Masterclass)** | DDL, DQL, DML, TCL, Joins (Inner, Left, Self), Group By, Having & Subqueries | ✅ Completed | [`lec_1_sql_fundamentals.ipynb`](notebooks/sql_fundamentals/lec_1_sql_fundamentals.ipynb) |
| **SQL Fundamentals (Solved Assignment)** | 10 Solved Employee Schema Problems from Hand-Written Assignment | ✅ Completed | [`assignment_sql_fundamentals.ipynb`](notebooks/sql_fundamentals/assignment_sql_fundamentals.ipynb) |
| **SQL Script (Raw Database File)** | Executable MySQL Script for Table Setup & Queries | ✅ Completed | [`Sql_Assignment.sql`](notebooks/sql_fundamentals/Sql_Assignment.sql) |
| **Data Collection & Web Scraping (Masterclass)** | HTML Basics, HTTP Requests, REST APIs, JSON Normalization, BeautifulSoup & CSV Export | ✅ Completed | [`lec_1_data_collection_and_web_scraping.ipynb`](notebooks/data_collection_web_scraping/lec_1_data_collection_and_web_scraping.ipynb) |
| **Data Collection & Scraping (Practice)** | 5 Solved Exercises (Public APIs, HTML Table Extraction, Hyperlinks, E-Commerce Catalog) | ✅ Completed | [`practice_web_scraping_and_apis.ipynb`](notebooks/data_collection_web_scraping/practice_web_scraping_and_apis.ipynb) |
| **Data Visualization (Matplotlib Masterclass)** | Line Plots, Grouped & Horizontal Bars, Scatter Colormaps, Pie Charts & Subplots | ✅ Completed | [`lec_1_matplotlib_fundamentals.ipynb`](notebooks/data_visualization/lec_1_matplotlib_fundamentals.ipynb) |
| **Data Visualization (Seaborn Masterclass)** | Themes, Relplot, Categorical Boxplots, Outliers, Histograms & Heatmaps | ✅ Completed | [`lec_2_seaborn_statistical_visualization.ipynb`](notebooks/data_visualization/lec_2_seaborn_statistical_visualization.ipynb) |
| **Data Visualization (Solved Assignment)** | 5 Solved Visual & Statistical Problems (Penguins, Tips Outliers, Bell Curve, Heatmap) | ✅ Completed | [`assignment_data_visualization.ipynb`](notebooks/data_visualization/assignment_data_visualization.ipynb) |
| **Upcoming Modules** | NumPy Vectorization & Array Operations | ⏳ Upcoming | `notebooks/numpy/` |

---

## 👤 Author

- **Soban Ahmad**  
- LinkedIn: [@SobanAhmad-28](https://www.linkedin.com/in/soban-ahmad-w)  
- Focus: AI/ML Engineering & Data Science

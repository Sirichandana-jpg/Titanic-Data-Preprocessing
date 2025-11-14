# TASK 1: Titanic-Data-Preprocessing

## 📂 Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **File used:** `Titanic-Dataset.csv`

---

## ⚙️ Steps Performed
1. **Import Dataset** and explore basic info (nulls, data types)
2. **Handle Missing Values** (mean, mode, and column drop)
3. **Encode Categorical Variables** (`Sex`, `Embarked`)
4. **Normalize/Standardize** numerical features (`Age`, `Fare`)
5. **Visualize Outliers** using boxplots and remove them

---

## 📊 Visualizations
- Missing value heatmap (before cleaning)
- Boxplots for outlier detection

---

## 🧠 Interview Questions Covered
- Types of missing data  
- Normalization vs Standardization  
- One-hot vs Label Encoding  
- Why preprocessing is important in ML  
- Handling data imbalance  

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn

---
# TASK 2: Exploratory Data Analysis (EDA)
----------------------------------------

📊 Overview:
This task performs Exploratory Data Analysis on the Titanic dataset using Pandas, Matplotlib, Seaborn, and Plotly.
The goal is to understand the dataset, identify patterns, detect outliers, and prepare it for further machine learning tasks.

----------------------------------------

🔹 What’s Included:
- Loading and exploring the dataset
- Summary statistics (mean, median, std)
- Handling missing values
- Visualizations:
  - Histograms
  - Boxplots
  - Countplots
  - Correlation heatmap
  - Pairplot
  - Interactive Plotly charts
- Key insights and feature-level observations

----------------------------------------

🛠️ Tools Used:
- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Plotly

----------------------------------------

🔍 Key Insights:
- Age and Fare columns contain outliers
- Survival depends strongly on Sex and Pclass
- Fare is right-skewed
- Missing values present in Age
----------------------------------------


## 🚀 How to Run
```bash
# Clone this repository
git clone https://github.com/Sirichandana-jpg/Titanic-Data-Preprocessing.git

# Open in VS Code or Jupyter Notebook
jupyter notebook elevatelabs1.ipynb


# 🚢 Titanic Data Statistical Analysis

## 📌 Project Overview
This project explores the Titanic passenger dataset using **descriptive statistics** and **data visualization**.  
The goal is to analyze passenger demographics, fares, and survival rates, and to identify patterns across different groups.

---

## 🛠 Tools & Libraries
- Python
- pandas → data cleaning & analysis
- matplotlib → visualization
- Jupyter Notebook / Google Colab

---

## 📂 Dataset
The dataset contains passenger information such as:
- `Survived` (0 = No, 1 = Yes)
- `Pclass` (Ticket class: 1, 2, 3)
- `Sex` (male, female)
- `Age` (in years)
- `Fare` (ticket price)

Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  
or public mirror: [GitHub Titanic Dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## 🔑 Steps in the Analysis
1. Load and clean the dataset.  
2. Handle missing values (fill Age with median).  
3. Calculate descriptive statistics (mean, median, std for Age and Fare).  
4. Compute survival rates overall and by groups:
   - Gender
   - Passenger Class
   - Age Groups (Child, Teen, Adult, Senior)  
5. Visualize:
   - Histograms (Age, Fare)
   - Bar charts (Survival by gender, class, and age group)

---

## 📊 Results
- Females had a significantly higher survival rate than males.  
- 1st class passengers survived at a higher rate than 2nd and 3rd class.  
- Children had higher survival rates compared to adults.  

*(Charts and figures are included in the notebook.)*

---

## 🚀 How to Run
1. Clone this repository.  
2. Open `titanic_analysis.ipynb` in Jupyter or Colab.  
3. Run all cells to reproduce the analysis.

---

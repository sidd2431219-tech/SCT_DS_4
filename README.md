# SCT_DS_4
Exploratory Data Analysis of Indian Road Accident Data to identify patterns based on road conditions, weather, and time of day

# 🚦 India Road Accident Data Analysis

## 📌 Project Overview
This project analyzes **Indian road accident data** to identify patterns related to **road conditions, weather, time of day, and accident severity**.  
The goal is to highlight **accident hotspots** and understand **key contributing factors**.

---

## 🗂 Dataset
- **File used:** `accident_prediction_india.csv`  
- **Size:** ~3000 rows, 22 columns  
- **Key columns:**  
  - State Name, City Name  
  - Year, Month, Day of Week, Time of Day  
  - Accident Severity, Number of Vehicles Involved  
  - Number of Casualties, Number of Fatalities  
  - Weather Conditions, Road Type, Road Condition, Lighting Conditions  
  - Speed Limit (km/h), Driver Age, Driver Gender  

> ⚠️ Note: Dataset can be uploaded in the repository (if license allows) or sourced from [data.gov.in](https://data.gov.in/) or Kaggle.

---

## 🔎 Analysis Performed
- ✅ Dataset loading and structure check  
- ✅ Handling missing values and data statistics  
- ✅ Accident distribution by **Time of Day**  
- ✅ Distribution of accidents by **Road Conditions**  
- ✅ Top 10 accident-prone **Weather Conditions**  
- ✅ State-wise and City-wise accident frequency  
- ✅ Correlation analysis between vehicles, casualties, fatalities, speed limit, and age  
- ✅ Extracted **key insights**  

---

## 📊 Visualizations
The following visualizations were created in Python (Matplotlib + Seaborn):
- Bar chart → Accidents by **Time of Day**  
- Pie chart → Accidents by **Road Condition**  
- Horizontal bar chart → Accidents by **Weather Conditions**  
- Line plot → Top **States** with highest accidents  
- Strip plot → Top **Cities** with highest accidents  
- Heatmap → Correlation between **Numerical Factors**

---

## 🚀 Key Insights
1. Most accidents occur during **evening hours**  
2. Road condition with maximum accidents: **Wet/Slippery**  
3. Weather condition linked to most accidents: **Clear weather**  
4. State with most accidents: **Maharashtra** *(example)*  
5. City with most accidents: **Delhi** *(example)*  
6. Highest fatalities recorded in **Uttar Pradesh** *(example)*  

(*Replace these with actual dataset results after running the notebook.*)

---

## 🛠️ Tools & Libraries Used
- **Python**  
- **Pandas** – data manipulation  
- **Matplotlib & Seaborn** – data visualization  
- **NumPy** – numerical computations  

---

## 📌 Future Scope
- Add **geo-coordinates** for mapping accident hotspots  
- Build an **Accident Severity Prediction Model** using ML (Logistic Regression / RandomForest)  
- Develop interactive **dashboards** using Plotly, Power BI, or Tableau  

---

## ⚡ How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/India-Road-Accidents-Analysis.git
---

## 📜 License
This project is intended for **educational and internship purposes**.  
Dataset source rights belong to their respective owners.  
Feel free to use the code for learning and analysis. 

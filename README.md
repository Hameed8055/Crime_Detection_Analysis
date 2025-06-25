# 🕵️‍♂️ Crime_Detection_Analysis

## 📌 Project Summary: Crime Detective System using Data Analysis and Machine Learning

### 🎯 Project Objective
To build a system that analyzes crime data to **track criminal behavior**, discover **crime patterns**, and **predict outcomes** like arrests and crime severity using Python, data analysis, and machine learning.

---

## 🗃️ Dataset Used

You worked with two datasets:

- A **synthetic dataset** with 200,000 crime records, generated for structured analysis.
- A **real-world crime dataset** (e.g., LAPD crime data) including:
  - Crime types  
  - Dates reported and occurred  
  - Locations  
  - Weapons used  
  - Arrest status  
  - Prior offenses

📄 **Project Report (PDF)**  
👉 [Click to Open Report](https://drive.google.com/file/d/1c8Sbr1J4CmcUybM3-KiVuaszXZie4gKx/view?usp=sharing)

---

## 🧹 Data Cleaning & Preprocessing

- Parsed date fields into `datetime` format
- Extracted new features: `hour`, `day_of_week`, `month`
- Encoded categorical features (`Crime_Type`, `Location`, `Weapons_Used`, etc.)
- Checked for duplicates and missing values
- Saved the cleaned dataset to CSV for reuse

---

## 📊 Exploratory Data Analysis (EDA)

Created various visualizations to uncover patterns and trends:

- 📌 Top 10 Crime Types (e.g., Theft, Homicide, Robbery)
- 🕒 Crime Distribution by Time of Day
- 🔫 Crime Severity by Weapon Usage
- 📈 Histogram of Prior Offenses
- 📊 Feature Importance for Predicting Arrests

---

## 🗺️ Geospatial Analysis

- Used **Folium** to plot crimes by geographic coordinates
- Built an interactive map to highlight **hotspot areas**

---

## 🤖 Machine Learning Models Built

### ✅ 1. **Arrest_Made Prediction** (Binary Classification)
- **Features:** Crime type, location, weapons used, prior offenses, time
- **Model Used:** Random Forest  
- **Result:** ~50% Accuracy  
> _(Expected due to weak signal and balanced target classes)_

### ✅ 2. **Crime_Severity Prediction** (Multiclass Classification)
- **Target:** Low / Medium / High
- **Model Used:** Random Forest  
- **Result:** ~33% Accuracy  
> _(Limited learning due to abstract labels and possible class imbalance)_

### ✅ 3. **Feature Importance Visualization**
- Key contributors: `Crime_Type`, `Prior_Offenses`, `Location`

---

## 🧠 Key Insights

- Certain crime types **correlate strongly** with arrest likelihood
- Weapons used showed **minimal influence** on arrests
- **Label engineering** is crucial for meaningful severity predictions
- ML models need **more contextual data** for higher accuracy

---

## 📁 Project Deliverables

- `cleaned_detective_system_data.csv`
- Exploratory visualizations
- Trained ML models
- Interactive crime heatmap
- Full project report [View Here](https://drive.google.com/file/d/1c8Sbr1J4CmcUybM3-KiVuaszXZie4gKx/view?usp=sharing)

---

## 💼 Hire Me or View More

- 🔗 **GitHub Repo:** [Crime_Detection_Analysis](https://github.com/Hameed8055/Crime_Detection_Analysis)
- 💼 **Fiverr:** [https://www.fiverr.com/s/bdwZjoN](https://www.fiverr.com/s/bdwZjoN)

---

## 🚀 Technologies Used

- Python
- Pandas, Seaborn, Matplotlib
- Scikit-learn, XGBoost
- Folium (for maps)
- Jupyter Notebook

---

## 📬 Get in Touch

Feel free to reach out for collaborations, feedback, or freelance work!


Visual reports (EDA plots, feature importance)

Machine learning models for binary and multiclass classification

Python scripts for modeling, cleaning, and visualization


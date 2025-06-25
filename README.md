# Crime_Detection_Analysis
Project Summary: Crime Detective System using Data Analysis and Machine Learning
🎯 Project Objective
To build a system that analyzes crime data to track criminal behavior, discover crime patterns, and predict outcomes like arrests and crime severity using Python, data analysis, and machine learning.

🗃️ Dataset Used
You worked with both:

A synthetic dataset with 200,000 crime records, generated for structured analysis.

A real-world crime dataset (e.g., LAPD crime data) that includes:

Crime types

Dates reported and occurred

Locations

Weapons used

Arrest status

Prior offenses

🧹 Data Cleaning & Preprocessing
Parsed date fields into datetime format.

Extracted new features: hour, day_of_week, month.

Encoded categorical features (Crime_Type, Location, Weapons_Used, etc.).

Checked for duplicates and missing values.

Saved the cleaned dataset to CSV for reuse.

📊 Exploratory Data Analysis (EDA)
You created various visualizations to uncover trends:

Top 10 Crime Types (Theft, Homicide, Robbery, etc.)

Crime Distribution by Time of Day

Crime Severity by Weapon Usage

Histogram of Prior Offenses

Feature Importance for Predicting Arrests

🗺️ Geospatial Analysis
Used folium to map crimes by latitude and longitude.

Created an interactive map to visualize crime hotspots.

🤖 Machine Learning Models Built
✅ 1. Arrest_Made Prediction (Binary Classification)
Features: Crime type, location, weapons used, prior offenses, time

Model Used: Random Forest

Result: Accuracy ~50%
(Expected due to weak signal and balanced target classes)

✅ 2. Crime_Severity Prediction (Multiclass Classification)
Target: Low / Medium / High

Model Used: Random Forest

Result: Accuracy ~33%
(Model failed to learn patterns – severity likely too abstract or imbalanced)

✅ 3. Feature Importance Visualization
Top contributors: Crime_Type, Prior_Offenses, Location

🧠 Key Insights
Certain crime types correlate more with arrests.

Weapons used doesn’t strongly affect arrest likelihood.

ML models need richer, more contextual data for better performance.

Label engineering is crucial for meaningful prediction (e.g., redefining severity classes).

📁 Project Deliverables
Cleaned dataset (cleaned_detective_system_data.csv)

Visual reports (EDA plots, feature importance)

Machine learning models for binary and multiclass classification

Python scripts for modeling, cleaning, and visualization


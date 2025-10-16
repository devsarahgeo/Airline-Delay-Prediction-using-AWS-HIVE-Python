# ✈️ Airline Delay Analysis and Prediction

## 📌 Project Overview
This was a team project, where each team member analyzed flight delay data for a specific year individually.  
The final step involved combining results across multiple years and individually building prediction models to forecast airline delays.  
In the end, we chose the best prediction model based on performance.

### Main Objectives
- Identify the **airports** and **carriers** with the lowest delay times.  
- Compare **arrival vs. departure** delays for airports.  
- Build and evaluate **prediction models** to classify whether a flight would be delayed or not.  

---

## 🔧 My Contribution (2005 Dataset)

### 1. Data Preparation (AWS EMR + Hive)
- Uploaded multiple input CSVs to **Amazon S3** for centralized storage.  
- Set up **Apache Hive** on **AWS EMR** to query and transform the raw flight data.  
- Created Hive **external tables** for structured access to the S3 data.  
- Processed, cleaned, and aggregated the flight records to generate a final **analysis-ready CSV** for the year 2005.  

### 2. Exploratory Analysis (Hive SQL)
- Wrote Hive SQL queries to answer key project questions:
  - Top 3 airports with the lowest delay time.  
  - Top 3 carriers with the lowest delay time.  
  - Comparison of **arrival vs. departure** delays.  

### 3. Modeling (Prediction Task)
- Downloaded my processed dataset and combined it with my teammates’ datasets (covering multiple years).  
- Built **classification models** to predict whether a flight would be delayed or not.  
- Tested and compared different prediction algorithms to evaluate performance.  

---

## 📊 Tech Stack & Skills Showcased
- **AWS S3** – Data storage and management.  
- **Hive on AWS EMR** – Data querying, transformation, and SQL-based analysis.  
- **Python (Pandas, Scikit-learn, etc.)** – Machine learning model development.  
- **Team Collaboration** – Communicated and worked with team members efficiently to combine datasets and results.

---

## 🚀 Outcome
- Delivered insights into delay patterns across **airports** and **carriers**.  
- Compared **arrival vs. departure** delay patterns for airports.  
- Developed predictive models capable of identifying potential delays.  
- Gained hands-on experience in **big data processing**, **SQL on distributed systems**, and **applied machine learning**.  

## Please refer ppt to see the steps taken for this project. Please refer the .ipynb file to see the code



# ✈️ Airline Delay Analysis and Prediction

## 🧭 Executive Summary
This group project focused on analyzing and predicting U.S. airline delays using large-scale flight data. Each team member worked on a specific year, and all results were later combined to identify delay trends across multiple years. The goal was to understand delay patterns, determine the most efficient airports and carriers, and build predictive models to forecast potential flight delays.

### 💼 Business Problem
Flight delays cause significant operational inefficiencies and customer dissatisfaction.
The project aimed to:

- Identify airports and carriers with the lowest delay times.

- Compare arrival vs. departure delay trends.

- Predict whether a flight would be delayed or not using historical data.

By addressing these objectives, airlines and airports can make data-driven decisions to minimize future delays and improve customer experience.

---

## ⚙️ Methodology (2005 Dataset)

### 1. Data Preparation (AWS EMR + Hive)
- Uploaded multiple input CSVs to **Amazon S3** for centralized storage.  
- Configured **Apache Hive on AWS EMR** to query and transform the raw flight data.  
- Created **Hive external tables** for structured access to the S3 data.  
- Processed, cleaned, and aggregated the flight records to generate a final **analysis-ready dataset** for the year 2005.  

### 2. Exploratory Analysis (Hive SQL)
- Used Hive SQL to answer key analytical questions:
  - Top 3 airports with the lowest delay time.  
  - Top 3 carriers with the lowest delay time.  
  - Comparison of **rrival and departure delay patterns**.  

### 3. Modeling (Prediction Task)
- Combined the 2005 dataset with teammates’ datasets from other years.
- Built **classification models** in Python (Scikit-learn) to predict whether a flight would be delayed.
- Tested multiple algorithms and selected the **best-performing model** based on accuracy and F1 score.

---

## 🧠 Skills & Tech Stack
- **AWS S3** – Data storage and versioning
- **Hive on AWS EMR** – Distributed querying and data transformation
- **Python (Pandas, Scikit-learn)** – Model building and evaluation
- **Team Collaboration** – Data integration and performance comparison across multiple contributors
- **Data Analysis & Visualization**: Used Excel for insight generation from the large-scale dataset

---

## 📈 Results
- Identified airports and carriers with consistently **low delay averages**.
- Compared **arrival vs. departure** delay patterns across airports.
- Developed machine learning models capable of predicting flight delays with solid performance metrics.
- Gained hands-on experience in **big data processing**, **SQL on distributed systems**, and **applied machine learning**.

## 📂 Resources
- Presentation (PPT): Detailed project steps and workflow visualization.
- Jupyter Notebook (.ipynb): Data processing, model training, and evaluation code.




# 🏠 Seattle Housing Market EDA — Larry Sanders Project

## 📌 Overview
This repository contains an **Exploratory Data Analysis (EDA)** of the Seattle and surrounding area housing market, tailored to the client **Larry Sanders**.  
The objective was to explore the dataset, test hypotheses, and recommend 3 properties based on Larry's specific preferences:

- **Waterfront property**  
- **Limited budget** (≤ $2,000,000)  
- **Nice & isolated but still central neighborhood**  
- **Low density of children nearby**

---

## 📂 Repository Structure
I. Overview of dataset and data cleaning 
II. Basic descriptive statistics & distributions 
III. Hypothesis testing

---

## 📊 Hypotheses Tested

**H1:** Waterfront properties tend to be more expensive, but there may still be affordable options in less densely populated neighborhoods.  
**H2:** Properties located in central, but less densely populated neighborhoods are more likely to have fewer children.  
**H3:** Waterfront properties that have not been recently renovated may be more affordable, but still have scenic views.

---

## 🗺 Key Features
- **Data Cleaning:** Handled missing values, fixed inconsistent encodings, removed outliers using IQR for visualization clarity.
- **Statistical Analysis:** Summary statistics, distribution plots, and correlation analysis.
- **Geospatial Analysis:** Used `GeoPandas` + `contextily` to map properties across Seattle and cluster central vs. isolated regions.
- **Client Recommendations:** Identified top 3 waterfront properties ≤ $2M with large lots and in quiet neighborhoods.
- **Visual Deliverables:** High-resolution static maps for exploration.

---


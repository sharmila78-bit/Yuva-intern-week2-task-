# Week 2: Exploratory Data Analysis (EDA) and Visualization on Titanic Dataset

## Project Overview
This repository contains the deliverables for **Week 2** of the Data Science internship at **Yuva Intern**. The primary goal is to perform comprehensive Exploratory Data Analysis (EDA) and create statistical data visualizations on the publicly sourced Titanic dataset using Python.

---

## Objectives
* Understand feature relationships, passenger demographics, and survival distributions.
* Handle continuous and categorical feature summaries using statistical metrics.
* Generate high-quality, annotated visual representations using `Matplotlib` and `Seaborn`.
* Derive data-driven business and domain insights from visual patterns.

---

## Tech Stack & Libraries
* **Language:** Python
* **Environment:** VS Code / Jupyter Notebook
* **Libraries:**
  * `pandas` — Data manipulation and summary statistics
  * `matplotlib` — Base plotting and figure styling
  * `seaborn` — Statistical visualizations and distribution plots

---

## Visualizations & Insights

### 1. Survival Rate by Gender (`plot1_survival_by_gender.png`)
* **Finding:** Female passengers had a substantially higher survival count compared to male passengers.
* **Insight:** Confirms adherence to maritime evacuation protocols prioritizing women and children.

### 2. Age Distribution and Survival (`plot2_age_distribution.png`)
* **Finding:** Higher survival density in infants and children (ages 0–10). Working-age adults between 18 and 35 experienced the highest casualty rates.
* **Insight:** Lifeboat access priority favored vulnerable young age demographics.

### 3. Fare Distribution across Passenger Classes (`plot3_pclass_fare_box.png`)
* **Finding:** 1st Class tickets had wide variance and high outliers, while 2nd and 3rd Class fares remained clustered near lower values.
* **Insight:** Clear socio-economic separation in ticketing and cabin placement.

### 4. Correlation Heatmap (`plot4_correlation_heatmap.png`)
* **Finding:** Strong negative correlation between `pclass` and `fare` (-0.55), and negative correlation between `pclass` and `survived` (-0.34).
* **Insight:** Higher-class passengers had a measurably higher probability of survival

# 🏥 Emergency Department Data Analysis & Dashboard

## 📌 Project Overview

This project analyzes Emergency Department patient data using **Microsoft Excel**.

The goal of this project is to understand patient volume, admission patterns, waiting times, patient demographics, referral departments, and patient satisfaction.

The project follows a practical data analyst workflow:

**Raw Data → Data Cleaning → Data Analysis → Dashboard → Business Insights**

An interactive Excel dashboard was created using PivotTables, PivotCharts, formulas, and slicers to make the analysis easy to understand.

---

## 🎯 Business Problem

Emergency departments handle a large number of patients every day. Analyzing patient data can help identify patterns in:

- Patient volume
- Patient demographics
- Hospital admissions
- Waiting times
- Referral departments
- Patient satisfaction
- Monthly emergency department activity

The purpose of this project is to analyze these areas and present the findings in an easy-to-understand dashboard.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze the total number of emergency department patients.
2. Understand patient demographics such as age and gender.
3. Analyze the number of admitted and non-admitted patients.
4. Calculate average patient waiting time.
5. Compare waiting times across referral departments.
6. Analyze monthly patient volume.
7. Analyze patient satisfaction scores.
8. Build an interactive Excel dashboard.
9. Identify meaningful business insights from the data.

---

## 🗂️ Dataset

The dataset contains emergency department patient records.

Each row represents a patient visit.

The dataset includes information such as:

- Patient ID
- Patient Age
- Patient Gender
- Admission Date
- Admission Time
- Department Referral
- Patient Admission Flag
- Patient Satisfaction Score
- Patient Waiting Time
- Age Group
- Admission Year-Month

The dataset contains **9,216 patient records** after preparation and cleaning.

---

## 🧹 Data Cleaning

Before performing the analysis, the dataset was cleaned and prepared in Microsoft Excel.

The cleaning process included:

- Checking for missing values
- Identifying blank cells
- Checking data types
- Formatting date fields
- Standardizing categorical values
- Creating an Age Group column
- Creating an Admission Year-Month field
- Checking numerical columns
- Reviewing inconsistent or missing data
- Preparing the data for PivotTable analysis

The original raw data was kept separately from the cleaned data so that the cleaning process could be reviewed.

---

## 📊 Analysis Performed

### 1. Patient Volume Analysis

Analyzed the total number of emergency department patient visits.

**Total Patients: 9,216**

---

### 2. Patient Demographic Analysis

Analyzed patients based on:

- Gender
- Age groups

The age groups were used to understand which patient age categories had the highest number of visits.

The **Under 18** age group was the largest group, with **1,971 patients**.

---

### 3. Patient Admission Analysis

Analyzed whether patients were admitted to the hospital after their emergency department visit.

The analysis includes:

- Admitted patients
- Non-admitted patients

**Total admitted patients: 4,612**

---

### 4. Waiting Time Analysis

Calculated the overall average patient waiting time.

**Average Waiting Time: 35.3 minutes**

Waiting time was also compared across different referral departments.

- Highest average waiting time: **Neurology — 36.8 minutes**
- Lowest average waiting time: **Renal — 34.7 minutes**

The differences between departments were relatively small, indicating that average waiting times were fairly consistent across the analyzed departments.

---

### 5. Monthly Patient Volume Analysis

Analyzed emergency department visits by month to identify changes in patient volume over time.

Key findings:

- **Highest monthly volume:** January 2024 — **506 patients**
- **Lowest monthly volume:** February 2023 — **129 patients**

This shows noticeable variation in monthly emergency department activity.

---

### 6. Patient Satisfaction Analysis

Patient satisfaction scores were analyzed to understand the overall patient experience.

The dashboard displays the average satisfaction score on a **10-point scale**.

> Note: Missing satisfaction values were reviewed during the data-cleaning process to avoid incorrectly treating missing values as actual satisfaction scores.

---

## 📈 Excel Dashboard

An interactive dashboard was created to present the analysis in a simple and visual format.

### Dashboard Features

The dashboard includes:

- Total Patients KPI
- Admitted Patients KPI
- Average Waiting Time KPI
- Average Patient Satisfaction KPI
- Average Age KPI
- Monthly Patient Visits
- Patient Distribution by Age Group
- Patient Distribution by Gender
- Average Waiting Time by Department
- Patients by Referral Department
- Patient Admission Status
- Interactive slicers

### Interactive Filters

The dashboard includes slicers that allow users to filter the analysis by different patient attributes.

---

## 💡 Key Business Insights

Based on the analysis:

1. The dataset contains **9,216 emergency department patient visits**.

2. **4,612 patients were admitted** after their emergency department visit.

3. The overall average waiting time was **35.3 minutes**.

4. **Neurology** had the highest average waiting time at **36.8 minutes**, while **Renal** had the lowest at **34.7 minutes**.

5. Patients **under 18** represented the largest age group with **1,971 patients**.

6. **January 2024** recorded the highest monthly patient volume with **506 patients**.

7. **February 2023** recorded the lowest monthly patient volume with **129 patients**.

8. Monthly emergency department activity varied considerably throughout the analysis period.

---

## 🛠️ Tools Used

### Microsoft Excel

The entire project was completed using Microsoft Excel.

Excel features used:

- Excel Tables
- Data Cleaning
- Data Formatting
- Excel Formulas
- PivotTables
- PivotCharts
- Slicers
- Dashboard Design
- Data Analysis

---

## 📁 Project Structure

```text
Emergency-Department-Analysis/
│
├── README.md
│
├── Excel/
│   └── Emergency_Department_Analysis.xlsx
│
└── Screenshots/
    └── Emergency_Department_Dashboard.png

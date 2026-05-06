# Hospital Appointment Data Cleaning (Excel + Power Query)

## Project Overview

This project focuses on cleaning and standardizing a hospital appointment dataset to make it suitable for analysis. Real-world datasets often contain inconsistencies, incorrect formats, and mixed data types that can lead to misleading insights if not properly handled.

Using Excel and Power Query, this project transforms raw, messy data into a structured and analysis-ready format.

---

## Dataset Source

* Source: Kaggle
* [see dataset here](https://www.kaggle.com/datasets/nudratabbas/messy-clinic-appointments-dataset)
* Description: The dataset contains hospital appointment records, including patient details, appointment dates, billing information, and follow-up indicators.

---

## Problem Statement

The dataset contained several data quality issues that made analysis unreliable:

* Inconsistent categorical values (e.g., gender and follow-up fields)
* Incorrect date formats
* Mixed currencies embedded in numeric fields
* Non-standardized boolean values

---

## Data Cleaning Process

### 1. Handling Categorical Inconsistencies

* Standardized **Gender** values into:

  * Male
  * Female
* Standardized **Follow-up Required** into:

  * Yes
  * No

---

### 2. Date Formatting

* Converted booking and appointment dates into a consistent date format (dd/mm/yyyy) 
* Ensured compatibility for time-based analysis

---

### 3. Billing Amount Transformation (Power Query)

* Extracted numeric values from mixed text (currencies + numbers)
* Removed non-numeric characters
* Converted column into numeric data type

---

### 4. Data Integrity Decisions

Certain fields were intentionally left unchanged to preserve real-world meaning:

* **Patient ID** → duplicates retained (indicates repeat visits)
* **Patient Name** → unchanged
* **Age** → left as-is due to natural variability
* **Doctor & Department** → already consistent

---

## Before vs After

### Before Cleaning

<img width="792" height="533" alt="Messy" src="https://github.com/user-attachments/assets/6ba0a6fc-34c7-4517-b88d-db33a7b49f38" />


### After Cleaning

<img width="894" height="513" alt="Cleaned" src="https://github.com/user-attachments/assets/6f08fd6e-eafb-4629-bda6-a4dc11c16c48" />


---

## Tools Used

* Microsoft Excel
* Power Query

---

## Outcome

The dataset is now:

* Clean and consistent
* Properly formatted
* Ready for analysis in tools like Power BI, SQL, or Python

---

## Project Files

* Cleaned Dataset: [see here](https://1drv.ms/x/c/e078c146df3d6406/IQBLcT5KJtWdQZaprkGm_SejAUjFuIXR0gtIJnh5Ln6psRI?e=Ld0tff)
* Raw Dataset: [see here](https://1drv.ms/x/c/e078c146df3d6406/IQD-7dHirs-FQ6T28QHT0VwXAf1XANlI_cMnVWYyPVpOAMI?e=PzzXLq)

---

## How to Use

1. Download the cleaned dataset
2. Import into your preferred analysis tool (Power BI, SQL, Python, etc.)
3. Use for data exploration, visualization, or KPI analysis

---

## Contact

If you have feedback or suggestions, feel free to connect with me on LinkedIn or reach out!

# 🏥 Hospital ER Visit Analysis Dashboard

## 📊 Project Overview
This Power BI dashboard provides a deep dive into **Emergency Room (ER) operations** and patient analytics. Using data from 2023 and 2024, the report tracks key performance indicators (KPIs) like patient volume, wait times, and satisfaction scores to help healthcare administrators optimize staffing and improve patient care.

---

## 📁 Repository Structure
* **`Medical report.pbix`** → The primary interactive Power BI dashboard.
* **`Hospital ER_Data.csv`** → The raw dataset containing over 9,000 patient records.
* **`README.md`** → Project documentation and guide.

---

## ✨ Key Insights & Visualizations
The dashboard is divided into several analytical sections:

* **🚀 Executive Summary**: Total patient count, admission rates, and overall satisfaction trends.
* **⏳ Efficiency Metrics**: Analysis of **Patient Wait Times** across different hours of the day and days of the week.
* **🏥 Departmental Referrals**: Tracking patient flow into specialties like *Cardiology, Neurology, Orthopedics, and Renal*.
* **👥 Demographics**: Breakdown of patient visits by **Age, Gender, and Race** to ensure equitable care.
* **⭐ Patient Experience**: Correlation between wait times and satisfaction scores (1-10).

---

## 🛠 Tech Stack & Skills
* **Tool**: Power BI Desktop
* **Data Cleaning**: Power Query (handling nulls in satisfaction scores and formatting dates).
* **Calculations**: DAX (Data Analysis Expressions) used.
* **Data Source**: Flat CSV file (`Hospital ER_Data.csv`).

---

## 🚀 How to View the Project
1.  **Download** the `Medical report.pbix` file from this repository.
2.  **Open** the file using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3.  **Interact** with the slicers on the dashboard to filter data.

---

## 📖 Data Dictionary
| Column Name | Description |
| :--- | :--- |
| **Patient Id** | Unique identifier for each patient visit. |
| **Admission Date** | Timestamp of when the patient entered the ER. |
| **Patient Waittime** | Minutes spent waiting before being seen. |
| **Department Referral** | The specific medical department the patient was sent to. |
| **Admission Flag** | Boolean (True/False) indicating if the patient was admitted to the hospital. |
| **Satisfaction Score** | Patient-reported rating of their experience. |

---

### Developed with 💙 by **Harini SV**
*Feel free to connect with me if you have any questions about the DAX measures or data cleaning steps used in this project!*

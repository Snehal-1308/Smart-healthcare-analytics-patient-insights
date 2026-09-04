# Smart healthcare analytics patient insights Using SAP Analytics Cloud

##  Project Overview

**Smart Healthcare Analytics and Patient Insights** is a healthcare analytics project developed using **SAP Analytics Cloud (SAC)** to transform hospital patient data into meaningful insights through interactive dashboards and visualizations.

The project analyzes patient demographics, diseases, treatment costs, insurance claims, patient outcomes, and regional healthcare trends. The dashboard is designed to support hospitals and healthcare management teams in making data-driven decisions.

---

##  Objectives

The main objectives of this project are:

* Analyze patient demographics and disease distribution
* Monitor patient admission and discharge trends
* Evaluate treatment costs and insurance claim patterns
* Measure patient recovery and healthcare outcomes
* Build interactive and dynamic dashboards using SAP Analytics Cloud
* Provide actionable insights for hospital management

---

##  Tools & Technologies

* SAP Analytics Cloud (SAC)
* Kaggle Healthcare Dataset
* Data Modeling
* Data Visualization
* Dashboard Development
* Data Analytics

---

##  Dataset

The project uses a **hospital patient records dataset sourced from Kaggle** containing information related to patients, treatments, hospital outcomes, insurance claims, and treatment costs.


### Dataset Attributes

The dataset contains the following fields:

| Attribute           | Description                        |
| ------------------- | ---------------------------------- |
| `Patient_ID`        | Unique identifier for each patient |
| `Age`               | Patient age                        |
| `Gender`            | Patient gender                     |
| `Medication`        | Medication provided to the patient |
| `Admission_Date`    | Date of patient admission          |
| `Discharge_Date`    | Date of patient discharge          |
| `Disease`           | Disease diagnosed                  |
| `Patient_State`     | State/region of the patient        |
| `Outcome`           | Patient outcome                    |
| `Insurance_Claimed` | Insurance claim information        |
| `Treatment_Cost`    | Cost associated with treatment     |

---


## Data Preprocessing

Before importing the dataset into SAP Analytics Cloud, the data was cleaned and transformed.

The following preprocessing steps were performed:

* Removed null and duplicate records
* Converted date fields into a standard date format
* Standardized disease and medication names
* Verified treatment cost values
* Cleaned inconsistent outcome records
* Prepared the structured dataset for analytics and visualization

---

##  Derived Metrics

The project uses calculated metrics to support healthcare analysis.

### Recovery Rate

```text
Recovery Rate =
(Recovered Patients / Total Patients) × 100
```

### Average Treatment Cost

```text
Average Treatment Cost =
Total Treatment Cost / Total Patients
```

---

##  SAP Analytics Cloud Implementation

The cleaned healthcare dataset was imported into **SAP Analytics Cloud** using the **Import Model** feature.

### Measures

* Treatment_Cost
* Insurance_Claimed
* Age

### Dimensions

* Disease
* Gender
* Patient_State
* Outcome
* Medication

### Date Dimensions

* Admission_Date
* Discharge_Date

The data was modeled using dimensions, measures, hierarchies, and calculated fields to support dynamic analysis and storytelling.

---

#  Dashboard Design

The project consists of multiple analytical sections designed to provide different perspectives of healthcare data.

## 1. Executive Overview

The Executive Overview provides a high-level view of the patient population.

### Visualizations

* **Donut Chart** – Total Patients per Gender
* **Bar Chart** – Total Patients per State

---

## 2. Patient and Disease Analytics

This section focuses on understanding patient distribution and disease patterns.

### Visualizations

* **Pie Chart** – Total Patients per Disease
* **Bar Chart** – Total Patients per Gender
* **Donut Chart** – Total Patients per Outcome

---

## 3. Financial and Insurance Analytics

This section analyzes treatment costs and insurance claims.

### Visualizations

* **Bar Chart** – Treatment Cost per Disease
* **Tree Map** – Insurance Claimed per Disease
* **Trend Chart** – Average Treatment Cost per Disease

---

## 4. Outcome and Regional Performance

This section provides insights into:

* Patient Outcome Distribution
* Recovery Trends Over Time
* Regional Healthcare Performance

---

#  Screenshorts
## 1. Executive Overview
<img width="1918" height="932" alt="page 1" src="https://github.com/user-attachments/assets/9aa8a2e6-a349-4bf4-8bd6-bc4d07d8ad2b" />

## 2. Patient and Disease Analytics
<img width="1918" height="931" alt="page 2" src="https://github.com/user-attachments/assets/05ca9afa-a8da-4eac-9198-05ba8a9b2a55" />

## 3. Financial and Insurance Analytics
<img width="1918" height="930" alt="page 3" src="https://github.com/user-attachments/assets/1b336bd4-0cac-4f44-b512-823b17f5d215" />

## 4. Outcome and Regional Performance
<img width="1918" height="930" alt="page 4" src="https://github.com/user-attachments/assets/5eecdb5e-199c-42e3-8c8f-a870a055cb9a" />

#  Visualizations

The following visualization types were used:

| Visualization | Purpose                          |
| ------------- | -------------------------------- |
| Line Chart    | Analyze trends                   |
| Bar Chart     | Compare categories               |
| Pie Chart     | Show distribution                |
| Tree Map      | Analyze contribution             |
| Donut Chart   | Show proportions and percentages |

---

#  Filters & Input Controls

Interactive filters were implemented to allow users to explore the healthcare data dynamically.

Available filters include:

* Disease
* Gender
* Outcome
* Patient State
* Admission Date
* Medication

These controls allow users to perform dynamic data exploration and analyze specific segments of the dataset.

---

#  Smart Insights & Forecasting

SAP Analytics Cloud features were used to support:

* Detection of disease patterns
* Identification of high-cost treatments
* Forecasting of future patient admissions
* Analysis of healthcare trends

---

#  Key Insights

### Patient & Disease Insights

* Certain diseases showed significantly higher patient occurrence.
* Recovery rates varied across diseases and age groups.
* Some medications were associated with longer recovery periods.

### Financial & Insurance Insights

* Critical diseases generated higher treatment costs.
* Insurance claims were higher for specialized treatments.
* Some states showed greater healthcare expenditure.

### Regional Healthcare Trends

* Urban regions reported higher patient admissions.
* Certain states experienced seasonal disease patterns.
* Healthcare demand varied significantly across regions.

---

#  Business Recommendations

Based on the analysis, the project recommends that hospitals:

* Improve focus on high-risk diseases
* Optimize resource allocation across departments
* Enhance insurance claim processing efficiency
* Use predictive analytics for hospital planning

---

#  Dashboard Features

The SAP Analytics Cloud story provides:

* Multi-page story navigation
* Dynamic filtering
* Drill-down analysis
* Interactive charts and KPIs
* Healthcare KPI visualization
* Analytical storytelling
* User-friendly dashboard design

---

#  Project Outcome

This project demonstrates how **SAP Analytics Cloud can transform healthcare data into meaningful insights** through interactive dashboards and analytics.

By analyzing patient trends, treatment costs, insurance claims, and healthcare outcomes, the solution can support smarter healthcare management, operational efficiency, and data-driven decision-making.

---

#  Future Enhancements

The project can be further enhanced with:

* Real-time hospital database integration
* AI-based disease prediction models
* Advanced patient risk analysis
* Mobile healthcare analytics dashboards
* Integration with Electronic Health Record (EHR) systems

---

#  References

* Kaggle Healthcare Dataset
* SAP Analytics Cloud Documentation
* SAP Learning Resources
* Healthcare Analytics Research Articles

---

##  Author

**Gurnule Snehal**

**SAP Educate to Employ (E2E) – Analytics Track**

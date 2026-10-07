# Healthcare Performance Dashboard

### Patient, Clinical, Doctor Performance & Financial Analytics

[![Power BI](https://img.shields.io/badge/Microsoft%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Data Analytics](https://img.shields.io/badge/Data%20Analytics-0078D4?style=for-the-badge&logo=googleanalytics&logoColor=white)]()
[![Healthcare Analytics](https://img.shields.io/badge/Healthcare%20Analytics-2E7D32?style=for-the-badge&logo=health&logoColor=white)]()
[![Dashboard](https://img.shields.io/badge/Interactive%20Dashboard-6A1B9A?style=for-the-badge)]()

> **An interactive Microsoft Power BI dashboard designed to analyse patient activity, clinical patterns, doctor performance, billing, insurance and healthcare operations.**

---

## 👨‍💻 Developed By

### **Anurag Kumar Poddar**

**Data Analyst | Business Analyst**

*Microsoft Power BI Portfolio Project*

---

## 📊 Project Overview

The **Healthcare Performance Dashboard** is an interactive Business Intelligence project developed using **Microsoft Power BI**.

The dashboard transforms patient-level healthcare data into a visual analytical solution that helps explore:

- 👥 Patient activity and volume
- 🏥 Bed-category distribution
- 🩺 Diagnosis-wise patient volume
- 👨‍⚕️ Doctor performance
- ⭐ Patient feedback
- 💰 Billing and revenue
- 🛡️ Health insurance amounts
- 🧪 Diagnostic test-wise financial analysis
- 📅 Admission, discharge and follow-up information

The objective is to provide a **single-page management-style dashboard** for faster and clearer healthcare data analysis.

---

## 🎯 Business Objectives

The dashboard was developed to:

- Monitor important healthcare KPIs from a single view
- Analyse patient distribution across different bed categories
- Identify high-volume diagnoses
- Compare doctor-wise patient volume and feedback
- Analyse doctor-wise billing and insurance amounts
- Compare billed and insured amounts across diagnostic tests
- Explore data using interactive patient and date filters
- Convert raw healthcare data into meaningful business insights

---

## 📌 Dashboard Features

| Feature | Description |
|---|---|
| 👥 Patient Analysis | Analyse patient volume and distribution |
| 🏥 Bed Analysis | Compare patients across bed categories |
| 🩺 Diagnosis Analysis | Identify high-volume diagnoses |
| 👨‍⚕️ Doctor Analysis | Compare doctor-wise patient activity |
| ⭐ Feedback Analysis | Analyse average doctor feedback |
| 💰 Revenue Analysis | Analyse billing amounts |
| 🛡️ Insurance Analysis | Compare health insurance amounts |
| 🧪 Test Analysis | Compare billing and insurance by diagnostic test |
| 📅 Date Analysis | Explore admission and discharge periods |
| 🔎 Interactive Filtering | Filter by Patient ID and admission date |

---

## 📈 Dashboard KPIs

The dashboard contains KPI cards for:

### **Earliest Admission**
Displays the earliest admission date within the selected filter context.

### **Latest Discharge**
Provides a discharge-date reference based on the configured report context.

### **Follow-Up Scheduled**
Provides visibility into follow-up scheduling.

### **Bill Amount**
Displays the consolidated billing amount for the selected data.

> KPI values dynamically change according to the active filter context.

---

## 📊 Dashboard Visualizations

<img width="1196" height="746" alt="Healthcare Performance Dashboard" src="https://github.com/user-attachments/assets/008d242b-d1a9-4b22-95d3-6dda18ac4e15" />


### 1. Patient Distribution by Bed Category

**Chart:** Column Chart

**Fields:**
- Bed_Occupancy
- Count of Bed_Occupancy

**Purpose:**

Shows patient distribution across different bed categories such as General, ICU and Private.

---

### 2. Patient Consultations by Attending Doctor

**Chart:** Donut Chart

**Fields:**
- Doctor
- Sum of Feedback

**Purpose:**

Provides a doctor-level comparison using feedback aggregation and helps understand the distribution across attending doctors.

---

### 3. Top Diagnoses by Patient Volume

**Chart:** Funnel Chart

**Fields:**
- Diagnosis
- Count of Diagnosis

**Purpose:**

Ranks diagnoses according to patient volume and highlights higher-volume clinical categories.

---

### 4. Billed vs. Insured Amount by Diagnostic Test

**Chart:** Line Chart

**Fields:**
- Test
- Sum of Health Insurance Amount
- Sum of Billing Amount

**Purpose:**

Compares billed amounts with health insurance amounts across different diagnostic tests.

---

### 5. Revenue & Insurance by Doctor

**Chart:** Clustered Bar Chart

**Fields:**
- Doctor
- Sum of Billing Amount
- Sum of Health Insurance Amount

**Purpose:**

Provides a side-by-side comparison of doctor-wise billing and insurance amounts.

---

### 6. Performance by Doctor

**Chart:** Clustered Bar Chart

**Fields:**
- Doctor
- Average Feedback
- Count of Patient_ID

**Purpose:**

Combines doctor-level feedback and patient volume to provide a broader performance perspective.

---

## 🔎 Interactive Analysis

The dashboard includes interactive filtering through:

- **Patient_ID slicer**
- **Admission Date range slicer**
- Cross-filtering between visuals
- Dynamic KPI updates
- Interactive chart selections

Users can move from an overall healthcare view to a focused analysis of a particular patient or admission period.

---

## 🧠 Key Analytical Questions

The dashboard helps answer questions such as:

- Which bed category has the highest patient volume?
- Which diagnoses have the highest number of patients?
- Which doctors handle higher patient volumes?
- How does doctor feedback vary across doctors?
- Which doctors have higher billing amounts?
- How does health insurance compare with billing?
- Which diagnostic tests have higher financial values?
- How does healthcare activity change across admission periods?

---

## 🗂️ Data Areas

The project uses a structured healthcare dataset containing the following analytical areas:

```text
Healthcare Dataset
│
├── Patient
│   └── Patient_ID
│
├── Admission / Discharge
│   ├── Admit_Date
│   ├── Discharge_Date
│   └── Followup Date
│
├── Clinical
│   ├── Diagnosis
│   └── Test
│
├── Bed / Capacity
│   └── Bed_Occupancy
│
├── Doctor
│   └── Doctor
│
├── Feedback
│   └── Feedback
│
└── Financial
    ├── Billing Amount
    └── Health Insurance Amount


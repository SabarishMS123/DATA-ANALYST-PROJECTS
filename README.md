

```markdown
# 🏥 Healthcare & Clinical Data Analytics Suite

<div align="center">

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Advanced-blue?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-ETL-green?style=for-the-badge&logo=microsoft&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**A comprehensive collection of end-to-end healthcare analytics and clinical business intelligence projects developed in Microsoft Power BI.**

[Analytical Journey](#-analytical-journey--domain-focus) • [Brain Tumor Analytics](#-project-1-brain-tumor-distribution-analytics) • [TB Analytics](#-project-2-naam-hospitals--tuberculosis-analytics) • [Repository Structure](#-repository-structure) • [Tech Stack](#-technology-stack--analytical-methods)

</div>

---

## 📖 Analytical Journey & Domain Focus

Healthcare analytics requires balancing clinical accuracy with intuitive user experience. This repository details two core clinical intelligence implementations:

1. **🧠 Brain Tumor Staging & Cohort Distribution Analysis:**
   - **Histopathology & WHO Staging:** Tracking diagnostic incidence across Grade 1 through Grade 4 pathologies (Meningioma, Pituitary Adenoma, Glioma, Ependymoma, and Medulloblastoma).
   - **Anatomical Mapping:** Regional localization tracking across anatomical brain structures (Pituitary, Frontal, Temporal, Occipital, Parietal, Cerebellum, and Brainstem).
   - **Demographic & Diagnostic Trends:** Correlating average patient age, tumor dimension metrics (cm), confirmed vs. unconfirmed intake trends, and annual diagnosis trajectories.

2. **🫁 NAAM Hospitals – Tuberculosis (TB) Epidemiological & Hospital Analytics:**
   - **Epidemiological Risk Stratification:** Evaluating multi-variable clinical risk determinants including HIV co-infection, diabetes, BMI classification, smoking status, and alcohol intake.
   - **Drug Resistance Surveillance:** Monitoring cohort distribution across Drug-Sensitive, Multi-Drug Resistant (MDR), and Extensively Drug-Resistant (XDR) strains alongside geographical recovery rates.
   - **Operational Hospital & Treatment Suitability:** Benchmarking physician recovery rates, follow-up appointment compliance (averaging 6.50 visits), and institutional bed/care capacity across Government Hospitals, District Hospitals, Community Health Centers, and Medical Colleges.
   - **Temporal Trend Forecaster:** Analyzing month-over-month patient volume patterns, multi-year survival trajectories, and treatment completion throughput.

---

## 🧠 Project 1: Brain Tumor Distribution Analytics

This project visualizes the distribution, anatomical localization, and demographic impact of various brain tumor grades. 

### 📸 Dashboard Screenshots

<div align="center">
  <img src="./images/brain-grade-1.png" width="800" alt="Grade 1 Brain Tumor Analysis" />
  <p><em>WHO Grade 1 Staging Analysis</em></p>
  
  <img src="./images/brain-grade-2.png" width="800" alt="Grade 2 Brain Tumor Analysis" />
  <p><em>WHO Grade 2 Staging Analysis</em></p>
  
  <img src="./images/brain-grade-3.png" width="800" alt="Grade 3 Brain Tumor Analysis" />
  <p><em>WHO Grade 3 Staging Analysis</em></p>
  
  <img src="./images/brain-grade-4.png" width="800" alt="Grade 4 Brain Tumor Analysis" />
  <p><em>WHO Grade 4 Staging Analysis</em></p>
</div>

### 📊 Key Clinical Findings by Grade

* **WHO Grade 1 Staging Analysis**
  * **Clinical Metrics:** 1,588 total patients evaluated, average patient age of 51.55 years, and mean tumor size of 2.03 cm.
  * **Key Findings:** Pituitary tumors account for the highest localized proportion (22% MABR), with Glioma presenting the predominant tumor classification (69.08%). The 41–50 age group is most affected.

* **WHO Grade 2 Staging Analysis**
  * **Clinical Metrics:** 441 patients evaluated, average patient age of 43.05 years, and mean tumor size of 4.08 cm.
  * **Key Findings:** Highest anatomical density observed in the Cerebellum (24% MABR), with Glioma (43.54%) and Meningioma (29.25%) dominating diagnostic distributions.

* **WHO Grade 3 Staging Analysis**
  * **Clinical Metrics:** 84 evaluated cases, average age of 41.21 years, and an elevated mean tumor dimension of 5.97 cm.
  * **Key Findings:** Shift toward higher aggressiveness with Cerebellar localization at 32% MABR; patient cohort heavily concentrated in the 31–40 and 41–50 age groups.

* **WHO Grade 4 Staging Analysis**
  * **Clinical Metrics:** 414 high-grade malignant cases, average age of 40.77 years, and high severity tumor size averaging 6.54 cm.
  * **Key Findings:** Glioma represents 75.12% of cases, followed by Medulloblastoma (24.88%), with the 60+ demographic experiencing the highest rate of severe intake.

---

## 🫁 Project 2: NAAM Hospitals – Tuberculosis Analytics

A comprehensive hospital and epidemiological dashboard tracking TB patient outcomes, drug resistance, demographic risk factors, and operational efficiency across 4 network hospitals.

### 📸 Dashboard Screenshots

<div align="center">
  <img src="./images/naam-landing.png" width="800" alt="TB Landing Page" />
  <p><em>Portal Landing Navigation</em></p>
  
  <img src="./images/naam-overall.png" width="800" alt="Overall Performance" />
  <p><em>Overall Performance Dashboard: Core KPIs & Demographics</em></p>
  
  <img src="./images/naam-hospital.png" width="800" alt="Hospital Analysis" />
  <p><em>Hospital Operational & Facility Suitability Analysis</em></p>
  
  <img src="./images/naam-medical.png" width="800" alt="Medical Analysis" />
  <p><em>Clinical & Medical Diagnostic Analysis</em></p>
  
  <img src="./images/naam-risk.png" width="800" alt="Risk Factor Analysis" />
  <p><em>Risk Factor Stratification Dashboard</em></p>
  
  <img src="./images/naam-time.png" width="800" alt="Time Analysis" />
  <p><em>Longitudinal & Time Trend Analysis</em></p>
  
  <img src="./images/naam-treatment.png" width="800" alt="Treatment Analysis" />
  <p><em>Treatment Protocol & Outcome Analysis</em></p>
</div>

### 🔍 Board Breakdown

* **Overall Performance Dashboard**
  * **Core KPIs:** 10,000 recorded patients, 3,000 recovered cases, 3,000 active MDR cases, with a 34% general baseline recovery rate across 4 network hospitals.
  * **Demographics:** Age group analysis highlights high vulnerability among the 36–55 and 56–75 age categories, split across urban (49.51%) and rural (50.49%) catchments.

* **Hospital Operational & Facility Suitability Analysis**
  * **Facility Benchmarking:** Case intake tracking across Community Health Centers, Government Hospitals, Medical Colleges, and District Hospitals.
  * **Clinical Performance:** Doctor-level recovery rate tracking (ranging between 29% and 38%) alongside an overall treatment completion rate benchmark of 32.82%.

* **Clinical & Medical Diagnostic Analysis**
  * **Pathological Breakdown:** Drug-sensitive strains (34.17%), MDR strains (33.36%), and XDR strains (32.47%).
  * **Co-morbidity Factors:** Multi-variable segmentation correlating HIV positivity, diabetes status, and BMI index distributions.

* **Risk Factor Stratification Dashboard**
  * **Determinant Correlation:** Cross-tabulation of HIV-positive vs. negative cohorts across severity scales (Mild, Moderate, Severe).
  * **Lifestyle Influence:** Outcome distribution (Recovered, Under Treatment, Deceased) correlated against smoking habits and alcohol consumption.

* **Longitudinal & Time Trend Analysis**
  * **Temporal Flow:** Month-by-month recovery volume trends, annual diagnostic trajectories, and seasonal patient intake distributions covering multi-year observation periods.

* **Treatment Protocol & Outcome Analysis**
  * **Therapeutic Efficacy:** Tracking patient progression, drug adherence indicators, and regimen success rates across active treatment groups. Average follow-up visits sit at 6.50, with an average treatment duration of 195.40 days.

---

## 📁 Repository Structure

```text
├── BRAIN TUMOUR ANALYTICS/      # Power BI workbook and assets for neuro-oncology staging
├── TUBERCULOSIS ANALYTICS/      # Power BI workbook and data models for NAAM Hospitals TB study
├── images/                      # High-resolution dashboard screenshots
│   ├── brain-grade-1.png
│   ├── brain-grade-2.png
│   ├── brain-grade-3.png
│   ├── brain-grade-4.png
│   ├── naam-landing.png
│   ├── naam-overall.png
│   ├── naam-hospital.png
│   ├── naam-medical.png
│   ├── naam-risk.png
│   ├── naam-time.png
│   └── naam-treatment.png
├── .gitignore
└── README.md
```

---

## 🛠️ Technology Stack & Analytical Methods

* **Business Intelligence & Visualization:** Microsoft Power BI Desktop
* **Data Modeling:** Star Schema design, healthcare entity normalization, one-to-many relationship mapping
* **Calculations & Logic:** Advanced DAX (cohort filtering, mortality/recovery percentage metrics, time intelligence)
* **ETL & Data Hygiene:** Power Query (handling healthcare records, clinical codes, missing values, and type standardizations)
* **Version Control:** Git, Git LFS, GitHub

---

## 👤 Author Details

**Sabarish M S**
* **Location:** Salem, Tamil Nadu, India
* **Portfolio:** [sabarishdev.netlify.app](https://sabarishdev.netlify.app)
* **GitHub:** [@SabarishMS123](https://github.com/SabarishMS123)

---
<div align="center">
  <i>Developed for advanced clinical business intelligence and epidemiological tracking.</i>
</div>
```

# 📊Exam Dashboard – Power BI Report

## 🔎 Overview

This Power BI project analyzes exam results on different tests and tracks the goals set for each test centre using a sample dataset.

The report is designed as an executive-level dashboard, focusing on KPIs, regional performance, and exam success rates.

---

## 🏗 Data Model

The report is built using a clean **star schema**:

- **Fact Table**
  - FactContractTargets
  - FactExamResults

- **Dimension Tables**
  - DimDate
  - DimRegion
  - DimContract
  - DimTestCentre
  - DimCandidate


The model follows best practices:
- Single-direction relationships
- Hidden foreign keys
- Dedicated measures table
- Organized display folders
- Proper date table configuration

---

## 📈 Key Business Questions Answered

- How many exams are taking place over time?
- What is the exam pass rate, and what is the trend per region?
- Are the regions on track with their goals?
- Which exams are more popular?
- Which exams have higher success rates?

---

## 🚀 Key Features

- Executive KPI overview
- Score band distributions
- Region performance analysis
- Registration to exam lag time
- Universal slicers
- Clean star schema modeling
- Modern report design

---

## 🧠 DAX & Technical Highlights

- Clean measures
- Slicers working on both fact tables
- Optimized DAX measures for performance
- Visual calculations for min/max highlighting
- Optimized reusable base measures
- Custom tooltip pages
- Custom theme

---

## 📊 Report Screenshots

### Executive Overview
![Executive Overview](assets/Executive%20Overview.jpg)

### Sales Performance 
![Operational Drilldown](assets/Operational%20Drilldown.jpg)


---

## 🛠 Tools Used

- Power BI Desktop
- DAX
- CSV data

---

## 🎯 Objective

The purpose of this project is to demonstrate:

- Strong dimensional modeling
- Advanced DAX capabilities
- Business-oriented analytical thinking
- Clean and scalable Power BI design

---

## 📬 Contact

If you’d like to discuss this project or collaborate, feel free to connect.


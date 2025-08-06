# Student_Survey_Pbi_Practise


https://app.powerbi.com/reportEmbed?reportId=9719df77-268b-487c-802b-a1bac9a3f2e4&autoAuth=true&ctid=5532c884-1dee-4813-b3ce-4ee75ee7485e

# 🧠 Student Purchase Analysis - Power BI Report

## 📊 Project Overview

This Power BI project analyzes student spending across various retail stores in the United States based on a survey dataset. It explores insights into purchase behavior on categories like video games, indoor games, toys, books, gadgets, etc., segmented by **Store Location** and **Store Setting**.

**Industry Type:** Retail Store  
**Dataset:** Student Survey  

---

## 📌 Problem Statement

Create a Power BI report to visualize meaningful insights from the Student Survey data.

---

## 📈 Report Visualizations

### 1. **Tabular Visualization**
- Visualize Total Amount of Purchase (TAP) using conditional formatting:
  - 🔴 Red: `0 < TAP < 35,000`
  - 🟡 Yellow: `35,000 <= TAP < 60,000`
  - 🔵 Blue: `TAP >= 60,000`
- Grouped by: `Store Location` and `Store Setting`

### 2. **Matrix Visualization**
- Show the amount spent on **Outdoor Sports**.
- Cross-tabbed by: `Age Groups` × `Store Setting`
- Apply color formatting for total outdoor sports spend.

### 3. **Funnel Chart**
- Show total amount of purchases by `Store Setting`.
- Display **data labels** as **percentage of first**.

### 4. **Pie Chart**
- Display total purchases by `Store Location`.
- Filter to only show for **Suburban** `Store Setting`.

### 5. **Advanced Visuals**
- **Scatter Plot**: 
  - Video games and outdoor sports purchases vs. age.
- **Sand Dance Plot**:
  - Indoor sports and video games spend across age groups.

---

## 🔐 Row-Level Security (RLS)

Restrict data access using the **User Mapping Table**.

> Example:  
> User: *Mani*  
> Role: *Rural only*  
> Access: Can only view records from **Rural** locations, not Urban/Suburban.

---

## ☁️ Cloud Deployment

1. Publish report on **Power BI Cloud Service**.
2. Design a **Master Dashboard**:
   - Includes **Funnel Chart** & **Scatter Plot**
3. Set **Scheduled Refresh**:
   - 6 times a day (every 4 hours)

---

## 💬 Power BI Q&A Feature

Use the Q&A feature to enable natural language queries:

- ✅ Show **average age** of students
- ✅ Show **Donut Chart** for total purchases by `Store Location`

---

## ✅ Deliverables

- [x] Power BI Report File (.pbix)
- [x] Dataset (Student Survey + User Mapping Table)
- [x] Published Dashboard on Power BI Service
- [x] Documentation (README.md)

---

## 📂 Folder Structure (Suggestion)


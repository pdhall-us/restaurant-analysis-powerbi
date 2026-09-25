# 🍽️ Power BI Restaurant Analysis

> **Power BI learning through a hands-on restaurant data analysis and dashboard project.**

This repository contains my practice and progress while learning **Microsoft Power BI** through a Restaurant Analysis Project.

The project is used to explore Power BI concepts, understand different features, work with data, and create meaningful visualizations through practical implementation.

---

## 📊 About the Project

The **Restaurant Analysis Project** uses restaurant-related data to explore and understand the process of working with data in Power BI.

Throughout the project, I will be applying different concepts as I learn them and documenting the steps, concepts, and new terms that I come across.

This repository therefore serves as both a **Power BI project** and a record of my learning throughout the project.

---

## 🛠️ Tools

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge\&logo=microsoftexcel\&logoColor=white)

---

## 📂 Repository Structure

```text
Power-BI-Restaurant-Analysis/
│
├── 📊 Power BI Project
├── 📁 Dataset
├── 🖼️ Dashboard / Screenshots
└── 📄 README.md
```

---

# 📖 Project Progress & Learning Notes

---

## Step 01 — Downloading the dataset

### 🎯 What I Did

Downloaded the dataset that is available online for project purposes.


1. Downloaded and reviewed the restaurant dataset.
2. Opened the dataset in Excel.
3. Explored the available columns and data.
4. Identified the information that could be useful for analysis.

### 📚 What I Learned

**Dataset**

> A dataset is a collection of related data organized in a structured format that can be used for analysis.

### 💡 Analysis Notes

1. After exploring data I found that it is having a excel file named "Data_CFR" that contains 3 sheets which have information of customer, food, and restaurant. Apart from that it also have order data of jan to april 2024 in separate excel files inside order data folder.
2. After analysing the data I found out that inside customer table, membership column is having inconsistent values. At some place there is just G and R instead of Gold and Regular.

---

## Step 02 — Data Preparation

### 🎯 What I Did

1. Loaded **Data_CFR** into Power BI power query to perform transformation.
2. Changed the identified inconistent values through replace.
3. Loaded **Data_CFR** into PowerBi.
4. Then appended "Order Data" folder in power query.
5. Loaded that also in Power BI.

### 📚 What I Learned

**Power Query**
> It is a built-in ETL tool that helps in transforming the data, not only that it also records the transformation steps which is very helpful in automating the reports.

**Append**
> Append is combining two or more table on top of each other.
---

## Step 02 — Data Modeling

### 🎯 What I Did

1. Analyzed the relation between the tables.
2. Created relationship between food details table and order data table.

### 📚 What I Learned

**Dimension Table**
> It contains unique values. Suppose cutomer details, restaurant details, etc.

**Fact Table**
> It contains the main business event or transaction. It can have the repeated unique values of the dimension table. Suppose cutomer id can be repeated.

**Cardinality**
> It is nothing but the relationship type between the tables. it can be one-to-one, one-to-*, and so on.
- For example, one-to-many: from dimension table customer id will be unique and will occur only once, on the other hand in fact table a customer can order multiple times, so it can occur more than one.

---

## 📊 Dashboard

Dashboard screenshots and project results will be added here.

<!--
Example:

![Restaurant Analysis Dashboard](screenshots/dashboard.png)
-->
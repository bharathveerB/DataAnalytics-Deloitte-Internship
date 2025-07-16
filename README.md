# Deloitte : Data Analytics Virtual Experience

This repository contains the completed tasks and insights from the **Deloitte Australia Data Analytics Virtual Job Simulation** hosted on [Forage](https://www.theforage.com/).

## 📌 Overview

As part of this simulation, I stepped into the role of a data analyst in Deloitte’s Forensic Technology team. The experience simulated real-world tasks involving data cleaning, analysis, visualization, and business recommendation reporting.

## ✅ Key Tasks Completed

### 1. Analysis in Excel
Objective

Create a **4th column** named `Equality Class` based on the following logic:

| Equality Score Range | Classification           |
|----------------------|--------------------------|
| -10 to +10           | Fair                     |
| -20 to -11 or 11 to 20 | Unfair                  |
| Less than -20 or greater than 20 | Highly Discriminative |

### ✅ Classification Logic in Excel

The following formula was used in the `Equality Class` column (assuming `Equality Score` is in column C):

```excel
=IFS(C2<-20,"Highly Discriminative",C2>20,"Highly Discriminative",C2<-10,"Unfair",C2>=10,"fair",C2<=10,"Fair")
```


### 2. **Data Visualization with Tableau**
- Created an interactive dashboard to visualize key metrics




## 📊 Tools Used

- **Microsoft Excel**: Data cleaning, classification, pivot tables, formulas
- **Tableau**: Data visualization, dashboard creation



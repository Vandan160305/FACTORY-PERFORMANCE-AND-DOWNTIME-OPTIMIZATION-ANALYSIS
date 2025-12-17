# 📊 Factory Performance And Downtime Optimization Analysis

---

## 🚀 Project Overview

This repository contains my work for the **Factory Performance And Downtime Optimization Analysis** . This Will focuses on solving real-world business problems using **data visualization, analysis, and forensic techniques**.

The project is divided into **two major tasks**:

1. **Operational Analytics using Tableau** – Machine failure analysis across factories
2. **Forensic Data Analysis using Excel** – Gender pay equality investigation

---

## 🛠️ Tools & Technologies

* **Tableau Public / Tableau Desktop** – Interactive dashboards
* **Microsoft Excel** – Data classification & analysis
* **JSON / Excel datasets** – Source data 

---

## 📌 Task 1: Machine Failure Analysis (Tableau)

### 🔍 Business Context

Daikibo Industrials collected telemetry data from **4 global factories**, where machines send health data every **10 minutes** over **one month (May 2021)**.

**Factories Analyzed:**

* Daikibo Factory Meiyo – Tokyo, Japan
* Daikibo Factory Seiko – Osaka, Japan
* Daikibo Berlin – Berlin, Germany
* Daikibo Shenzhen – Shenzhen, China

Each factory operates **9 different machine types**.

---

### 🎯 Client Questions

1. **Which factory had the highest number of machine breakdowns?**
2. **Which machine types failed most frequently in that factory?**

---

### 📊 Analysis Performed

* Parsed and analyzed telemetry data from a unified JSON file
* Created calculated fields to identify **unhealthy / broken machines**
* Built an **interactive Tableau dashboard** to:

  * Compare machine failures by factory
  * Drill down into machine types for the most affected location

  <img width="1918" height="1073" alt="Screenshot 2025-09-21 232741" src="https://github.com/user-attachments/assets/99fdb4ca-4cbd-4678-954c-e13fc32e8efa" />


---

### 📈 Key Insights

* The factory with the **highest number of machine failures** was clearly identified
* Specific machine types (e.g., **Laser Cutter / Heavy Duty Machines**) showed the highest failure frequency in that location
* Dashboard enables quick decision-making for **maintenance prioritization**

---

## 📌 Task 2: Gender Pay Equality Analysis (Excel)

### 🔍 Business Context

Daikibo Industrials raised concerns about **gender-based salary inequality** across roles and locations.

The Forensic Tech team generated an **Equality Score** for each job role:

* Range: **-100 to +100**
* **0** represents perfect pay equality

---

### 📄 Dataset Columns

1. Factory
2. Job Role
3. Equality Score
4. **Equality Class** (Created by me)

---

### 🧮 Classification Logic

I added a new column, **Equality Class**, using the following rules:

| Equality Score Range              | Classification        |
| --------------------------------- | --------------------- |
| -10 to +10                        | Fair                  |
| Less than -10 or greater than +10 | Unfair                |
| Less than -20 or greater than +20 | Highly Discriminative |

#### Examples:

* `10 → Fair`
* `-9 → Unfair`
* `-30 → Highly Discriminative`

---

### 📊 Outcome

* Enabled leadership to **quickly identify roles with pay inequality**
* Supported data-driven decisions for **HR policy corrections**
* Demonstrated forensic-style data classification and interpretation


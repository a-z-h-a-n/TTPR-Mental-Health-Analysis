# TTPR Summer 2025 Capstone Project – Mental Health in Tech

**Team 3 – Foursight**  
TTPR Summer 2025 | Baruch College  

---

## 📌 Project Overview
This project analyzes the **Mental Health in Tech Survey (2014)** dataset to uncover how demographics, workplace support systems, and organizational culture influence mental health in the technology sector.  

The technology industry, with its fast pace and demanding environment, often exposes employees to **burnout, stigma, and limited access to care**. Our goal was to identify trends, barriers, and risk factors while providing **data-driven recommendations** for building healthier workplaces.  

---

## 🧹 Methodology
Our approach combined **data cleaning, normalization, and exploratory data analysis (EDA)** using Python, followed by the creation of **interactive dashboards in Power BI**.  

**Steps:**
- Removed irrelevant columns and standardized categorical variables.  
- Normalized gender (45+ variations → Male/Female/Non-binary).  
- Restricted age values to realistic ranges (16–100).  
- Checked for duplicates, nulls, and inconsistencies.  
- Re-labeled company size categories (`no_employees → company_size`).  
- Visualized findings with **Matplotlib, Seaborn, and Power BI dashboards**.  

**Tools Used:**  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebooks  
- Power BI  

---

## 📊 Key Insights
### 1. Demographics & Treatment
- Younger professionals (16–24) have the **lowest treatment-seeking rate (45%)**, while older groups (55–64) reach **71%**.  
- Female respondents are **most likely to seek treatment (69%)**, compared to **45% for men**.  
- The dataset reflects tech’s **male-dominated workforce** (813 male vs. 185 female vs. 27 “Other”).  

### 2. Workplace Support
- **Company size matters:** Larger firms (1000+ employees) report the highest benefits access (65%), while very small companies (<25 employees) show the lowest (only ~10% with benefits).  
- Employees with care options: **68% sought treatment**, vs. 40% without options. Awareness itself is as important as actual access.  

### 3. Culture & Stigma
- Employees are more comfortable discussing mental health with **coworkers than supervisors**, highlighting the impact of hierarchy and stigma.  
- **Anonymity in workplace resources** significantly increases trust and treatment-seeking.  

### 4. Remote & Self-Employment
- Remote workers report **fewer available resources**, though treatment rates are similar to in-person employees.  
- Self-employed individuals are **slightly more likely** to seek treatment and less likely to report workplace consequences.  

---

## 📸 Power BI Dashboards
Interactive dashboards were built to highlight treatment patterns, demographic gaps, and workplace support availability.  

### 🌍 Treatment Rate by Country & Care Access
![Treatment by Country](Treatment%20Rates%20By%20Country%20and%20Care%20Access.png)

### 👥 Treatment Seeking by Age & Gender
![Treatment by Age and Gender](Treatment%20Seeking%20By%20Age%20and%20Gender%20in%20Tech.png)

---

## 📌 Key Recommendations
- **Expand mental health benefits** across all company sizes, especially small/mid-sized firms.  
- **Increase awareness and communication** about available resources, not just availability.  
- **Normalize conversations** by reducing stigma in supervisor-employee interactions.  
- **Ensure anonymity and privacy** in programs to build trust.  
- Collect **more recent datasets** to reflect post-COVID remote work realities and evolving tech culture.  

---

## 👥 Team Members and Roles
- **Sedode Avoseh** – Scrum Master  
- **Azhan Talukder** – Product Owner (Data Cleaning, Python Analysis, GitHub Documentation)  
- **David Taveras** – Product Developer  
- **Ayele Kouevidjin** – Product Developer  

---

## 📖 References
- Kaggle: *Mental Health in Tech Survey (2014)* (Shamim, 2014)  

---

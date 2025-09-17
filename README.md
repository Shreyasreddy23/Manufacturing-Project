# Manufacturing Analytics Project (Group 4)

## 📌 Project Description  
This project demonstrates an end-to-end **manufacturing analytics pipeline** using multiple tools.  
Raw production data was transformed and analyzed with **SQL**, **Excel**, **Tableau**, and **Power BI**, and the results were summarized in a **presentation**.  

The goal was to track **key performance indicators (KPIs)** such as rejection rate, work order completion, and production efficiency, enabling better **decision-making** and **shop-floor visibility**.

---

## 📂 Folder Structure  
Manufacturing-Analytics-Project/
├── excel/                   # Excel-based data analysis and dashboard
├── sql/                     # SQL scripts for database setup and queries
├── tableau/                 # Tableau workbooks and dashboards
├── powerbi/                 # Power BI report files
├── presentation/            # Project presentation slides (PowerPoint)
├── README.md                # Project documentation (this file)

---

## 🛠️ Files and Tools Used  
- **Excel**: KPI dashboard with pivot tables, charts, and raw data analysis.  
- **SQL (MySQL)**: Database schema + queries for manufacturing analytics.  
- **Tableau**: Interactive dashboards for production and quality metrics.  
- **Power BI**: Real-time KPI dashboard with rejection rates and completion % metrics.  
- **PowerPoint**: Final project presentation summarizing goals, methods, and results.  

---

## 🔎 Component Overviews  

### 📊 Excel Dashboard  
- Raw manufacturing data + KPI calculations.  
- Sheets include: `Data`, `Dashboard`, `Employee and Machine`, `Units vs Rejected`, and `Department Wise Manufacture`.  
- Visual summary of metrics using PivotCharts and formulas.  

👉 **To view:** Open in **Microsoft Excel** and check the **Dashboard** sheet.  

---

### 🗄️ SQL Scripts  
- Database: `manufacturing_analytics`  
- Tables: `customers`, `employees`, `items`, `machines`, `operations`, `departments`, `production_records`  
- Includes data population + sample queries/views for production and quality analysis.  

👉 **To use:** Run `SQL_Project.sql` in **MySQL** to build and load the schema.  

---

### 📈 Tableau Dashboard  
- Packaged workbook with interactive dashboards.  
- Shows KPIs like production over time, quality per line, department drill-downs.  

👉 **To view:** Open `.twbx` file in **Tableau Desktop**.  

---

### 📉 Power BI Dashboard  
Key metrics included:  
- ✅ Work Order Completion: ~**80.14%**  
- 📦 Units Produced: ~**60.05 million**  
- ❌ Units Rejected: ~**0.49 million**  
- 📊 Rejection Rate: ~**0.82%**  
- 🧾 Orders Fulfilled: **10,000**  

👉 **To view:** Open `.pbix` in **Power BI Desktop**.  

---

### 🎤 PowerPoint Presentation  
- Contains project workflow, methods, and screenshots.  
- Summarizes objectives, KPIs, and dashboards from Excel, Tableau, and Power BI.  

👉 **To view:** Open `.pptx` in **PowerPoint**.  

---

## 🚀 Instructions to Run  
1. **Clone/download** this repo.  
2. **Install required tools:**  
   - Microsoft Excel  
   - MySQL  
   - Tableau Desktop  
   - Power BI Desktop  
   - PowerPoint  
3. Open the respective files in each tool.  
4. (Optional) Connect Tableau/Power BI to the MySQL database after running the SQL script.  

---




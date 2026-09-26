# 🏥 Hospital Analytics Dashboard

A Power BI-based hospital performance and analytics project designed to help hospital administrators, clinicians, and finance teams monitor operational, patient, and financial performance in a single, interactive dashboard.

This repository contains a sample healthcare analytics dashboard built with Microsoft Power BI. It brings together hospital KPIs, operational metrics, patient flow, physician data, and financial indicators into a single reporting experience that is easy to explore and share.

You can also view the published dashboard here:

- [Power BI report](https://app.powerbi.com/groups/me/reports/64bbf6b3-4ae5-498e-b0e3-2c1438bead80/60e699dc408815843810?experience=power-bi)

![Dashboard Home Page](https://github.com/sibashish9040/Hospital-Dashboard/blob/main/docs/Home_page.png)

---

## 1. Overview

Healthcare organizations deal with large amounts of operational and clinical information every day. This dashboard is designed to provide a quick and clear summary of the most important indicators, so decision-makers can:

- track the overall health of the hospital
- monitor patient and department trends
- understand resource usage such as beds, rooms, and staff
- evaluate doctor performance and treatment activity
- monitor hospital expenses and financial performance
- identify operational bottlenecks and improve planning

The project uses sample data to represent a realistic hospital environment and demonstrates how interactive dashboards can support better operational decisions.

---

## 2. Why This Project Matters

Hospitals often have multiple disconnected data sources such as:

- patient records
- appointment data
- doctor information
- admissions and discharge statistics
- room and bed capacity
- hospital supply and stock
- billing and finance records

This dashboard consolidates these data points into one report so users can see patterns at a glance instead of manually analyzing raw spreadsheets.

It is especially useful for:

- hospital administrators
- department heads
- finance teams
- IT/data analysts
- operational managers
- healthcare consultants

---

## 3. Dashboard Features

This report includes major Power BI capabilities and dashboard design patterns, such as:

- interactive slicers and filters
- KPI cards for quick metrics snapshot
- bar, line, pie, and area charts
- trend monitoring over time
- drill-down and detailed views
- navigation between multiple report pages
- custom tooltips and bookmarks
- responsive visual storytelling for decision-making

### Main report pages

- Overview
- Patient Insights
- Doctor Information
- Hospital Performance
- Financial Analysis
- Home page

The visual layer is built to make hospital data more understandable for both technical and non-technical users.

---

## 4. Dashboard Pages

### 4.1 Home Page
The landing page provides a summary overview of the hospital and serves as the navigation hub for the rest of the report.

![Overview Page](https://github.com/sibashish9040/Hospital-Dashboard/blob/main/docs/overview_page.png)

### 4.2 Overview Page
The overview page presents a high-level summary of hospital operations, likely covering KPIs such as patient volume, bed occupancy, department activity, and service performance.

![Overview Page](https://github.com/sibashish9040/Hospital-Dashboard/blob/main/docs/overview_page.png)

### 4.3 Patient Insights Page
This page focuses on patient-related trends, potentially covering patient distribution, treatment history, satisfaction levels, appointment trends, and patient demographics.

![Patient Page](https://github.com/sibashish9040/Hospital-Dashboard/blob/main/docs/patinet_page.png)

### 4.4 Doctor Information Page
This section highlights doctor-related information such as department assignments, workload, performance metrics, and possibly physician distribution.

![Doctor Page](https://github.com/sibashish9040/Hospital-Dashboard/blob/main/docs/Doctor_page.png)

### 4.5 Hospital Performance Page
This page measures internal efficiency and capacity, such as room occupancy, bed utilization, service load, and operational throughput.

![Hospital Page](https://github.com/sibashish9040/Hospital-Dashboard/blob/main/docs/Hospital_page.png)

### 4.6 Financial Analysis Page
This page focuses on the financial health of the hospital, covering revenue, bills, costs, operational expenditures, and maybe departmental spend analysis.

![Finance Page](https://github.com/sibashish9040/Hospital-Dashboard/blob/main/docs/Finance_page.png)

---

## 5. Tools and Technologies Used

This project uses a combination of data analytics and reporting tools:

- Microsoft Power BI
- Microsoft Excel
- SQL (for relational data handling and query logic)
- DAX (Data Analysis Expressions)
- Data modeling concepts including star schema design
- Business intelligence visualization best practices

### Why these tools?

- Power BI is used for building the interactive dashboard and business visuals.
- Excel files are used as the raw source data.
- SQL helps structure and query relational data logic.
- DAX is used to create custom measures and calculated fields.
- Data modeling ensures clean source-to-report relationships and consistent metrics.

---

## 6. Repository Structure

```text
Hospital-Dashboard-main/
├── README.md
├── dashboard/
│   └── Hospital_dashboard.pbix
├── datasets/
│   ├── Appointment.xlsx
│   ├── Beds.xlsx
│   ├── Department.xlsx
│   ├── Doctor.xlsx
│   ├── Hospital Bills.xlsx
│   ├── Medical Stock.xlsx
│   ├── Medical Tests.xlsx
│   ├── Patient_Tests.xlsx
│   ├── Rooms.xlsx
│   ├── Satisfaction Score.xlsx
│   ├── Staff.xlsx
│   ├── Supplier.xlsx
│   ├── Surgery.xlsx
│   ├── medicine_patient.xlsx
│   ├── patient.xlsx
│   └── ...
├── docs/
│   ├── Home_page.png
│   ├── overview_page.png
│   ├── patinet_page.png
│   ├── Doctor_page.png
│   ├── Hospital_page.png
│   └── Finance_page.png
└── ...
```

### File explanations

- `dashboard/Hospital_dashboard.pbix`  
  The main Power BI report file. This is the actual dashboard project that can be opened in Power BI Desktop.

- `datasets/`  
  Contains Excel files used as the source data for the report. These files represent various hospital datasets such as patient records, doctor information, appointment records, finance data, and operational metrics.

- `docs/`  
  Contains screenshots of the report pages to help users understand the dashboard without opening Power BI.

- `README.md`  
  Documentation for the project, including overview, usage instructions, and setup guidance.

---

## 7. Data Sources Included

The dataset folder contains multiple Excel files covering different hospital operational areas. Some of the major sample datasets include:

- `Appointment.xlsx` — appointment scheduling and visit patterns
- `Beds.xlsx` — bed occupancy and capacity information
- `Department.xlsx` — department-wise details and categories
- `Doctor.xlsx` — doctor records and department mapping
- `Hospital Bills.xlsx` — financial billing data
- `Medical Stock.xlsx` — medicine and inventory tracking
- `Medical Tests.xlsx` — test-related records
- `Patient_Tests.xlsx` — patient testing information
- `Rooms.xlsx` — room availability and utilization
- `Satisfaction Score.xlsx` — patient/service satisfaction metrics
- `Staff.xlsx` — staff and workforce information
- `Supplier.xlsx` — hospital supplier or vendor data
- `Surgery.xlsx` — surgical procedures and case data
- `patient.xlsx` — patient master data
- `medicine_patient.xlsx` — medication and patient-linked data

These files together model a realistic hospital ecosystem and provide enough detail to generate meaningful operational and financial insights.

---

## 8. Business Questions the Dashboard Helps Answer

This dashboard is designed to answer questions like:

- How many patients are being served across departments?
- Which departments have the highest patient volume?
- Are beds and rooms being utilized efficiently?
- How long are patients waiting or being scheduled?
- Which doctors or departments are handling the most cases?
- What is the financial performance of the hospital?
- Which services or departments contribute most to revenue and costs?
- Are there recurring operational issues in patient flow, room allocation, or staff utilization?
- How healthy is the hospital’s operational performance over time?

These kinds of questions are common in hospital management and can support better planning and decision-making.

---

## 9. How to Use This Project

### Prerequisites

To work with this project, you need:

- Microsoft Power BI Desktop installed on your machine
- Microsoft Excel (for opening the dataset files)
- Access to the repository files
- Optional: Power BI Service for publishing and sharing a report

### Step-by-step guide

1. Clone or download this repository.
2. Open the `dashboard` folder.
3. Launch `Hospital_dashboard.pbix` in Power BI Desktop.
4. Ensure the source Excel files in the `datasets` folder remain in the same relative location as expected by the report.
5. If Power BI asks for a file location or data source path, point it to the correct directory containing the Excel files.
6. Refresh data if needed.
7. Interact with filters, slicers, and visuals to explore the report.
8. Use the dashboard for analysis, presentation, or extension into a real hospital use case.

### Important note about data paths

The dashboard may be configured to load files from a specific local folder path. If you move the project or the data files, Power BI may prompt for a new path. In that case:

- locate the dataset files in `datasets/`
- update the file path in Power BI's data source settings
- refresh the report

---

## 10. Running and Publishing the Report

### Open in Power BI Desktop

You can open the `.pbix` file directly:

```text
dashboard/Hospital_dashboard.pbix
```

### Publish to Power BI service

If you want to share it with stakeholders:

1. Open the `.pbix` file in Power BI Desktop.
2. Sign in to your Power BI account.
3. Click the `Publish` button.
4. Select the workspace where you want the report to appear.
5. Share the dashboard with users or teams.

This makes it easy to distribute operational dashboards across management and reporting teams.

---

## 11. Suggested Use Cases

This project can be adapted for many real-world scenarios, including:

- Hospital administrative reporting
- Department-wise performance monitoring
- Revenue and billing trend analysis
- Capacity planning and bed utilization review
- Patient satisfaction monitoring
- Staffing and resource optimization
- Clinical operations dashboards
- Healthcare business intelligence projects

---

## 12. Real-World Business Value

The dashboard offers value by turning raw hospital data into readable trends and actionable insight. Instead of spending hours manually reviewing multiple spreadsheets, managers can use the dashboard to:

- identify performance gaps quickly
- compare departments and facilities
- understand utilization and capacity
- detect cost drivers
- improve service quality
- support strategic planning

This is especially useful in sectors where operational efficiency and patient outcomes are critical.

---

## 13. Limitations and Notes

This is a sample portfolio project and uses representative healthcare data. It should not be treated as production patient-data reporting without validation and privacy review.

### Important considerations

- The data is sample-based and not tied to a real hospital system.
- Real-world healthcare reporting should comply with patient privacy regulations.
- Production environments should include data governance, access control, and secure storage practices.
- Data quality checks should be performed before using the dashboard in live operational decisions.

---

## 14. Future Enhancements

This project can be expanded in many ways, for example:

- add live data integration with SQL or cloud storage
- include predictive analytics for patient volume and demand forecasting
- implement row-level security for different user roles
- add more detailed patient outcome and treatment analytics
- connect with healthcare APIs or electronic health record systems
- add mobile-friendly viewing and executive summaries
- include drill-through pages for department-level details

---

## 15. Conclusion

The Hospital Analytics Dashboard is a practical example of how Power BI can transform healthcare data into a readable, interactive, and decision-oriented visualization. It demonstrates how hospital operations, patient information, staffing, and financial performance can be viewed together in a single report.

This repository is useful for:

- learning Power BI dashboard design
- understanding healthcare data storytelling
- exploring sample hospital analytics
- building similar dashboards for real organizations

Whether you are a beginner learning Power BI or a business analyst exploring healthcare insights, this project provides a strong foundation for building meaningful operational dashboards.

---

## 16. Quick Summary

- Project type: Power BI dashboard
- Main file: `dashboard/Hospital_dashboard.pbix`
- Data source: Excel files in `datasets/`
- Report pages: Home, Overview, Patient Insights, Doctor Information, Hospital Performance, Financial Analysis
- Use case: hospital performance and healthcare analytics
- Best for: business intelligence, healthcare analytics, dashboard design learning

---

## 17. Contact and Contribution

This repository is a sample dashboard project and can be extended or customized for specific hospital reporting needs.

If you want to improve or adapt the dashboard:

- add more datasets
- refine DAX calculations
- improve UX and visual design
- add more hospital KPIs
- customize for your organization’s specific workflow

---

> Note: This README is written to make the project understandable for both technical and non-technical users. If you are using this repository for a learning or portfolio project, you can also add your own screenshots, business glossary, or a section describing your design decisions.

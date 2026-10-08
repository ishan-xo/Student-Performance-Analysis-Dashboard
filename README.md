# Student Academic Performance & Risk Mitigation Dashboard

An enterprise-grade Power BI end-to-end analytics solution transforming raw academic records into actionable institutional intelligence. This repository covers the complete pipeline: data extraction, anomaly resolution in Power Query, star-schema data modeling, custom DAX metrics, and a 3-tier executive dashboard.

---

## 📌 Repository Architecture

data/
│   ├── student_marks.csv               # Raw source data with real-world anomalies
│   └── student_marks_upgraded.csv      # Cleansed dataset export
docs/
│   ├── Power_BI_Teammate_Playbook.pdf  # Comprehensive ETL & modeling playbook
│   └── Student Performance Analysis Dashboard.pdf  # Full multi-page report export
images/
│   ├── slide 3 Dataset Overview.png    # Data pipeline & schema visual
│   ├── slide 5.png                     # Page 1: Student Overview
│   ├── slide 6.png                     # Page 2: Performance Analysis
│   └── slide 7.png                     # Page 3: Attendance & At-Risk Analysis
├── Student_Performance_Dashboard.pbix  # Production Power BI report file
└── README.md

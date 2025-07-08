# 🖥️ IT Support SLA Tracker

This project simulates a small business IT support system that tracks assets and support tickets, monitors SLA compliance, and builds an Excel dashboard to visualize performance.

---

## 🚀 What it does
✅ **Reads ticket data** from CSV files  
✅ **Calculates days open** for each ticket and flags tickets overdue (> 3 days SLA)  
✅ **Outputs two updated files:**
- `tickets_updated.csv` → all tickets, with DaysOpen and Overdue flags
- `overdue_tickets.csv` → tickets violating SLA

✅ **Generates an Excel dashboard** with pivot tables & charts to visualize:
- Ticket priorities
- Tech workloads
- SLA compliance (on-time vs overdue)

---

## 🛠️ Tech stack
- Python (pandas, numpy, datetime)
- Excel (pivot tables, formatting)
- Git & VS Code

---

## 📁 Project structure

IT-SLA-Tracker/
├── assets/
│ └── assets.csv
├── tickets/
│ ├── tickets.csv
│ ├── tickets_updated.csv
│ └── overdue_tickets.csv
├── dashboards/
│ └── IT_Support_Data.xlsx
├── scripts/
│ └── sla_report.py
└── README.md

## ⚡ How to run
```bash
python scripts/sla_report.py

##💡 Why I built this
To practice building real IT support workflows — automating SLA tracking, managing data in Python, and visualizing it in Excel. It’s a practical project for anyone pursuing helpdesk, IT operations, or data-driven support roles.

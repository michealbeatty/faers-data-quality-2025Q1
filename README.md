# FAERS Q1 2025: Systemic Failures in Adverse Event Data Reporting

## Summary

This repository contains an independent analysis of the FDA’s **FAERS** (Federal Adverse Event Reporting System) data for **Q1 2025**, uncovering **significant gaps and anomalies** in how drug safety data is reported by manufacturers.

### 🔍 Key Findings:
- **17%** of all reports are missing critical demographic fields: **age, sex, and/or weight**
- Just **4 pharmaceutical companies** — Celltrion, Sunovion, Lupin, and Alexion — are responsible for **27.8%** of those missing reports
- Records include **impossible values**, such as:
  - An event date listed as **year 1025 AD**
  - A **19-day-old infant** weighing **3,912 kg (8,620 lbs)**
  - Invalid report codes like `5DAY` and `30DAY`

## ⚠Why This Matters

FAERS is the FDA’s primary tool for **detecting safety signals** in post-market drugs. When manufacturers submit incomplete or nonsensical data:
- Dangerous side effects can go unnoticed
- Patient populations (e.g. infants, women) may be underrepresented or excluded
- Oversight becomes unreliable

This analysis raises concerns about the **FDA’s enforcement of data reporting standards** and the **integrity of its most relied-upon safety dataset**.

---

## Files

- `ffaers_2025Q1.ipynb` — Full Jupyter notebook with methodology, analysis, and code
- `/images/` — Shareable visualizations (see below)
- `/data/README.md` — How to download raw FDA data

---

## Visualizations

- ![Pie Chart: 4 Companies](images/missing_data_pie.png)
- ![Bar Chart: Top 4 Offenders](/images/top_4_offenders.png)

---

## Reproducibility

All analysis is based on **publicly available FAERS data**:  
[https://fis.fda.gov/extensions/FPD-QDE-FAERS/FPD-QDE-FAERS.html](https://fis.fda.gov/extensions/FPD-QDE-FAERS/FPD-QDE-FAERS.html)

Code is fully documented and reproducible.

---

## Author

**Micheal Beatty**  
Chicago-based data analyst and civic tech researcher  
[LinkedIn](https://linkedin.com/in/mwbeatty)

---

### Press / Researchers

If you’re reporting on drug safety, FDA oversight, or data quality issues in pharmacovigilance, feel free to reference or contact.

> **Contact:** mikelbt@gmail.com  
> **Please cite this repo if using in reporting or academic work.**

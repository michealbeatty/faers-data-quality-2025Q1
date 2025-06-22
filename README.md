# FAERS 2025Q1: Systemic Data Quality Failures in Adverse Event Reporting

## Overview

This project analyzes the FDA’s FAERS database for Q1 2025, uncovering significant failures in basic demographic reporting. The dataset, intended for post-market drug safety surveillance, contains systemic omissions and anomalies that compromise signal detection and regulatory oversight.

## Key Findings

- **17%** of all reports lack basic patient demographics: age, sex, and weight.
- **7 companies** exceed the threshold for major non-compliance (3,500+ reports, >50% missing).
- **3 companies** submitted over 5,000 reports each, with nearly all lacking demographics.
- Implausible records include:
  - **A 19-day-old infant** listed as weighing **3,912 kg**.
  - Event dates from the year **1025 AD** to **2444 AD**.
  - Misused report types like `5DAY` and `30DAY`.

## Why It Matters

FAERS is a primary tool for identifying post-market drug risks. When manufacturers fail to report who was affected — or when, or how — the entire system breaks down. These omissions represent more than clerical errors; they are a threat to public health.

## Files

- `ffaers_2025Q1.ipynb`: Full analysis notebook.
- `/images/`: Visual assets from the report.
- `/data/README.md`: How to download the raw FDA dataset.

## Visuals

### Compliance Spectrum
![Compliance Spectrum](/images/demographic_reporting_compliance_spectrum.png)

### Age Group Confusion Matrix
![Confusion Matrix](/images/age_group_confusion_matrix.png)

### Major Offender Breakdown
![Pie Chart](/images/revised_major_offenders_pie.png)

## Reproducibility

All code is fully reproducible using public FDA data:  
[https://fis.fda.gov/extensions/FPD-QDE-FAERS/FPD-QDE-FAERS.html](https://fis.fda.gov/extensions/FPD-QDE-FAERS/FPD-QDE-FAERS.html)

## Author

Micheal Beatty  
[LinkedIn](https://linkedin.com/in/mwbeatty)  
Chicago-based data analyst, software engineer, and civic tech advocate.

---

**License:** MIT. Feel free to reuse with attribution.
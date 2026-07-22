# Dataset Documentation

## Overview

This folder contains the datasets used in the HR Attrition Analytics Dashboard project.

The project follows a standard analytics workflow by separating the original dataset from the processed dataset used for analysis and dashboard development.

---

## Dataset Structure

```
dataset/
│
├── raw/
│   └── employee_attrition_raw.csv
│
├── processed/
│   └── employee_attrition_cleaned.csv
```

---

## Raw Dataset

**File**

employee_attrition_raw.csv

**Description**

This file contains the original HR dataset before any cleaning or transformation.

It represents the starting point of the analysis.

---

## Processed Dataset

**File**

employee_attrition_cleaned.csv

**Description**

This dataset was prepared for analysis after performing data validation and cleaning.

Cleaning activities included:

- Data quality validation
- Duplicate verification
- Missing value verification
- Standardized formatting
- Preparation for PivotTables and dashboard analysis

---

## Project Statistics

| Metric | Value |
|---------|------:|
| Employees | 1,468 |
| Variables | 35 |
| Industry | Human Resources |
| Target Variable | Attrition |

---

## Purpose

These datasets are provided to improve transparency and allow the analysis to be reproduced.

The processed dataset was used to build all PivotTables, KPIs, charts, and the executive dashboard included in this repository.
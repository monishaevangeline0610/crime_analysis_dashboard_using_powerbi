# Crime Analysis Dashboard (Power BI)

An interactive Power BI dashboard that analyzes crime data across selected Indian states (2014–2025). This repository contains the Power BI report (.pbix), the source dataset (CSV), and preview images used in the README.

## Contents
- Dashboard/India Crime Analysis.pbix  — Power BI report file (open with Power BI Desktop)
- Dataset/Crime Dataset.csv         — Cleaned dataset used for the report
- images/                          — Dashboard preview images
- README.md                         — This file

## About the dataset
The dataset includes the following columns (example):
- State, City, Year
- Crime Category, Crime Type
- Victim Gender, Victim Age Group
- Case Status, Chargesheet Status

Data cleaning steps applied:
- Duplicate removal, missing-value handling, type correction
- Calculated columns and DAX measures for KPIs

## How to use
Prerequisite: Power BI Desktop (latest stable recommended).
1. Open `Dashboard/India Crime Analysis.pbix` in Power BI Desktop.
2. If asked, update data source to point to `Dataset/Crime Dataset.csv` and refresh.
3. Interact with slicers (Year, City, State) to explore the visuals.

## Notes & recommendations
- The .pbix file may be large; avoid committing large edited PBIX files when updating visuals.
- If the dataset contains sensitive information, remove or anonymize PII before sharing.

## Contributing
Pull requests and issues are welcome. For major changes, please open an issue first to discuss proposed changes.

## Contact
Monisha Evangeline — (add preferred contact email or link)

## License
No license file is included in this repository (removed per request). If you want a license added, please indicate which one (e.g., MIT, Apache-2.0).

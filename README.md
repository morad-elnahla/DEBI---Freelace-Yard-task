# 📄 DEBI Freelance Yard Task

This project processes the provided Excel file and generates three types of outputs automatically:

---

## 📊 1. Generated Charts (PNG)

The system analyzed the Excel data and produced the following visualizations:

- **accessory_pairings.png**  
  - Shows the top accessory/apparel pairings by count.
  - Extracted by grouping category + pairing columns.

- **avg_bundled_revenue_weekday.png**  
  - Shows the average bundled revenue grouped by weekday.
  - Weekday extracted either directly from a column or from dates.

- **average_roas.png**  
  - ROAS chart was skipped because the Excel file did not contain:
    - A ROAS column  
    - Or revenue+cost columns with valid names to calculate ROAS  

---

## 📑 2. Generated PDF Report

Created automatically at:

`freelance_report_from_excel.pdf`

The PDF includes:

- Title + metadata  
- Accessory pairings chart + table  
- Weekday revenue chart + table  
- (No ROAS section because data not found)

Everything was formatted into a clean, structured PDF summary.

---

## 📓 3. Generated Jupyter Notebook

Created at:

`generate_report_from_excel.ipynb`

This notebook contains:

- Excel loading  
- Column detection  
- Data grouping  
- Chart generation  
- PDF exporting  
- All steps used to recreate the output files  

---

## 📂 Input File Used

`01JTE8DRAZV3A8WT69HYANMN8W.xlsx`

This file was the only data source used for all generated outputs.

---

## ✅ Final Output Files

- accessory_pairings.png  
- avg_bundled_revenue_weekday.png  
- freelance_report_from_excel.pdf  
- generate_report_from_excel.ipynb  
- (ROAS chart missing due to missing ROAS/Revenue/Cost data)


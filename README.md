# Joint and Interactive Associations of Depression and Frailty with Mortality in Cancer Survivors

This repository contains the statistical code used for the analysis presented in the manuscript:

**"Joint and Interactive Associations of Depression and Frailty with Mortality in Cancer Survivors"**

---

## 📊 Data Source

The data used in this study are publicly available from the **National Health Interview Survey (NHIS)**:

- NHIS data: https://www.cdc.gov/nchs/nhis.htm  
- NHIS Linked Mortality Files: https://www.cdc.gov/nchs/data-linkage/mortality.htm  

Access to the linked mortality data may require completion of standard data use procedures.

⚠️ Due to data use agreements, the raw data and processed analytical dataset cannot be shared in this repository.

---

## 📁 Repository Structure

- `data_preparation/`  
  Scripts for cleaning NHIS data and constructing study variables (e.g., depression, FRAIL scale)

- `analysis/`  
  Scripts for statistical analyses, including survey-weighted Cox proportional hazards models

- `tables_figures/`  
  Code for generating tables and Kaplan–Meier curves

---

## 🔁 Reproducibility

The analyses can be reproduced by:

1. Downloading NHIS public-use data and Linked Mortality Files  
2. Following the data preparation scripts to construct variables  
3. Running the analysis scripts in sequence  

All key analytic steps, including variable definitions and model specifications, are implemented in the provided code.

---

## 💻 Software

Analyses were conducted using:

- SAS 9.4  
- R 4.3.1  

Required R packages are listed within the scripts.

---

## 📌 Notes

- Depression was defined based on self-reported physician diagnosis  
- Frailty was assessed using the FRAIL scale  
- Survey weights, strata, and primary sampling units were incorporated in all analyses  

---

## 📬 Contact

For questions regarding the code or analysis, please contact:

Hongyin Zhou  
Email: 786438015@qq.com

---

## 📄 License

This repository is provided for academic and research purposes only. Please cite the original manuscript when using this code.

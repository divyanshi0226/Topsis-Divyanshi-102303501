# TOPSIS Fund Ranking Program

**Author:** Divyanshi  
**Roll No:** 102303501  
**Course:** Predictive Analytics using Statistics  
**Method Used:** TOPSIS (Multi-Criteria Decision Making)

---

## Overview

This project implements the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)**
method to rank multiple investment funds based on several quantitative performance parameters.

TOPSIS is a widely used multi-criteria decision-making (MCDM) technique that evaluates alternatives
based on their relative distance from the ideal best and ideal worst solutions.

---

## Description

The program applies the TOPSIS methodology to evaluate and rank investment funds using the given dataset.

The following steps are performed:

- Construction of the decision matrix from input data
- Normalization of criteria values using vector normalization
- Assignment of equal weights to all criteria
- Identification of ideal best (V⁺) and ideal worst (V⁻) solutions
- Calculation of Euclidean distances from ideal solutions
- Computation of TOPSIS score
- Ranking of funds based on the TOPSIS score

---

## Dataset

- The dataset consists of **8 funds (M1–M8)** evaluated using **5 parameters (P1–P5)**
- The data was originally provided in Excel format
- All criteria are assumed to be **benefit-type criteria**
- No missing or non-numeric values are present

---

## File Structure

- `TOPSIS_Fund_Selection.ipynb` – Jupyter / Google Colab notebook containing the full implementation  
- `TOPSIS_Fund_Ranking.csv` – Output file containing TOPSIS scores and final ranks  
- `README.md` – Project documentation  

---

## Requirements

- Python 3.x
- pandas
- numpy

Install required libraries using:

```bash
pip install pandas numpy

The approach provides an objective and systematic ranking of alternatives based on multiple criteria,
making it suitable for decision-making problems in finance and management.



**Author:** Divyanshi  
**Roll NO.** 102303501
**Course:** Predictive Analytics using Statistics
**Method Used:** TOPSIS (MCDM)


# TOPSIS Fund Ranking Program

A Python-based implementation of the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method to rank multiple funds based on several performance parameters.

## Description

TOPSIS is a multi-criteria decision-making (MCDM) technique that ranks alternatives based on their
distance from the ideal best and ideal worst solutions.

This project applies the TOPSIS methodology to evaluate and rank investment funds using given
quantitative parameters.

The program performs the following steps:

- Constructs a decision matrix from the input data
- Normalizes the criteria values using vector normalization
- Applies equal weights to all criteria
- Determines the ideal best (V⁺) and ideal worst (V⁻) solutions
- Calculates Euclidean distance from ideal best and worst
- Computes the TOPSIS score
- Ranks the funds based on the TOPSIS score

---

## Dataset

- Input data consists of **8 funds (M1–M8)** evaluated on **5 parameters (P1–P5)**
- The dataset was originally provided in Excel format
- All criteria are assumed to be **benefit-type criteria**
- No missing or non-numeric values are present

---

## File Structure

- TOPSIS_Fund_Selection.ipynb  
- TOPSIS_Fund_Ranking.csv  
- README.md  


## Requirements

- Python 3.x
- pandas
- numpy

Install required libraries using:

pip install pandas numpy


---

## How to Run

1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Upload the dataset if required
3. Run all cells sequentially
4. View the final ranking in the notebook and generated CSV file

---

## Output

The final output includes:

- TOPSIS score for each fund
- Rank of each fund (higher score indicates better performance)

---


## Assumptions

- All criteria are treated as benefit-type criteria
- Equal weights are assigned to all parameters
- Higher TOPSIS score indicates better fund performance


## Conclusion

This project demonstrates the application of the TOPSIS method for fund evaluation and selection.
The approach provides an objective and systematic ranking of alternatives based on multiple criteria,
making it suitable for decision-making problems in finance and management.

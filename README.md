# Analyzing Death Age Differences: Right-Handers vs Left-Handers

**A MedTourEasy Data Analytics Traineeship Project**

## Overview
This project uses Bayesian statistics to investigate the claim that 
left-handers die younger than right-handers. Using age distribution 
data from a 1986 National Geographic survey and CDC mortality data, 
the analysis reveals that the apparent age gap is a **statistical 
artifact** — not a biological phenomenon.

## Key Finding
| Study Year | LH Avg Age | RH Avg Age | Gap |
|------------|------------|------------|-----|
| 1990       | 68.3 yrs   | 72.7 yrs   | 4.4 yrs |
| 2018       | ~72.0 yrs  | ~72.0 yrs  | 0.0 yrs |

The gap disappears over time, confirming it is a **cohort effect** 
caused by the historical suppression of left-handedness — not 
early death.

## Tools & Method
- **Language:** Python (pandas, numpy, matplotlib)
- **Method:** Bayes' Theorem — P(A | Handedness) = P(LH | A) × P(A) / P(LH)
- **Datasets:** National Geographic Survey 1986 · CDC Death Distribution 1999

## Files
| File | Description |
|------|-------------|
| `lefthandedness_analysis.ipynb` | Full annotated Jupyter notebook |
| `lefthandedness_report.pdf` | Presentation-style project report |
| `lefthandedness_report.pdf` | Presentation-style project report |

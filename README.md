# Cookie Cats: A/B Testing & Retention Analysis

## Project Overview
This project analyzes the impact of moving the first gate in the mobile game **Cookie Cats** from level 30 to level 40. The goal is to determine which gate placement results in higher player retention.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scipy
* **Techniques:** Bootstrapping, Shapiro-Wilk Test, Mann-Whitney U Test

## Key Findings
1. **Retention:** Moving the gate to level 40 **significantly decreases** 7-day retention.
2. **Engagement:** There is **no statistically significant difference** in the number of game rounds played between the two versions.

## Conclusion
Based on the analysis (99.8% confidence), we recommend **keeping the gate at Level 30** to maximize player retention.

## Files
* `AB_Testing_Analysis.ipynb`: The complete analysis code and visualizations.
* `cookie_cats.csv`: The dataset used (Source: Kaggle).

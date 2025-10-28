## Overview
As an intermediate-beginner in data science, I leveraged AI assistance, permitted by the course, to learn coding trendlines in Pandas, enhancing my analysis 
with linear regression to quantify cost trends. This resourceful approach reflects my ability to adapt quickly, bring a fresh perspective, and deliver 
impactful results by creatively integrating modern tools like AI into my workflow. 

The project is a short analysis of medical insurance data to uncover factors potentially driving charges. I completed it as part of Codecademy's Data Science 
curriculum. I used Python, Pandas, Matplotlib, and NumPy, I explored relationships between age, BMI, smoking status, and other variables to identify key 
cost drivers. The analysis includes statistical summaries, scatter plots with trendlines, and insights into patterns like the significant impact of 
smoking on charges. 

I really enjoyed the freedom and creativity that came with this project, and am excited for more. 

## Objectives
- Import and explore the dataset (`insurance.csv`) from Kaggle.
- Perform statistical analyses (e.g., correlations, group means) to identify cost trends.
- Visualize relationships (e.g., age vs. charges, BMI vs. charges) with scatter plots and trendlines.
- Document findings and discuss potential biases (e.g., BMI limitations) for a comprehensive analysis

## Key Findings
- **Age and Charges**: Age has a moderate correlation (0.30) with charges, showing three distinct cost cohorts increasing with age.
- **Smoking Impact**: Smokers have significantly higher charges (~$32,050 vs. ~$8,434 for non-smokers), dominating high-cost cohorts (> $30,000).
- **BMI Role**: BMI has a weak correlation (0.20) with charges, but high BMI (> 30) combined with smoking sharply increases costs.
- **Trendlines**: Non-smokers show a steadier cost increase (~$267/year), while smokers’ costs are more variable (~$326/year).

## Files
- `DataScience_Insurance_CodeAcademy_Project.ipynb`: Jupyter Notebook with all code, visualizations, and markdown observations.
- `insurance.csv`: Dataset (optional, included for reproducibility).

## How to Run
1. Clone this repository: `git clone https://github.com/yourusername/medical-insurance-analysis.git`
2. Ensure Python 3, Pandas, Matplotlib, and NumPy are installed (e.g., via `pip install pandas matplotlib numpy`).
3. Open `DataScience_Insurance_CodeAcademy_Project.ipynb` in Jupyter Notebook.
4. Run all cells to view analyses and visualizations.

## Tools Used
- Python (Pandas, Matplotlib, NumPy)
- Jupyter Notebook (conda env: `udemy_env`)
- Dataset: [Kaggle Medical Insurance Costs](https://www.kaggle.com/datasets/mirichoi0218/insurance)

## About
Developed by Spencer Wilkins as a portfolio project to demonstrate data analysis, Python programming, critical thinking skills, resourcefulness and curiosity. 
Feedback welcome.

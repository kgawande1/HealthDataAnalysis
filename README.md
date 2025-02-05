# Health Data Analysis Project

## Overview
This project examines the impact of smoking, alcohol consumption, and diet quality on key health metrics, such as sleep hours and overall health scores. Using statistical analysis and visualizations, it identifies significant patterns in health-related behaviors.  

## Research Questions  

### 1. Does Smoking Affect Sleep Quality?  
- A box plot analysis compares sleep duration between smokers and non-smokers.  
- Findings indicate that smokers experience greater variability in sleep hours, with more outliers, suggesting that smoking negatively affects sleep consistency and quality.  

### 2. Which Has a Greater Impact on Health: Alcohol Consumption or Diet Quality?  
- A correlation analysis measures the relationship between these factors and overall health scores.  
- Diet quality shows a **stronger positive correlation (0.68)** with health scores than alcohol consumption, which has a **weak negative correlation (-0.14)**. This suggests that improving diet quality has a greater impact on health than reducing alcohol intake.  

### 3. How Does Smoking Affect Health Scores Across Different Age Groups?  
- A grouped bar graph compares health scores of smokers and non-smokers across different age groups.  
- Health scores decline with age, but the gap between smokers and non-smokers increases in older groups, indicating that smoking accelerates health deterioration over time.  

## Project Files  
- **`HealthDataAnalysis - Analyzed Document.pdf`** – Summary of findings, statistical analysis, and conclusions.  
- **`HealthDataAnalysisPlots.ipynb`** – Jupyter Notebook containing data analysis and visualization code.  
- **`health_data.csv`** – Dataset with variables such as age, BMI, diet quality, sleep hours, and health scores.  

## Summary Statistics  
| Variable         | Mean  | Std Dev | Min  | Median | Max  |  
|-----------------|-------|---------|------|--------|------|  
| Age             | 40.23 | 11.75   | 1.10 | 40.30  | 86.23 |  
| BMI             | 25.35 | 4.99    | 10.3 | 25.31  | 40.97 |  
| Diet Quality    | 69.93 | 14.07   | 19.91| 69.97  | 110.27 |  
| Sleep Hours     | 6.97  | 1.52    | 2.43 | 6.99   | 11.64 |  
| Health Score    | 85.50 | 13.64   | 29.11| 87.54  | 100.00 |  

## How to Use  
1. Open `HealthDataAnalysisPlots.ipynb` in Jupyter Notebook.  
2. Run all cells to generate the visualizations and statistical results.  
3. Review the findings in `HealthDataAnalysis - Analyzed Document.pdf`.  

## Dependencies  
Install required libraries using:  
```bash
pip install pandas matplotlib seaborn numpy
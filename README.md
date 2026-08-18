# EDA, Regression & Power BI Project

## Dataset
The uploaded file contains 32 rows and 5 columns:
`Duration`, `Date`, `Pulse`, `Maxpulse`, `Calories`.

## Important limitation
The assignment asks for a regression model to predict **Sales**, but the supplied dataset contains **no Sales/Revenue column**. It would be misleading to fabricate a Sales target. This project therefore:
1. Performs EDA on the supplied dataset.
2. Builds a baseline linear regression model for **Calories** (the available outcome).
3. Provides Power BI-ready data and a dashboard specification.
4. Documents the limitation and recommendations.

## Model result
- MAE: 47.794
- RMSE: 71.022
- R²: -3.511

## Files
- `data/data.csv` — original uploaded dataset
- `notebooks/EDA_Regression_Analysis.ipynb` — Python notebook
- `outputs/EDA_Regression_Report.xlsx` — Excel report
- `outputs/duration_vs_calories.png` — analysis chart
- `outputs/pulse_vs_calories.png` — analysis chart
- `powerbi/PowerBI_Data.xlsx` — Power BI-ready workbook
- `powerbi/POWER_BI_DASHBOARD_GUIDE.md` — dashboard build guide

## GitHub
Upload the whole project folder to a GitHub repository. The `.ipynb`, `.xlsx`, CSV, README, and dashboard guide are included.

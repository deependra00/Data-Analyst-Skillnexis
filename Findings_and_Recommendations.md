# Findings & Recommendations

## Findings
The supplied dataset has 32 records and 5 columns. It contains workout variables rather than sales variables: Duration, Date, Pulse, Maxpulse and Calories. There is 1 missing Date value and 2 missing Calories values.

The regression analysis uses Calories as the outcome because Sales is not present. The baseline linear regression achieved MAE 47.79, RMSE 71.02, and R² -3.511 on the held-out test set.

## Recommendations
1. If the actual assignment requires Sales prediction, provide a dataset containing Sales/Revenue as the target.
2. For the current dataset, use the Power BI dashboard to monitor workout duration, pulse, maximum pulse and calories.
3. Handle missing dates and calories before production reporting.
4. For a real sales model, compare linear regression with tree-based models and evaluate using a time-aware train/test split if the data is chronological.

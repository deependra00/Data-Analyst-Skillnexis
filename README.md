# Clean a Messy Dataset in Pandas

This project demonstrates practical **data cleaning and preprocessing using Python and Pandas**.

## Tasks Completed

1. Loaded the CSV dataset using Pandas.
2. Cleaned column names and whitespace.
3. Identified and removed duplicate records.
4. Handled missing values using median imputation for numeric columns and mode/`Unknown` for text columns.
5. Filtered rows using a data-driven numeric condition.
6. Created derived columns from the available dataset fields.
7. Exported the cleaned dataset as CSV.

## Dataset Summary

- Original shape: `32 rows × 5 columns`
- Duplicate rows removed: `1`
- Final shape: `31 rows × 7 columns`

## New Columns

- numeric_total = duration + pulse
- non_missing_count

## Filtering

Filtered out rows with no populated fields.

## Files

- `data.csv` — original uploaded dataset
- `cleaned_dataset.csv` — cleaned and filtered dataset
- `Clean_Messy_Dataset_Pandas.ipynb` — reproducible Jupyter Notebook
- `cleaning_summary.json` — cleaning statistics
- `README.md` — project documentation

## Tools

- Python
- Pandas
- Jupyter Notebook

## How to Run

```bash
pip install pandas jupyter
jupyter notebook
```

Open `Clean_Messy_Dataset_Pandas.ipynb` and run all cells.

**Project Type:** Data Analytics / Data Cleaning

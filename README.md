# Task-14-ETL-Mini-Pipeline-Python-Extract-Transform-Load
# Retail Sales ETL Project

## Extract
- Dataset loaded from Kaggle CSV into Google Colab
- Raw data stored without modification

## Transform
- Removed duplicate records
- Handled missing values
- Standardized column names and data types
- Created derived columns where required
- Split data into customers, products, and transactions tables

## Load
- Exported cleaned datasets as CSV files
- Files saved in output/ folder for downstream analytics

## Validation
- Record counts verified before and after transformations
- Ensured no unintended data loss

with open("/content/etl_project/README.md", "w") as f:
    f.write(readme_text)

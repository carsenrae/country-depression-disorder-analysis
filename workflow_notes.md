# Workflow Notes

1. Started with raw CSV:
   - `Mental health Depression disorder Data.csv`

2. Loaded raw data into DuckDB:
   - Table name: `mental_health_raw`

3. Cleaned the data in DuckDB:
   - Created `mental_health_clean`
   - Removed rows where `Year` could not be converted to an integer

4. Exported processed datasets:
   - `top10_avg_depression.csv`
   - `top3_depression_trend.csv`

5. Used Python/pandas/matplotlib to create:
   - `top10_avg_depression.png`
   - `depression_trends_top3.png`
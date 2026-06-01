# Sales Performance Dashboard

Retail sales dashboard focused on revenue, margin, regions, products, and sales rep performance.

## Business Questions

- Which regions and products drive revenue?
- Which sales reps are above or below target?
- Where is gross margin strongest?
- What trend should leadership watch next?

## Repository Structure

```text
data/                 Sample data for the case study
src/                  Python analysis workflow
sql/                  SQL queries for KPI extraction
reports/              Executive summary and recommendations
outputs/              Generated analysis outputs, ignored by git
requirements.txt      Python dependencies
```

## How To Run

```bash
pip install -r requirements.txt
python src/analysis.py
```

The script reads `data/sample_data.csv`, creates KPI summaries, and saves generated outputs in `outputs/`.

## Analyst Skills Demonstrated

- Cleaning and profiling a structured dataset
- Creating KPI summaries with Python
- Writing SQL-style business questions
- Translating metrics into executive recommendations
- Organizing a reproducible portfolio repository

## Next Improvements

- Replace the sample data with a larger public dataset
- Add an exploratory Jupyter notebook
- Build a dashboard in Power BI, Tableau, Looker Studio, or Streamlit
- Add data quality checks and metric definitions

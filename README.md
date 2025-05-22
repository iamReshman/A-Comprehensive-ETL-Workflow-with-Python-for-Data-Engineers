# A-Comprehensive-ETL-Workflow-with-Python-for-Data-Engineers
## 📌 Problem Statement
Extract data from various formats (CSV, JSON, XML), transform it by standardizing units, and load it into a structured format suitable for analysis and database ingestion.

## 🛠 Tools Used
- Python
- Pandas
- XML Parsing (`xml.etree.ElementTree`)
- Logging with `datetime`
- VSCode

## 🔁 Approach
1. Extract data from mixed-format files.
2. Transform units:
   - Height: Inches ➜ Meters
   - Weight: Pounds ➜ Kilograms
3. Load cleaned data into a CSV.
4. Log each step with timestamps.

## 📈 Insights
- Unified structure from heterogeneous sources.
- Standardized unit system allows downstream analysis.
- Logging ensures traceability and easy debugging.

## 📂 Output
- `transformed_data.csv`: Final unified dataset.
- `log_file.txt`: Execution log.

## ▶️ Run
```bash
python etl_pipeline.py

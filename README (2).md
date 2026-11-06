# BlinkIT Grocery Sales Analysis Dashboard

A dashboard built from 8,523 BlinkIT grocery item records. It is organised around four questions: how the business is performing, whether the data is reliable, what drives sales, and what management should do next.

Open `index.html` in a browser to view it (internet needed to load Chart.js).

## Files
- `index.html` – the finished dashboard
- `template.html` – page layout with a placeholder for the data
- `build.py` – reads the Excel file, cleans it and writes `index.html`
- `data/BlinkIT_Grocery_Data.xlsx` – source data

## Rebuild
```
pip install pandas openpyxl
python build.py
```

## Data notes
- Fat content had five spellings (Low Fat, LF, low fat, Regular, reg) and was combined into two.
- Item weight is missing for 1,463 rows and was left as missing, not filled in.
- The file has no currency or date, so sales are shown as plain numbers.

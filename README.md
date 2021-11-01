# nubank-finance-report

My personal finance report. To use it follow these steps:

[01] Download the csv containing your expenses from Nubank website and place it in the `/faturas` folder

[02] Run `01-edit-nubank-csv.ipynb` notebook (don't forget to set up the month in the format `YYYY-MM`) to adjust the csv to the categories you want. 
Sometimes Nubank mistakens the categories and you will have to adjust them for better analysis.

[03] Run `02-print-report.ipynb` notebook (don't forget to set up the month in the format `YYYY-MM` and your month's income in the dict).

## Chase Builds

Small Python tools for messy business data: spreadsheets, PDFs, customer lists and weekly reports.

Each tool is scored against generated test data where the right answer is known, and the score is written into its README by a script, not typed by hand. When a tool is not sure, it sends the value to a review sheet instead of guessing.

| Tool | What it does | Measured result |
|---|---|---|
| [pdf-to-excel](https://github.com/chasebuilds/pdf-to-excel) | Invoice PDFs to one Excel workbook, with a confidence score on every field | 3,600 of 3,600 fields correct on 400 invoices in 10 layouts |
| [excel-cleaner-pro](https://github.com/chasebuilds/excel-cleaner-pro) | Cleans messy CSV and Excel files and logs every change on an audit sheet | 5,615 of 5,627 fixable errors fixed, 611 of 611 unsafe values flagged |
| [data-merger](https://github.com/chasebuilds/data-merger) | Merges customer lists with different columns into one record per customer | 28,512 rows from 5 files with 0 false merges |
| [automated-reporting-system](https://github.com/chasebuilds/automated-reporting-system) | Raw weekly exports to a finished Excel report and HTML dashboard | 876 of 876 KPI values exact, 17 of 18 planted faults caught |
| [business-research-tool](https://github.com/chasebuilds/business-research-tool) | Company names to a research sheet where every fact has a source | 99.4% match precision on 300 test companies |
| [web-data-extractor](https://github.com/chasebuilds/web-data-extractor) | Public catalog pages to a checked spreadsheet, only where robots.txt allows | 360 of 360 field values correct on the test site |

All results are on synthetic data. Each repo has a `BENCHMARK.md` with the method and a `LIMITATIONS.md` that says what the tool does not handle.

[![PDF to Excel: an invoice PDF and the fields pulled from it](https://raw.githubusercontent.com/chasebuilds/pdf-to-excel/main/docs/preview.png)](https://github.com/chasebuilds/pdf-to-excel)

**Stack:** Python, pandas, openpyxl, pdfplumber, pytest. Every repo runs its tests and lint on each push.

Available for data cleanup, PDF extraction and report automation work through Upwork.

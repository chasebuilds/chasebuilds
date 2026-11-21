## Chase Builds

Small Python tools for messy business data: spreadsheets, PDFs, customer lists and weekly reports. Portfolio site: [chasebuilds.github.io](https://chasebuilds.github.io)

Each tool is scored against generated test data where the right answer is known, and the score is written into its README by a script, not typed by hand. When a tool is not sure, it sends the value to a review sheet instead of guessing.

| Tool | What it does | Measured result |
|---|---|---|
| [pdf-to-excel](https://github.com/chasebuilds/pdf-to-excel) | Invoice PDFs to one Excel workbook, with a confidence score on every field. Also runs as a FastAPI service in Docker | 3,600 of 3,600 fields correct on 400 invoices in 10 layouts |
| [excel-cleaner-pro](https://github.com/chasebuilds/excel-cleaner-pro) | Cleans messy CSV and Excel files and logs every change on an audit sheet. Includes a Streamlit app | 5,615 of 5,627 fixable errors fixed, 611 of 611 unsafe values flagged |
| [data-merger](https://github.com/chasebuilds/data-merger) | Merges customer lists with different columns into one record per customer. Exports to SQLite with example SQL | 28,512 rows from 5 files with 0 false merges |
| [automated-reporting-system](https://github.com/chasebuilds/automated-reporting-system) | Raw weekly exports to a finished Excel report and HTML dashboard. [Live demo](https://chasebuilds.github.io/automated-reporting-system/) rebuilt by GitHub Actions | 876 of 876 KPI values exact, 17 of 18 planted faults caught |
| [business-research-tool](https://github.com/chasebuilds/business-research-tool) | Company names to a research sheet where every fact has a source. Cached, rate-limited, works offline | 99.4% match precision on 300 test companies |
| [web-data-extractor](https://github.com/chasebuilds/web-data-extractor) | Public catalog pages to a checked spreadsheet, only where robots.txt allows. Async with per-host limits | 360 of 360 field values correct on the test site |
| [data-quality-checks](https://github.com/chasebuilds/data-quality-checks) | Declarative checks for CSV, Excel and Parquet files, compiled to DuckDB SQL, with an HTML and JSON report | 1,784 of 1,800 planted faults caught, 0 false alarms in 220 clean runs |
| [pdf-table-extractor](https://github.com/chasebuilds/pdf-table-extractor) | Tables from digital PDFs to clean Excel and CSV, stitched across pages, with a totals check on every table | 38,528 of 38,968 cells exact, 240 of 240 tables found |
| [address-normalizer](https://github.com/chasebuilds/address-normalizer) | Messy US mailing addresses to standardized, split fields, with duplicates grouped | 99.5% of cleaned rows fully right, 100% duplicate precision |
| [excel-to-sql](https://github.com/chasebuilds/excel-to-sql) | Load CSV and Excel files into SQL with type inference, key detection, upsert and a load report | 2,000 of 2,000 generated columns typed correctly, 500 of 500 bad rows rejected |
| [spreadsheet-diff](https://github.com/chasebuilds/spreadsheet-diff) | Compare two versions of a CSV or Excel file by key: added, removed and changed rows, cell by cell | 2,803 of 2,803 planted cell edits found in 20,000 rows, 0 false flags |
| [product-matcher](https://github.com/chasebuilds/product-matcher) | Match products between two lists by GTIN/SKU, units and fuzzy names, with a review sheet | 2,216 of 2,216 automatic matches correct |
| [json-to-tables](https://github.com/chasebuilds/json-to-tables) | Nested JSON and JSON Lines to tidy related tables in Excel, CSV or SQLite | 426,604 of 426,604 values placed exactly once with the right parent |
| [lead-list-qa](https://github.com/chasebuilds/lead-list-qa) | Offline checks for B2B contact lists: email and phone format, duplicates, role and free-mail addresses | 1,531 of 1,531 planted faults caught, 0 of 3,469 clean rows flagged |
| [excel-formula-auditor](https://github.com/chasebuilds/excel-formula-auditor) | Scan Excel workbooks for formula risks: errors, hard-coded numbers, inconsistent formulas, broken links | All 6 planted issue types caught, 0 false flags on 50 clean workbooks |
| [transaction-categorizer](https://github.com/chasebuilds/transaction-categorizer) | Categorize bank and card transactions with an editable rules file, flag duplicates, monthly summary | 5,100 seeded transactions categorized correctly, 100 of 100 duplicates found |
| [csv-combine-split](https://github.com/chasebuilds/csv-combine-split) | Combine a folder of CSV and Excel files with aligned columns, or split a big file | 100,000 of 100,000 rows out from 20 mixed files, every column aligned |

All results are on synthetic data. Each repo has a `BENCHMARK.md` with the method and a `LIMITATIONS.md` that says what the tool does not handle.

[![PDF to Excel: an invoice PDF and the fields pulled from it](https://raw.githubusercontent.com/chasebuilds/pdf-to-excel/main/docs/preview.png)](https://github.com/chasebuilds/pdf-to-excel)

**Stack:** Python, pandas, openpyxl, pdfplumber, DuckDB, SQLite, FastAPI, Pydantic, Streamlit, httpx, Docker, GitHub Actions. Every repo runs ruff, mypy and pytest with coverage on each push.

Available for data cleanup, PDF extraction and report automation work through Upwork.

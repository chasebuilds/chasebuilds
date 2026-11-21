## Hi, I'm Chase Builds 👋

I turn messy business data into clean, usable files: spreadsheets with duplicates and mixed formats, invoices stuck in PDFs, lists spread across several files, and weekly reports someone builds by hand.

**[See my work](https://chasebuilds.github.io)** · **[Hire me on Upwork](https://www.upwork.com/freelancers/~0107f20574d26eac0e)**

### What I can do for you

| You have | You get back |
|---|---|
| A messy Excel or CSV file | One clean file, plus a sheet listing every change I made and why |
| A pile of PDF invoices or statements | One Excel sheet with the data in rows and columns, totals checked |
| The same customers spread across several lists | One master list, duplicates merged, every row traceable to its source |
| A weekly report you build by hand | A one-command report and dashboard that refuses to run on bad data |

Anything I'm not sure about goes on a review sheet for you to check. Nothing is changed on a guess.

### Featured work

| | |
|---|---|
| [![PDF to Excel](https://raw.githubusercontent.com/chasebuilds/pdf-to-excel/main/docs/preview.png)](https://github.com/chasebuilds/pdf-to-excel) | [![Excel Cleaner Pro](https://raw.githubusercontent.com/chasebuilds/excel-cleaner-pro/main/docs/preview.png)](https://github.com/chasebuilds/excel-cleaner-pro) |
| **[pdf-to-excel](https://github.com/chasebuilds/pdf-to-excel)**: invoice PDFs to Excel. 3,600 of 3,600 fields correct on 400 test invoices. | **[excel-cleaner-pro](https://github.com/chasebuilds/excel-cleaner-pro)**: messy spreadsheets cleaned with a full audit trail. 5,615 of 5,627 planted errors fixed. |
| [![Data Merger](https://raw.githubusercontent.com/chasebuilds/data-merger/main/docs/preview.png)](https://github.com/chasebuilds/data-merger) | [![Automated Reporting](https://raw.githubusercontent.com/chasebuilds/automated-reporting-system/main/docs/preview.png)](https://chasebuilds.github.io/automated-reporting-system/) |
| **[data-merger](https://github.com/chasebuilds/data-merger)**: several customer lists into one. 28,512 rows merged with 0 false merges. | **[automated-reporting-system](https://github.com/chasebuilds/automated-reporting-system)**: weekly exports to a report and dashboard. [Live demo](https://chasebuilds.github.io/automated-reporting-system/). |

### How I work

- **Measured, not claimed.** Every tool is tested against generated data where the right answer is known, and the score is written by a script. Results are on synthetic data; each repo has a `BENCHMARK.md` and a `LIMITATIONS.md`.
- **Checkable.** You get an audit sheet of every change and a review sheet for anything uncertain.
- **Tested code.** Every repo runs linting, type checks and tests on each push.

**Skills:** Python · pandas · Excel (openpyxl) · SQL (SQLite, DuckDB) · PDF extraction (pdfplumber) · FastAPI · Streamlit · Docker · GitHub Actions · web data collection (robots.txt respected)

<details>
<summary><b>All 17 tools</b> (click to open)</summary>

| Tool | What it does | Measured result (synthetic data) |
|---|---|---|
| [pdf-to-excel](https://github.com/chasebuilds/pdf-to-excel) | Invoice PDFs to one Excel workbook, with a confidence score on every field. Also runs as a FastAPI service in Docker | 3,600 of 3,600 fields correct on 400 invoices in 10 layouts |
| [excel-cleaner-pro](https://github.com/chasebuilds/excel-cleaner-pro) | Cleans messy CSV and Excel files and logs every change. Includes a Streamlit app | 5,615 of 5,627 fixable errors fixed, 611 of 611 unsafe values flagged |
| [data-merger](https://github.com/chasebuilds/data-merger) | Merges customer lists with different columns into one record per customer. Exports to SQLite | 28,512 rows from 5 files with 0 false merges |
| [automated-reporting-system](https://github.com/chasebuilds/automated-reporting-system) | Raw weekly exports to an Excel report and HTML dashboard. [Live demo](https://chasebuilds.github.io/automated-reporting-system/) | 876 of 876 KPI values exact, 17 of 18 planted faults caught |
| [pdf-table-extractor](https://github.com/chasebuilds/pdf-table-extractor) | Tables from digital PDFs to Excel and CSV, stitched across pages, totals checked | 38,528 of 38,968 cells exact, 240 of 240 tables found |
| [data-quality-checks](https://github.com/chasebuilds/data-quality-checks) | Rules for CSV, Excel and Parquet files, run as DuckDB SQL, with an HTML report | 1,784 of 1,800 planted faults caught, 0 false alarms |
| [address-normalizer](https://github.com/chasebuilds/address-normalizer) | Messy US mailing addresses standardized and split, duplicates grouped | 99.5% of cleaned rows fully right, 100% duplicate precision |
| [spreadsheet-diff](https://github.com/chasebuilds/spreadsheet-diff) | Compare two versions of a spreadsheet, cell by cell | 2,803 of 2,803 planted edits found, 0 false flags |
| [product-matcher](https://github.com/chasebuilds/product-matcher) | Match products between two lists by SKU, units and fuzzy names | 2,216 of 2,216 automatic matches correct |
| [excel-to-sql](https://github.com/chasebuilds/excel-to-sql) | Load spreadsheets into SQL with type inference and a load report | 2,000 of 2,000 columns typed correctly |
| [json-to-tables](https://github.com/chasebuilds/json-to-tables) | Nested JSON to tidy related tables in Excel, CSV or SQLite | 426,604 of 426,604 values placed exactly once |
| [lead-list-qa](https://github.com/chasebuilds/lead-list-qa) | Offline checks for contact lists: formats, duplicates, role addresses | 1,531 of 1,531 planted faults caught |
| [excel-formula-auditor](https://github.com/chasebuilds/excel-formula-auditor) | Scan workbooks for formula errors, hard-coded numbers and broken links | All 6 planted issue types caught, 0 false flags |
| [transaction-categorizer](https://github.com/chasebuilds/transaction-categorizer) | Categorize bank transactions with editable rules, flag duplicates | 5,100 of 5,100 seeded transactions categorized |
| [csv-combine-split](https://github.com/chasebuilds/csv-combine-split) | Combine a folder of files with aligned columns, or split a big one | 100,000 of 100,000 rows out, columns aligned |
| [business-research-tool](https://github.com/chasebuilds/business-research-tool) | Company names to a research sheet where every fact has a source | 99.4% match precision on 300 test companies |
| [web-data-extractor](https://github.com/chasebuilds/web-data-extractor) | Public catalog pages to a checked spreadsheet, only where robots.txt allows | 360 of 360 field values correct |

</details>

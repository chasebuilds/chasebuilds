## Hi, I'm Chase Builds 👋

I build small, practical software for small businesses: clean spreadsheets, fast websites, dashboards, booking systems, automations and security checkups. Every project here is tested, documented, and many have a live demo you can click.

**[See my work](https://chasebuilds.github.io)** · **[Hire me on Upwork](https://www.upwork.com/freelancers/~0107f20574d26eac0e)**

### What I can do for you

<!--ROWS-->
| You have | You get back | See it |
|---|---|---|
| [A messy Excel or CSV file](#data-cleanup-and-pdfs) | One clean file, plus a sheet listing every change I made and why | [excel-cleaner-pro](https://github.com/chasebuilds/excel-cleaner-pro) |
| [Comps and value questions](#real-estate-and-appraisal) | A comps grid and value range with every adjustment shown, plus market trend and ratio checks | [Live demo](https://chasebuilds.github.io/comparable-sales-grid/) |
| [A pile of PDF invoices or statements](#data-cleanup-and-pdfs) | One Excel sheet with the data in rows and columns, totals checked | [pdf-to-excel](https://github.com/chasebuilds/pdf-to-excel) |
| [The same customers spread across several lists](#data-cleanup-and-pdfs) | One master list, duplicates merged, every row traceable to its source | [data-merger](https://github.com/chasebuilds/data-merger) |
| [A weekly report you build by hand](#apps-and-dashboards) | A one-command report and dashboard that refuses to run on bad data | [Live demo](https://chasebuilds.github.io/automated-reporting-system/) |
| [Sales numbers you can't see at a glance](#apps-and-dashboards) | A dashboard with key figures, trend charts, filters and CSV export | [Live demo](https://chasebuilds.github.io/react-analytics-dashboard/) |
| [Job tickets and invoices on paper](#apps-and-dashboards) | A phone app your crew can use offline: tickets, photos, signature, invoice | [Live demo](https://chasebuilds.github.io/field-service-pwa/) |
| [A business with no website, or an old one](#websites-and-design) | A fast one-page site that works on phones, with your hours, services and map | [Live demos](https://chasebuilds.github.io/local-business-site/) |
| [Bookings by phone and paper](#apis-and-automation) | A booking system that never double-books and handles time zones | [appointment-booking-api](https://github.com/chasebuilds/appointment-booking-api) |
| [Copy-paste work in Google Sheets](#apis-and-automation) | Automations for form cleanup, summary emails, invoices and reminders | [sheets-automations](https://github.com/chasebuilds/sheets-automations) |
| [A hillside tract you are thinking of buying](#maps-3d-and-land) | A 3D first look: buildable acres, a lot layout, cut and fill, flood zone and four exits priced | [Live demo](https://chasebuilds.github.io/land-feasibility-3d/) |
| [A worry that your site is not safe](#security-checkups) | A plain-English checkup of your site's public setup, with fixes in priority order | [Sample report](https://chasebuilds.github.io/site-security-check/) |
| [Questions buried in a stack of PDFs](#ai-with-local-models) | Answers with the file and page cited, from AI that runs on your own computer | [pdf-qa-local](https://github.com/chasebuilds/pdf-qa-local) |
<!--/ROWS-->

Anything I'm not sure about goes on a review sheet for you to check. Nothing is changed on a guess.

<!--GROUPS-->
### Data cleanup and PDFs

Messy spreadsheets, PDFs and customer lists turned into clean files, with every change logged.

<a href="https://github.com/chasebuilds/pdf-to-excel"><img src="https://raw.githubusercontent.com/chasebuilds/pdf-to-excel/main/docs/preview.png" alt="pdf-to-excel" width="560"></a>

- **[pdf-to-excel](https://github.com/chasebuilds/pdf-to-excel)** · Invoice PDFs to one Excel workbook, with a confidence score on every field. 3,600 of 3,600 fields correct on 400 invoices in 10 layouts.
- **[excel-cleaner-pro](https://github.com/chasebuilds/excel-cleaner-pro)** · Cleans messy CSV and Excel files and logs every change on an audit sheet. 5,615 of 5,627 fixable errors fixed, 611 of 611 unsafe values flagged.
- **[data-merger](https://github.com/chasebuilds/data-merger)** · Merges customer lists with different columns into one record per customer. 28,512 rows from 5 files with 0 false merges.
- **[small-business-county-study](https://github.com/chasebuilds/small-business-county-study)** · Small-business conditions in 31 Eastern Kentucky counties from free Census files, with charts and a written report rebuilt from one command. [Live demo](https://chasebuilds.github.io/small-business-county-study/).
- Plus 12 more in the full list below.

### Real estate and appraisal

Tools for appraisers, agents and assessors: comps, value models, cost and income approaches, ratio studies. These are analysis tools, not appraisals; a USPAP appraisal needs a licensed or certified appraiser.

<a href="https://chasebuilds.github.io/comparable-sales-grid/"><img src="https://raw.githubusercontent.com/chasebuilds/comparable-sales-grid/main/docs/screenshot.jpg" alt="comparable-sales-grid" width="560"></a>

- **[comparable-sales-grid](https://github.com/chasebuilds/comparable-sales-grid)** · Sales comparison grid: finds comps, adjusts each line with rates measured from the sales file, and reconciles a value range. Within 5% of true value on 93.0% of 200 synthetic test homes. [Live demo](https://chasebuilds.github.io/comparable-sales-grid/).
- **[home-value-model](https://github.com/chasebuilds/home-value-model)** · Automated valuation model tested on later sales, with a confidence score that says when not to trust an estimate. 6.0% median error, 72.4% within 10%, on 718 later Ames, Iowa sales. [Live demo](https://chasebuilds.github.io/home-value-model/).
- **[housing-market-trends](https://github.com/chasebuilds/housing-market-trends)** · Market-conditions dashboard: monthly metrics by market and price band, and a time-adjustment rate with a 95% band. 1.55 point mean error on the yearly price change over 196 synthetic market windows. [Live demo](https://chasebuilds.github.io/housing-market-trends/).
- **[assessment-ratio-study](https://github.com/chasebuilds/assessment-ratio-study)** · IAAO-style sales ratio study of a tax roll: COD, PRD, PRB and sales-chasing checks with a PASS, REVIEW or FAIL report. Regressivity, under-assessment and sales chasing caught in 30 of 30 seeded counties. [Live demo](https://chasebuilds.github.io/assessment-ratio-study/).
- Plus 4 more in the full list below.

### Maps, 3D and land

Public LiDAR, flood and stream data turned into 3D maps and first-pass land studies in the browser.

<a href="https://chasebuilds.github.io/land-feasibility-3d/"><img src="https://raw.githubusercontent.com/chasebuilds/land-feasibility-3d/main/docs/overview.png" alt="land-feasibility-3d" width="560"></a>

- **[land-feasibility-3d](https://github.com/chasebuilds/land-feasibility-3d)** · First-pass land study in the browser: USGS LiDAR terrain in 3D, slope classes, lots and pads, cut and fill, flood and stream checks, four-exit pro forma. [Live demo](https://chasebuilds.github.io/land-feasibility-3d/).

### Websites and design

Fast, mobile-first pages and motion that work without a framework.

<a href="https://chasebuilds.github.io/local-business-site/"><img src="https://raw.githubusercontent.com/chasebuilds/local-business-site/main/docs/bakery.png" alt="local-business-site" width="560"></a>

- **[local-business-site](https://github.com/chasebuilds/local-business-site)** · One YAML file to a fast, mobile-first one-page website for a local business, in three themes. [Live demo](https://chasebuilds.github.io/local-business-site/).
- **[motion-design-gallery](https://github.com/chasebuilds/motion-design-gallery)** · Eleven copy-paste web animations in plain HTML, CSS and JavaScript, safe for visitors who turn motion off. [Live demo](https://chasebuilds.github.io/motion-design-gallery/).

### Apps and dashboards

Web apps, dashboards and browser tools that run on a phone or laptop.

<a href="https://chasebuilds.github.io/react-analytics-dashboard/"><img src="https://raw.githubusercontent.com/chasebuilds/react-analytics-dashboard/main/docs/screenshot.png" alt="react-analytics-dashboard" width="560"></a>

- **[react-analytics-dashboard](https://github.com/chasebuilds/react-analytics-dashboard)** · Sales and operations dashboard in React and TypeScript: key figures, trend charts, filters and CSV export. [Live demo](https://chasebuilds.github.io/react-analytics-dashboard/).
- **[pc-build-planner](https://github.com/chasebuilds/pc-build-planner)** · Pick a budget and use case, get a PC parts list where every part fits, with the reason for each pick. [Live demo](https://chasebuilds.github.io/pc-build-planner/).
- **[field-service-pwa](https://github.com/chasebuilds/field-service-pwa)** · Phone app for trades crews: job tickets, checklists, photos, parts, time, customer signature and invoice. Works offline. [Live demo](https://chasebuilds.github.io/field-service-pwa/).
- **[table-export-extension](https://github.com/chasebuilds/table-export-extension)** · Chrome and Edge extension that exports any table on a web page to CSV or Excel. No data leaves the browser.
- Plus 1 more in the full list below.

### APIs and automation

Backends and scripts that take repeat work off your plate.

<a href="https://github.com/chasebuilds/appointment-booking-api"><img src="https://raw.githubusercontent.com/chasebuilds/appointment-booking-api/main/docs/openapi-docs.png" alt="appointment-booking-api" width="560"></a>

- **[appointment-booking-api](https://github.com/chasebuilds/appointment-booking-api)** · Booking backend for a small business: staff hours, time off, no double-booking, time-zone-correct slots.
- **[sheets-automations](https://github.com/chasebuilds/sheets-automations)** · Five Google Sheets automations: form cleanup, summary emails, invoice PDFs, overdue reminders, low-stock alerts.
- **[web-data-extractor](https://github.com/chasebuilds/web-data-extractor)** · Public catalog pages to a checked spreadsheet, only where robots.txt allows. 360 of 360 field values correct on the test site.

### Security checkups

Plain-English checkups of a website's public setup, no hacking involved.

<a href="https://chasebuilds.github.io/site-security-check/"><img src="https://raw.githubusercontent.com/chasebuilds/site-security-check/main/docs/screenshot.png" alt="site-security-check" width="560"></a>

- **[site-security-check](https://github.com/chasebuilds/site-security-check)** · A passive checkup of your own website, written up in plain English with a grade and fixes in order. [Live demo](https://chasebuilds.github.io/site-security-check/).

### AI with local models

AI that runs on your own computer, so private files never leave it.

<a href="https://github.com/chasebuilds/pdf-qa-local"><img src="https://raw.githubusercontent.com/chasebuilds/pdf-qa-local/main/docs/screenshot.png" alt="pdf-qa-local" width="560"></a>

- **[pdf-qa-local](https://github.com/chasebuilds/pdf-qa-local)** · Ask questions about a folder of PDFs and get answers that cite the file and page. Runs on your own computer, so documents stay private. Right page cited on 29 of 30 test questions, 12 of 12 unanswerable questions refused.
<!--/GROUPS-->

### How I work

- **Measured, not claimed.** Tools are tested against generated data where the right answer is known, and the score is written by a script. Results are on synthetic data; repos say what they were tested on and where they fall short.
- **Checkable.** You get an audit sheet of every change and a review sheet for anything uncertain.
- **Tested code.** Every repo runs linting, type checks and tests on each push.

<!--ALL-->
<details>
<summary><b>All 37 projects</b> (click to open)</summary>

| Project | Group | What it does | Result or demo |
|---|---|---|---|
| [pdf-to-excel](https://github.com/chasebuilds/pdf-to-excel) | Data cleanup and PDFs | Invoice PDFs to one Excel workbook, with a confidence score on every field | 3,600 of 3,600 fields correct on 400 invoices in 10 layouts |
| [excel-cleaner-pro](https://github.com/chasebuilds/excel-cleaner-pro) | Data cleanup and PDFs | Cleans messy CSV and Excel files and logs every change on an audit sheet | 5,615 of 5,627 fixable errors fixed, 611 of 611 unsafe values flagged |
| [data-merger](https://github.com/chasebuilds/data-merger) | Data cleanup and PDFs | Merges customer lists with different columns into one record per customer | 28,512 rows from 5 files with 0 false merges |
| [small-business-county-study](https://github.com/chasebuilds/small-business-county-study) | Data cleanup and PDFs | Small-business conditions in 31 Eastern Kentucky counties from free Census files, with charts and a written report rebuilt from one command | [Live demo](https://chasebuilds.github.io/small-business-county-study/) |
| [pdf-table-extractor](https://github.com/chasebuilds/pdf-table-extractor) | Data cleanup and PDFs | Tables from digital PDFs to clean Excel and CSV, stitched across pages, with a totals check on every table | 38,528 of 38,968 cells exact, 240 of 240 tables found |
| [address-normalizer](https://github.com/chasebuilds/address-normalizer) | Data cleanup and PDFs | Messy US mailing addresses to standardized, split fields, with duplicates grouped | 99.5% of cleaned rows fully right, 100% duplicate precision |
| [data-quality-checks](https://github.com/chasebuilds/data-quality-checks) | Data cleanup and PDFs | Declarative checks for CSV, Excel and Parquet files, run as DuckDB SQL, with a pass/fail report | 1,784 of 1,800 planted faults caught, 0 false alarms in 220 clean runs |
| [business-research-tool](https://github.com/chasebuilds/business-research-tool) | Data cleanup and PDFs | Company names to a research sheet where every fact has a source | 99.4% match precision on 300 test companies |
| [spreadsheet-diff](https://github.com/chasebuilds/spreadsheet-diff) | Data cleanup and PDFs | Compare two versions of a spreadsheet, cell by cell | 2,803 of 2,803 planted edits found, 0 false flags |
| [product-matcher](https://github.com/chasebuilds/product-matcher) | Data cleanup and PDFs | Match products between two lists by SKU, units and fuzzy names | 2,216 of 2,216 automatic matches correct |
| [excel-to-sql](https://github.com/chasebuilds/excel-to-sql) | Data cleanup and PDFs | Load CSV and Excel into SQL with type inference and a load report | 2,000 of 2,000 columns typed correctly |
| [json-to-tables](https://github.com/chasebuilds/json-to-tables) | Data cleanup and PDFs | Nested JSON to tidy related tables in Excel, CSV or SQLite | 426,604 of 426,604 values placed exactly once |
| [lead-list-qa](https://github.com/chasebuilds/lead-list-qa) | Data cleanup and PDFs | Offline quality checks for B2B contact lists | 1,531 of 1,531 planted faults caught |
| [excel-formula-auditor](https://github.com/chasebuilds/excel-formula-auditor) | Data cleanup and PDFs | Scan Excel workbooks for formula errors, hard-coded numbers and broken links | All 6 planted issue types caught, 0 false flags |
| [transaction-categorizer](https://github.com/chasebuilds/transaction-categorizer) | Data cleanup and PDFs | Categorize bank transactions with editable rules and a monthly summary | 5,100 of 5,100 seeded transactions categorized |
| [csv-combine-split](https://github.com/chasebuilds/csv-combine-split) | Data cleanup and PDFs | Combine a folder of files with aligned columns, or split a big file | 100,000 of 100,000 rows out, columns aligned |
| [comparable-sales-grid](https://github.com/chasebuilds/comparable-sales-grid) | Real estate and appraisal | Sales comparison grid: finds comps, adjusts each line with rates measured from the sales file, and reconciles a value range | Within 5% of true value on 93.0% of 200 synthetic test homes. [Live demo](https://chasebuilds.github.io/comparable-sales-grid/) |
| [home-value-model](https://github.com/chasebuilds/home-value-model) | Real estate and appraisal | Automated valuation model tested on later sales, with a confidence score that says when not to trust an estimate | 6.0% median error, 72.4% within 10%, on 718 later Ames, Iowa sales. [Live demo](https://chasebuilds.github.io/home-value-model/) |
| [housing-market-trends](https://github.com/chasebuilds/housing-market-trends) | Real estate and appraisal | Market-conditions dashboard: monthly metrics by market and price band, and a time-adjustment rate with a 95% band | 1.55 point mean error on the yearly price change over 196 synthetic market windows. [Live demo](https://chasebuilds.github.io/housing-market-trends/) |
| [assessment-ratio-study](https://github.com/chasebuilds/assessment-ratio-study) | Real estate and appraisal | IAAO-style sales ratio study of a tax roll: COD, PRD, PRB and sales-chasing checks with a PASS, REVIEW or FAIL report | Regressivity, under-assessment and sales chasing caught in 30 of 30 seeded counties. [Live demo](https://chasebuilds.github.io/assessment-ratio-study/) |
| [listing-data-normalizer](https://github.com/chasebuilds/listing-data-normalizer) | Real estate and appraisal | Messy MLS, assessor and comps exports to one table in RESO field names, duplicates merged, price history kept | 159,352 of 159,352 fields exact, 98.8% of duplicate pairs found. [Live demo](https://chasebuilds.github.io/listing-data-normalizer/) |
| [income-approach-valuation](https://github.com/chasebuilds/income-approach-valuation) | Real estate and appraisal | Income approach for rentals and small commercial: rent roll to NOI, direct cap, band of investment and DCF, reconciled | [Live demo](https://chasebuilds.github.io/income-approach-valuation/) |
| [cost-approach-calculator](https://github.com/chasebuilds/cost-approach-calculator) | Real estate and appraisal | Cost approach calculator: replacement cost new, depreciation and land value to an indicated value, every step shown | [Live demo](https://chasebuilds.github.io/cost-approach-calculator/) |
| [valuation-report-builder](https://github.com/chasebuilds/valuation-report-builder) | Real estate and appraisal | One YAML or JSON file to a clean property valuation summary in HTML and PDF, with the math checked first | [Live demo](https://chasebuilds.github.io/valuation-report-builder/) |
| [land-feasibility-3d](https://github.com/chasebuilds/land-feasibility-3d) | Maps, 3D and land | First-pass land study in the browser: USGS LiDAR terrain in 3D, slope classes, lots and pads, cut and fill, flood and stream checks, four-exit pro forma | [Live demo](https://chasebuilds.github.io/land-feasibility-3d/) |
| [local-business-site](https://github.com/chasebuilds/local-business-site) | Websites and design | One YAML file to a fast, mobile-first one-page website for a local business, in three themes | [Live demo](https://chasebuilds.github.io/local-business-site/) |
| [motion-design-gallery](https://github.com/chasebuilds/motion-design-gallery) | Websites and design | Eleven copy-paste web animations in plain HTML, CSS and JavaScript, safe for visitors who turn motion off | [Live demo](https://chasebuilds.github.io/motion-design-gallery/) |
| [react-analytics-dashboard](https://github.com/chasebuilds/react-analytics-dashboard) | Apps and dashboards | Sales and operations dashboard in React and TypeScript: key figures, trend charts, filters and CSV export | [Live demo](https://chasebuilds.github.io/react-analytics-dashboard/) |
| [pc-build-planner](https://github.com/chasebuilds/pc-build-planner) | Apps and dashboards | Pick a budget and use case, get a PC parts list where every part fits, with the reason for each pick | [Live demo](https://chasebuilds.github.io/pc-build-planner/) |
| [field-service-pwa](https://github.com/chasebuilds/field-service-pwa) | Apps and dashboards | Phone app for trades crews: job tickets, checklists, photos, parts, time, customer signature and invoice. Works offline | [Live demo](https://chasebuilds.github.io/field-service-pwa/) |
| [table-export-extension](https://github.com/chasebuilds/table-export-extension) | Apps and dashboards | Chrome and Edge extension that exports any table on a web page to CSV or Excel. No data leaves the browser |  |
| [automated-reporting-system](https://github.com/chasebuilds/automated-reporting-system) | Apps and dashboards | Raw weekly exports to a finished Excel report and HTML dashboard | 876 of 876 KPI values exact, 17 of 18 planted faults caught. [Live demo](https://chasebuilds.github.io/automated-reporting-system/) |
| [appointment-booking-api](https://github.com/chasebuilds/appointment-booking-api) | APIs and automation | Booking backend for a small business: staff hours, time off, no double-booking, time-zone-correct slots |  |
| [sheets-automations](https://github.com/chasebuilds/sheets-automations) | APIs and automation | Five Google Sheets automations: form cleanup, summary emails, invoice PDFs, overdue reminders, low-stock alerts |  |
| [web-data-extractor](https://github.com/chasebuilds/web-data-extractor) | APIs and automation | Public catalog pages to a checked spreadsheet, only where robots.txt allows | 360 of 360 field values correct on the test site |
| [site-security-check](https://github.com/chasebuilds/site-security-check) | Security checkups | A passive checkup of your own website, written up in plain English with a grade and fixes in order | [Live demo](https://chasebuilds.github.io/site-security-check/) |
| [pdf-qa-local](https://github.com/chasebuilds/pdf-qa-local) | AI with local models | Ask questions about a folder of PDFs and get answers that cite the file and page. Runs on your own computer, so documents stay private | Right page cited on 29 of 30 test questions, 12 of 12 unanswerable questions refused |

</details>
<!--/ALL-->

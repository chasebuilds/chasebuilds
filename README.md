<a href="https://chasebuilds.github.io"><img src="assets/banner.jpg" alt="Chase Builds: graphics, 3D web and data tools. Written from scratch, tested on every push, measured against known answers." width="100%"></a>

<p align="center">
<img src="https://img.shields.io/badge/WebGPU-1b1714?style=flat-square&logo=webgpu&logoColor=white" alt="WebGPU"> <img src="https://img.shields.io/badge/WebGL2%20%2B%20GLSL-1b1714?style=flat-square&logo=webgl&logoColor=white" alt="WebGL2 %2B GLSL"> <img src="https://img.shields.io/badge/Three.js-1b1714?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js"> <img src="https://img.shields.io/badge/React-1b1714?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/TypeScript-1b1714?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript"> <img src="https://img.shields.io/badge/Python-1b1714?style=flat-square&logo=python&logoColor=FFD43B" alt="Python"> <img src="https://img.shields.io/badge/pandas-1b1714?style=flat-square&logo=pandas&logoColor=white" alt="pandas"> <img src="https://img.shields.io/badge/scikit--learn-1b1714?style=flat-square&logo=scikitlearn&logoColor=F7931E" alt="scikit--learn"> <img src="https://img.shields.io/badge/DuckDB-1b1714?style=flat-square&logo=duckdb&logoColor=FFF000" alt="DuckDB"> <img src="https://img.shields.io/badge/MCP-1b1714?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP">
</p>

<p align="center"><b><a href="#featured">Featured</a></b> · <b><a href="#benchmarks">Benchmarks</a></b> · <b><a href="#all-work">All work</a></b> · <b><a href="https://chasebuilds.github.io">Site</a></b></p>

### Featured

Live demos run in the browser. Click a picture to open one.

<!--SHOWCASE-->
<table>
<tr><td width="50%" valign="top"><a href="https://chasebuilds.github.io/r3f-showcase/"><img src="https://chasebuilds.github.io/img/r3f-showcase-sm.webp" alt="r3f-showcase" width="100%"></a><br><b><a href="https://github.com/chasebuilds/r3f-showcase">r3f-showcase</a></b><br>React Three Fiber scenes: product configurator, scroll-driven hero, gallery wall, GLSL lava planet.<br><sub>Lighthouse mobile 76 to 90 on the 3D pages</sub></td><td width="50%" valign="top"><a href="https://chasebuilds.github.io/webgpu-agent-kit/"><img src="https://chasebuilds.github.io/img/webgpu-agent-kit-sm.webp" alt="webgpu-agent-kit" width="100%"></a><br><b><a href="https://github.com/chasebuilds/webgpu-agent-kit">webgpu-agent-kit</a></b><br>10 WebGPU examples, naga WGSL validation, a CLI and an MCP server so coding agents write GPU code that runs.<br><sub>10 of 10 examples render with no validation errors</sub></td></tr>
<tr><td width="50%" valign="top"><a href="https://chasebuilds.github.io/liquid-logo-studio/"><img src="https://chasebuilds.github.io/img/liquid-logo-studio-sm.webp" alt="liquid-logo-studio" width="100%"></a><br><b><a href="https://github.com/chasebuilds/liquid-logo-studio">liquid-logo-studio</a></b><br>Logo to liquid metal: distance-field bevel and reflection shader in WebGL2, PNG and WebM export, one-tag embed.<br><sub>Embed script 8,000 bytes gzipped</sub></td><td width="50%" valign="top"><a href="https://chasebuilds.github.io/cursor-fluid/"><img src="https://chasebuilds.github.io/img/cursor-fluid-sm.webp" alt="cursor-fluid" width="100%"></a><br><b><a href="https://github.com/chasebuilds/cursor-fluid">cursor-fluid</a></b><br>Stable-fluids solver in WebGL2: advection, Jacobi pressure solve, vorticity confinement, adaptive quality.<br><sub>6,984 bytes gzipped, zero dependencies</sub></td></tr>
<tr><td width="50%" valign="top"><a href="https://chasebuilds.github.io/land-feasibility-3d/"><img src="https://chasebuilds.github.io/img/land-feasibility-3d-sm.webp" alt="land-feasibility-3d" width="100%"></a><br><b><a href="https://github.com/chasebuilds/land-feasibility-3d">land-feasibility-3d</a></b><br>USGS LiDAR terrain in 3D with slope classes, lot layout, cut and fill, flood and stream checks.</td><td width="50%" valign="top"><a href="https://chasebuilds.github.io/home-value-model/"><img src="https://chasebuilds.github.io/img/home-value-model-sm.webp" alt="home-value-model" width="100%"></a><br><b><a href="https://github.com/chasebuilds/home-value-model">home-value-model</a></b><br>Automated valuation model: hedonic ridge and gradient boosting, time-split test, IAAO accuracy metrics.<br><sub>6.0% median error on 718 later Ames, Iowa sales</sub></td></tr>
</table>
<!--/SHOWCASE-->

### Benchmarks

Scored by a script against data where the right answer is known. Each repo's `BENCHMARK.md` says how it was measured and where it falls short.

<!--BENCH-->
| Repo | What it does | Measured |
|---|---|---|
| [pdf-to-excel](https://github.com/chasebuilds/pdf-to-excel) | Invoice PDFs to one Excel workbook, with a confidence score on every field | 3,600 of 3,600 fields correct on 400 invoices in 10 layouts |
| [pdf-table-extractor](https://github.com/chasebuilds/pdf-table-extractor) | Tables from digital PDFs to clean Excel and CSV, stitched across pages, with a totals check on every table | 38,528 of 38,968 cells exact, 240 of 240 tables found |
| [data-quality-checks](https://github.com/chasebuilds/data-quality-checks) | Declarative checks for CSV, Excel and Parquet files, run as DuckDB SQL, with a pass/fail report | 1,784 of 1,800 planted faults caught, 0 false alarms in 220 clean runs |
| [data-merger](https://github.com/chasebuilds/data-merger) | Merges customer lists with different columns into one record per customer | 28,512 rows from 5 files with 0 false merges |
| [listing-data-normalizer](https://github.com/chasebuilds/listing-data-normalizer) | Messy MLS, assessor and comps exports to one table in RESO field names, duplicates merged, price history kept | 159,352 of 159,352 fields exact, 98.8% of duplicate pairs found |
| [comparable-sales-grid](https://github.com/chasebuilds/comparable-sales-grid) | Sales comparison grid: finds comps, adjusts each line with rates measured from the sales file, and reconciles a value range | Within 5% of true value on 93.0% of 200 synthetic test homes |
| [home-value-model](https://github.com/chasebuilds/home-value-model) | Automated valuation model tested on later sales, with a confidence score that says when not to trust an estimate | 6.0% median error, 72.4% within 10%, on 718 later Ames, Iowa sales |
| [assessment-ratio-study](https://github.com/chasebuilds/assessment-ratio-study) | IAAO-style sales ratio study of a tax roll: COD, PRD, PRB and sales-chasing checks with a PASS, REVIEW or FAIL report | Regressivity, under-assessment and sales chasing caught in 30 of 30 seeded counties |
| [automated-reporting-system](https://github.com/chasebuilds/automated-reporting-system) | Raw weekly exports to a finished Excel report and HTML dashboard | 876 of 876 KPI values exact, 17 of 18 planted faults caught |
| [pdf-qa-local](https://github.com/chasebuilds/pdf-qa-local) | Ask questions about a folder of PDFs and get answers that cite the file and page. Runs on your own computer, so documents stay private | Right page cited on 29 of 30 test questions, 12 of 12 unanswerable questions refused |
<!--/BENCH-->

### All work

<!--GROUPS-->
#### Data cleanup and PDFs

- **[pdf-to-excel](https://github.com/chasebuilds/pdf-to-excel)** · Invoice PDFs to one Excel workbook, with a confidence score on every field. 3,600 of 3,600 fields correct on 400 invoices in 10 layouts.
- **[excel-cleaner-pro](https://github.com/chasebuilds/excel-cleaner-pro)** · Cleans messy CSV and Excel files and logs every change on an audit sheet. 5,615 of 5,627 fixable errors fixed, 611 of 611 unsafe values flagged.
- **[data-merger](https://github.com/chasebuilds/data-merger)** · Merges customer lists with different columns into one record per customer. 28,512 rows from 5 files with 0 false merges.
- **[small-business-county-study](https://github.com/chasebuilds/small-business-county-study)** · Small-business conditions in 31 Eastern Kentucky counties from free Census files, with charts and a written report rebuilt from one command. [Live demo](https://chasebuilds.github.io/small-business-county-study/).
- Plus 12 more in the full list below.

#### Real estate

- **[comparable-sales-grid](https://github.com/chasebuilds/comparable-sales-grid)** · Sales comparison grid: finds comps, adjusts each line with rates measured from the sales file, and reconciles a value range. Within 5% of true value on 93.0% of 200 synthetic test homes. [Live demo](https://chasebuilds.github.io/comparable-sales-grid/).
- **[home-value-model](https://github.com/chasebuilds/home-value-model)** · Automated valuation model tested on later sales, with a confidence score that says when not to trust an estimate. 6.0% median error, 72.4% within 10%, on 718 later Ames, Iowa sales. [Live demo](https://chasebuilds.github.io/home-value-model/).
- **[listing-kit](https://github.com/chasebuilds/listing-kit)** · One YAML file to a fast single-listing website (gallery, map, open house calendar, payment estimate, print flyer), plus a fair-housing wording checker. Checker precision 94.0% on 137 held-out sentences; Lighthouse 100 on listing pages. [Live demo](https://chasebuilds.github.io/listing-kit/).
- **[seller-net-sheet-cma](https://github.com/chasebuilds/seller-net-sheet-cma)** · Seller net sheet with three price scenarios and proration formulas shown, plus a CMA listing presentation from a comps file. [Live demo](https://chasebuilds.github.io/seller-net-sheet-cma/).
- Plus 7 more in the full list below.

#### Maps, 3D and land

- **[land-feasibility-3d](https://github.com/chasebuilds/land-feasibility-3d)** · First-pass land study in the browser: USGS LiDAR terrain in 3D, slope classes, lots and pads, cut and fill, flood and stream checks, four-exit pro forma. [Live demo](https://chasebuilds.github.io/land-feasibility-3d/).

#### Websites and design

- **[local-business-site](https://github.com/chasebuilds/local-business-site)** · One YAML file to a fast, mobile-first one-page website for a local business, in three themes. [Live demo](https://chasebuilds.github.io/local-business-site/).
- **[motion-design-gallery](https://github.com/chasebuilds/motion-design-gallery)** · Eleven copy-paste web animations in plain HTML, CSS and JavaScript, safe for visitors who turn motion off. [Live demo](https://chasebuilds.github.io/motion-design-gallery/).
- **[r3f-showcase](https://github.com/chasebuilds/r3f-showcase)** · Four interactive 3D website pieces in React Three Fiber: product configurator, scroll-driven hero, gallery wall and a shader planet. Lighthouse mobile score 100 on the overview, 76 to 90 on the 3D pages. [Live demo](https://chasebuilds.github.io/r3f-showcase/).
- **[liquid-logo-studio](https://github.com/chasebuilds/liquid-logo-studio)** · Any SVG or PNG logo to animated liquid chrome, gold or holographic metal, saved as PNG or WebM or embedded with one script. Embed script is 8,000 bytes gzipped. [Live demo](https://chasebuilds.github.io/liquid-logo-studio/).
- Plus 1 more in the full list below.

#### Apps and dashboards

- **[react-analytics-dashboard](https://github.com/chasebuilds/react-analytics-dashboard)** · Sales and operations dashboard in React and TypeScript: key figures, trend charts, filters and CSV export. [Live demo](https://chasebuilds.github.io/react-analytics-dashboard/).
- **[pc-build-planner](https://github.com/chasebuilds/pc-build-planner)** · Pick a budget and use case, get a PC parts list where every part fits, with the reason for each pick. [Live demo](https://chasebuilds.github.io/pc-build-planner/).
- **[field-service-pwa](https://github.com/chasebuilds/field-service-pwa)** · Phone app for trades crews: job tickets, checklists, photos, parts, time, customer signature and invoice. Works offline. [Live demo](https://chasebuilds.github.io/field-service-pwa/).
- **[table-export-extension](https://github.com/chasebuilds/table-export-extension)** · Chrome and Edge extension that exports any table on a web page to CSV or Excel. No data leaves the browser.
- Plus 1 more in the full list below.

#### APIs and automation

- **[webgpu-agent-kit](https://github.com/chasebuilds/webgpu-agent-kit)** · Helps AI coding agents write working WebGPU code: ten live examples, a line-numbered WGSL checker, a CLI and an MCP server. 10 of 10 examples render with no validation errors. [Live demo](https://chasebuilds.github.io/webgpu-agent-kit/).
- **[appointment-booking-api](https://github.com/chasebuilds/appointment-booking-api)** · Booking backend for a small business: staff hours, time off, no double-booking, time-zone-correct slots.
- **[sheets-automations](https://github.com/chasebuilds/sheets-automations)** · Five Google Sheets automations: form cleanup, summary emails, invoice PDFs, overdue reminders, low-stock alerts.
- **[web-data-extractor](https://github.com/chasebuilds/web-data-extractor)** · Public catalog pages to a checked spreadsheet, only where robots.txt allows. 360 of 360 field values correct on the test site.

#### Security checkups

- **[site-security-check](https://github.com/chasebuilds/site-security-check)** · A passive checkup of your own website, written up in plain English with a grade and fixes in order. [Live demo](https://chasebuilds.github.io/site-security-check/).

#### AI with local models

- **[pdf-qa-local](https://github.com/chasebuilds/pdf-qa-local)** · Ask questions about a folder of PDFs and get answers that cite the file and page. Runs on your own computer, so documents stay private. Right page cited on 29 of 30 test questions, 12 of 12 unanswerable questions refused.
<!--/GROUPS-->

### How I build

- **Measured, not claimed.** Each tool is scored against data where the right answer is known, by a script, not by hand. Repos say what they were tested on and where they fall short.
- **Checkable.** Uncertain results go to a review sheet instead of being guessed.
- **Tested code.** Every repo runs linting, type checks and tests on each push.
- **Written from scratch.** Shaders, solvers and models are my own code; projects that started from an idea elsewhere credit it in their README.

<!--ALL-->
<details>
<summary><b>All 44 projects</b> (click to open)</summary>

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
| [comparable-sales-grid](https://github.com/chasebuilds/comparable-sales-grid) | Real estate | Sales comparison grid: finds comps, adjusts each line with rates measured from the sales file, and reconciles a value range | Within 5% of true value on 93.0% of 200 synthetic test homes. [Live demo](https://chasebuilds.github.io/comparable-sales-grid/) |
| [home-value-model](https://github.com/chasebuilds/home-value-model) | Real estate | Automated valuation model tested on later sales, with a confidence score that says when not to trust an estimate | 6.0% median error, 72.4% within 10%, on 718 later Ames, Iowa sales. [Live demo](https://chasebuilds.github.io/home-value-model/) |
| [listing-kit](https://github.com/chasebuilds/listing-kit) | Real estate | One YAML file to a fast single-listing website (gallery, map, open house calendar, payment estimate, print flyer), plus a fair-housing wording checker | Checker precision 94.0% on 137 held-out sentences; Lighthouse 100 on listing pages. [Live demo](https://chasebuilds.github.io/listing-kit/) |
| [seller-net-sheet-cma](https://github.com/chasebuilds/seller-net-sheet-cma) | Real estate | Seller net sheet with three price scenarios and proration formulas shown, plus a CMA listing presentation from a comps file | [Live demo](https://chasebuilds.github.io/seller-net-sheet-cma/) |
| [showing-route-planner](https://github.com/chasebuilds/showing-route-planner) | Real estate | Orders a day of showings to fit every listing window with the least driving; offline phone app with a buyer itinerary and calendar file | Matched the exact best route on 111 of 120 small test days. [Live demo](https://chasebuilds.github.io/showing-route-planner/) |
| [housing-market-trends](https://github.com/chasebuilds/housing-market-trends) | Real estate | Market-conditions dashboard: monthly metrics by market and price band, and a time-adjustment rate with a 95% band | 1.55 point mean error on the yearly price change over 196 synthetic market windows. [Live demo](https://chasebuilds.github.io/housing-market-trends/) |
| [assessment-ratio-study](https://github.com/chasebuilds/assessment-ratio-study) | Real estate | IAAO-style sales ratio study of a tax roll: COD, PRD, PRB and sales-chasing checks with a PASS, REVIEW or FAIL report | Regressivity, under-assessment and sales chasing caught in 30 of 30 seeded counties. [Live demo](https://chasebuilds.github.io/assessment-ratio-study/) |
| [listing-data-normalizer](https://github.com/chasebuilds/listing-data-normalizer) | Real estate | Messy MLS, assessor and comps exports to one table in RESO field names, duplicates merged, price history kept | 159,352 of 159,352 fields exact, 98.8% of duplicate pairs found. [Live demo](https://chasebuilds.github.io/listing-data-normalizer/) |
| [income-approach-valuation](https://github.com/chasebuilds/income-approach-valuation) | Real estate | Income approach for rentals and small commercial: rent roll to NOI, direct cap, band of investment and DCF, reconciled | [Live demo](https://chasebuilds.github.io/income-approach-valuation/) |
| [cost-approach-calculator](https://github.com/chasebuilds/cost-approach-calculator) | Real estate | Cost approach calculator: replacement cost new, depreciation and land value to an indicated value, every step shown | [Live demo](https://chasebuilds.github.io/cost-approach-calculator/) |
| [valuation-report-builder](https://github.com/chasebuilds/valuation-report-builder) | Real estate | One YAML or JSON file to a clean property valuation summary in HTML and PDF, with the math checked first | [Live demo](https://chasebuilds.github.io/valuation-report-builder/) |
| [land-feasibility-3d](https://github.com/chasebuilds/land-feasibility-3d) | Maps, 3D and land | First-pass land study in the browser: USGS LiDAR terrain in 3D, slope classes, lots and pads, cut and fill, flood and stream checks, four-exit pro forma | [Live demo](https://chasebuilds.github.io/land-feasibility-3d/) |
| [local-business-site](https://github.com/chasebuilds/local-business-site) | Websites and design | One YAML file to a fast, mobile-first one-page website for a local business, in three themes | [Live demo](https://chasebuilds.github.io/local-business-site/) |
| [motion-design-gallery](https://github.com/chasebuilds/motion-design-gallery) | Websites and design | Eleven copy-paste web animations in plain HTML, CSS and JavaScript, safe for visitors who turn motion off | [Live demo](https://chasebuilds.github.io/motion-design-gallery/) |
| [r3f-showcase](https://github.com/chasebuilds/r3f-showcase) | Websites and design | Four interactive 3D website pieces in React Three Fiber: product configurator, scroll-driven hero, gallery wall and a shader planet | Lighthouse mobile score 100 on the overview, 76 to 90 on the 3D pages. [Live demo](https://chasebuilds.github.io/r3f-showcase/) |
| [liquid-logo-studio](https://github.com/chasebuilds/liquid-logo-studio) | Websites and design | Any SVG or PNG logo to animated liquid chrome, gold or holographic metal, saved as PNG or WebM or embedded with one script | Embed script is 8,000 bytes gzipped. [Live demo](https://chasebuilds.github.io/liquid-logo-studio/) |
| [cursor-fluid](https://github.com/chasebuilds/cursor-fluid) | Websites and design | A dependency-free WebGL2 fluid background that follows the cursor, keeps hero text readable and scales quality to hold frame rate on phones | 6,984 bytes gzipped, no dependencies. [Live demo](https://chasebuilds.github.io/cursor-fluid/) |
| [react-analytics-dashboard](https://github.com/chasebuilds/react-analytics-dashboard) | Apps and dashboards | Sales and operations dashboard in React and TypeScript: key figures, trend charts, filters and CSV export | [Live demo](https://chasebuilds.github.io/react-analytics-dashboard/) |
| [pc-build-planner](https://github.com/chasebuilds/pc-build-planner) | Apps and dashboards | Pick a budget and use case, get a PC parts list where every part fits, with the reason for each pick | [Live demo](https://chasebuilds.github.io/pc-build-planner/) |
| [field-service-pwa](https://github.com/chasebuilds/field-service-pwa) | Apps and dashboards | Phone app for trades crews: job tickets, checklists, photos, parts, time, customer signature and invoice. Works offline | [Live demo](https://chasebuilds.github.io/field-service-pwa/) |
| [table-export-extension](https://github.com/chasebuilds/table-export-extension) | Apps and dashboards | Chrome and Edge extension that exports any table on a web page to CSV or Excel. No data leaves the browser |  |
| [automated-reporting-system](https://github.com/chasebuilds/automated-reporting-system) | Apps and dashboards | Raw weekly exports to a finished Excel report and HTML dashboard | 876 of 876 KPI values exact, 17 of 18 planted faults caught. [Live demo](https://chasebuilds.github.io/automated-reporting-system/) |
| [webgpu-agent-kit](https://github.com/chasebuilds/webgpu-agent-kit) | APIs and automation | Helps AI coding agents write working WebGPU code: ten live examples, a line-numbered WGSL checker, a CLI and an MCP server | 10 of 10 examples render with no validation errors. [Live demo](https://chasebuilds.github.io/webgpu-agent-kit/) |
| [appointment-booking-api](https://github.com/chasebuilds/appointment-booking-api) | APIs and automation | Booking backend for a small business: staff hours, time off, no double-booking, time-zone-correct slots |  |
| [sheets-automations](https://github.com/chasebuilds/sheets-automations) | APIs and automation | Five Google Sheets automations: form cleanup, summary emails, invoice PDFs, overdue reminders, low-stock alerts |  |
| [web-data-extractor](https://github.com/chasebuilds/web-data-extractor) | APIs and automation | Public catalog pages to a checked spreadsheet, only where robots.txt allows | 360 of 360 field values correct on the test site |
| [site-security-check](https://github.com/chasebuilds/site-security-check) | Security checkups | A passive checkup of your own website, written up in plain English with a grade and fixes in order | [Live demo](https://chasebuilds.github.io/site-security-check/) |
| [pdf-qa-local](https://github.com/chasebuilds/pdf-qa-local) | AI with local models | Ask questions about a folder of PDFs and get answers that cite the file and page. Runs on your own computer, so documents stay private | Right page cited on 29 of 30 test questions, 12 of 12 unanswerable questions refused |

</details>
<!--/ALL-->

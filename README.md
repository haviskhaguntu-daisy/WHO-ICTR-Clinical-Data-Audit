# WHO-ICTR-Clinical-Data-Audit
An Excel-based clinical data management
# WHO ICTRP Clinical Trial Registry Audit

## Project Overview
This project performs a clinical data management (CDM) audit on public trial records extracted from the World Health Organization International Clinical Trials Registry Platform (WHO ICTRP). The objective is to identify, document, and categorize eCRF data discrepancies, missing mandatory endpoints, and protocol non-compliance.

## Repository Contents
* `WHO_ICTRP_Clinical_Data_Audit.xlsx`: Multi-tab Excel workbook containing raw/cleaned trial records, an eCRF discrepancy query log, and a dynamic summary dashboard.

## Workbook Architecture
1. **`Cleaned_Data`**: Formatted trial records from the WHO ICTRP database containing study titles, registration dates, target sample sizes, and outcome endpoints.
2. **`Query_Log`**: Structured discrepancy log tracking data anomalies using standardized fields (`Query_ID`, `Trial_ID`, `Field_Name`, `Discrepancy_Description`, `Priority`, `Status`).
3. **`Summary_Dashboard`**: Interactive PivotTable and stacked column visualization categorizing clinical queries by severity (`High`/`Medium`) and status (`Open`/`Resolved`).

## Key Discrepancies Audited
* Mandatory completion fields missing (e.g., blank results dates and missing primary outcome parameters).
* Ambiguous numerical entries (e.g., participant age parameters missing specified time units).
* Unpopulated results endpoints despite flagged availability status.

## Tools Used
* Microsoft Excel (PivotTables, PivotCharts, Data Validation, Logical Formatting)
* Clinical Data Quality & Discrepancy Management Principles
*

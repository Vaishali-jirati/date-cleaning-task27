## Date Cleaning Basics (Retail Sales Dataset, Excel)

## Overview
Standardized inconsistent date formats and handled data anomalies using Microsoft Excel as part of the Data Analytics internship at Veda Technology.

## Files
- `Date_Cleaning.xlsx`: Excel file containing Raw data, Cleaned sheet, Checks, and Issue Log.

## Setup
- Tool: Microsoft Excel
- Dataset: Retail Sales Dataset(modified for data cleaning practice).

## Dataset
- **Source:** Retail Sales Dataset (modified for data cleaning practice).
- **Description:** A sample dataset containing 30 rows of transaction records, including Transaction ID, Date, Product Category, Quantity, and Total Amount.
- **Data Modification & Practice:** To practice real-world data cleaning challenges, date values in the raw dataset were intentionally customized with mixed formats (ISO `YYYY-MM-DD`, DMY `DD/MM/YYYY`, and Text formats) along with deliberate anomalies such as impossible calendar dates (e.g., April 31st, February 30th) and missing/blank entries to build an issue log.

## Key Deliverables & Approach
1. **Standardized Date Formats:** Handled mixed formats including ISO (`YYYY-MM-DD`), DMY (`DD/MM/YYYY`), and Text formats (`13-Jan-2023`) into a uniform date standard.
2. **Identified Data Anomalies (Issue Log):** Successfully tracked and flagged 5 invalid date entries:
   - Impossible dates (e.g., April 31st, February 30th).
   - Invalid month values (e.g., Month 13).
   - Missing/blank values and non-date text entries.

## What I learned
- Why dates are often problematic due to regional format mismatches and mixed text/numeric entries.
- How to parse dates explicitly and maintain an issue log to handle bad data cleanly without corrupting the dataset.


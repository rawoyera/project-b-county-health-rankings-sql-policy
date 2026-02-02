# Data Cleaning Log — County Health Rankings 2025

## Source
County Health Rankings 2025 Analytic Data

## Cleaning Steps
- Renamed core identifier columns to snake_case for SQL compatibility
- Preserved FIPS as a 5-character text field with leading zeros
- Removed national-level (United States) aggregate row
- Verified one row per county
- Exported dataset in CSV format for SQL analysis

## Notes
- No imputation performed
- All missing values retained as NULL equivalents

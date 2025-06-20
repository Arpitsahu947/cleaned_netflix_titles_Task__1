# cleaned_netflix_titles_Task__1
Data Cleaning and Preprocessing
# Netflix Dataset - Data Cleaning (Excel)

## Cleaning Summary

- **Missing Values**:
  - Replaced empty `country` fields with "Unknown".
  - Replaced empty `cast` and `director` fields with "Not Available".

- **Duplicates**:
  - Removed all duplicate rows using Excel's "Remove Duplicates" feature.

- **Standardization**:
  - Converted text fields like `type` and `country` to lowercase.
  - Renamed all column headers to lowercase and used underscores instead of spaces.

- **Date Format**:
  - Converted `date_added` to consistent `DD-MM-YYYY` format.

## File Included
- `cleaned_netflix_titles.xlsx` (Cleaned dataset)

## Tool Used
- Microsoft Excel

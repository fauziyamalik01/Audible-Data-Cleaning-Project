## 🎧 Audible Data Cleaning — Power Query Case Study
A data cleaning project using Power Query Editor in Excel to standardize and prepare an Audible audiobook dataset for analysis.

## 🧹 Cleaning Steps

1. Applied title casing to the name column for consistent formatting
2. Separated multiple authors in the author column by delimiter and standardized with a Writtenby: prefix
3. Converted the releasedate column to a consistent DD-MM-YYYY date format using locale settings
4. Extracted hours and minutes from the time column, trimmed whitespace, and merged them into a clean time_Standardized column
5. Converted the price column to Decimal Number format — no non-numeric values found
6. Cleaned the stars column by extracting numeric ratings and replacing "Not rated yet" with null
7. Split the narrator column into separate rows for books with multiple narrators and added a Narratedby: prefix
8. Merged releasedate and language into a new column releaseInfo in the format DD-MM-YYYY, Language
9. Formatted the price column to two decimal places using Accounting format


## 🛠️ Tools Used
Microsoft Excel — Power Query Editor (M Query, Split Column, Replace Values, Custom Column, Change Type with Locale)

# netflix-data-cleaning
"This repository contains the Netflix Movies and TV Shows dataset, cleaned and preprocessed in Excel. Missing values were handled, duplicates removed, text standardized, and dates formatted to make the dataset ready for analysis and visualization."
# Data Analyst Internship – Task 1 (Excel Version)

## Dataset Used
Netflix Movies and TV Shows dataset (Kaggle).

## Objective
To clean and preprocess the raw dataset using **Excel** by handling missing values, duplicates, inconsistent formats, and preparing it for analysis.

## Steps Performed
1. **Handled Missing Values**
   - Replaced missing `director` with "Unknown".
   - Replaced missing `cast` with "Not Available".
   - Replaced missing `country` with "Unknown".
   - Replaced missing `rating` with "Not Rated".
   - Forward filled `date_added` where possible.

2. **Removed Duplicates**
   - Used Excel’s *Remove Duplicates* function.

3. **Standardized Text Values**
   - Converted `rating` to uppercase using Excel’s `UPPER()`.
   - Converted `country` to title case using Excel’s `PROPER()`.

4. **Converted Date Formats**
   - Formatted `date_added` column to `DD-MM-YYYY`.

5. **Renamed Columns**
   - Cleaned headers: lowercase, underscores instead of spaces.

6. **Checked Data Types**
   - Ensured numeric fields (`release_year`, `duration`) are numbers.
   - Ensured `date_added` is a proper date.

## Deliverables
- `netflix_titles.csv` → Original dataset
- `netflix_cleaned.xlsx` → Cleaned dataset
- `README.md` → Documentation

## Outcome
The dataset is now consistent, clean, and ready for analysis or visualization.

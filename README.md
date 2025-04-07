

## 🧹 Task Summary:
This task involved cleaning and preprocessing the Netflix Movies and TV Shows dataset.

### 🔧 Cleaning Steps Performed:
- Removed duplicate entries.
- Handled missing values using `.fillna()` with "Unknown".
- Converted `date_added` to datetime format using `pd.to_datetime()`.
- Standardized text columns to lowercase and removed extra spaces.
- Renamed all column headers to lowercase with underscores.
- Verified and corrected column data types.

### 📁 Files:
- `netflix_titles.csv` – Original dataset
- `netflix_cleaning.py` – Cleaning script
- `netflix_cleaned.csv` – Final cleaned dataset

### ✅ Tools Used:
- Python
- Pandas


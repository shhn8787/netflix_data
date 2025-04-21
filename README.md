# Netflix Dataset Cleaning (Internship Task)

## 📋 Objective
The goal of this task was to clean and prepare a raw Netflix dataset using Python and Pandas. The dataset included missing values, duplicates, and inconsistent data formats.

## 🛠️ Tools Used
- **Python** (with Pandas)
- **VS Code**
- **GitHub** for version control

## 📂 Files Included
- **`data_cleaning.py`**: Python script used for data cleaning.
- **`netflix_titles.csv`**: Original raw dataset from Netflix.
- **`cleaned_netflix.csv`**: The cleaned version of the Netflix dataset after handling missing values and other issues.
- **`summary.txt`**: Summary of all changes made to the dataset.
  
## 🔍 Cleaning Steps
1. **Removed Duplicates**: Deleted any duplicate rows in the dataset.
2. **Handled Missing Values**: 
   - Filled missing values for 'director', 'cast', and 'country' with 'Unknown'.
   - Filled missing 'date_added' with a placeholder date ('01-Jan-2000').
   - Filled missing 'rating' and 'duration' with default values.
3. **Standardized Text**: 
   - Converted all 'type' and 'country' columns to lowercase and title case, respectively.
4. **Converted Date Format**: The 'date_added' column was converted to a proper `datetime` format.
5. **Renamed Columns**: All column names were made lowercase and spaces were replaced with underscores for consistency.

## 📈 Result
The cleaned dataset is saved as **`cleaned_netflix.csv`** and is ready for further analysis or use in machine learning tasks.

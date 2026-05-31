# Netflix Movies and TV Shows - Data Cleaning

This project focuses on cleaning the Netflix Movies and TV Shows dataset sourced from Kaggle.
The goal was to handle missing values, fix data types, and prepare the dataset for further analysis.

---

## Dataset
- **Source:** [Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/code/aryantiwari123/netflix-movies-and-tv-shows/input)
- **Raw Dataset:** `Netflix_Movies_and_TV_Shows.csv`
- **Cleaned Dataset:** `Netflix_Cleaned.csv`

---

## What I Did
- Handled missing values in `director`, `cast`, `country`, `rating` by filling with `'Unknown'`
- Converted `date_added` column from string to datetime dtype
- Extracted year from `date_added` and created a new column `year_added`
- Filled null values in `year_added` with the most frequently occurring year (mode)
- Removed extra whitespaces from all text columns
- Checked for duplicates — none were found in this dataset
- Renamed `listed_in` column to `genre` for better readability
- Removed `#` symbols from the `title` column

---

## Tools Used
- Python
- Pandas
- VS Code
- Git

---

## Files
- `Netflix_Movies_and_TV_Shows.csv` — Original raw dataset
- `Netflix_Cleaned.csv` — Final cleaned dataset
- `data_cleaning.ipynb` — Jupyter notebook with full cleaning code
- `Data_Cleaning_Report.pdf` — Screenshots of code and outputs

---

## How to Run
1. Install dependencies: `pip install pandas`
2. Open `data_cleaning.ipynb` in VS Code or Jupyter
3. Run all cells in order

---

## Author
**Tushar**
- [LinkedIn](https://www.linkedin.com/in/tushar-biswas03/)
- [GitHub](https://github.com/Tushar068)
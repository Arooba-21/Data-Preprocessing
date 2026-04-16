# Data Cleaning Projects

A collection of real-world data cleaning notebooks using Python (pandas, numpy). Each project tackles a different dataset and demonstrates practical cleaning techniques commonly needed before analysis or visualization.

---

## Projects

### 1. Customer Support Tickets
**File:** `customer_support_cleaning.ipynb`

Cleaned a customer support ticket dataset with mixed data types, inconsistent categories, and missing values.

**Key techniques:**
- Fixing data types (datetime parsing, category columns)
- Standardizing categorical values (e.g. `"male"`, `"MALE"` → `"male"`)
- Handling nulls with context-aware fills (`"Not Resolved"`, `0`)
- Outlier validation on rating columns
- Correcting spelling variations with a mapping dictionary

---

### 2. Retail Sales (Superstore)
**File:** `retail_data_cleaning.ipynb`

Cleaned a retail transactions dataset (Superstore-style) and prepared it for BI/dashboard use.

**Key techniques:**
- Standardizing column names (snake_case, stripping special characters)
- Date parsing and feature engineering (year, month, quarter, weekday, ship days)
- Null handling with business logic (drop key rows, fill postal codes)
- Duplicate removal on composite keys (`order_id` + `product_id`)
- String normalization on categorical fields (`.str.title()`)
- Sales outlier flagging using IQR (1st–99th percentile)
- Aggregated monthly summary export
- Output to multi-sheet Excel (`retail_cleaned.xlsx`)

---

## Skills Demonstrated

| Skill | Tools Used |
|---|---|
| Data type fixing | `pd.to_datetime`, `.astype('category')` |
| Missing value handling | `.fillna()`, `.dropna()` |
| String standardization | `.str.strip()`, `.str.lower()`, `.str.title()` |
| Duplicate detection | `.drop_duplicates()` |
| Outlier flagging | `.quantile()` |
| Feature engineering | `.dt` accessor, lambda functions |
| Aggregation | `.groupby()`, `.agg()` |
| Export | `pd.ExcelWriter`, `openpyxl` |

---

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/data-cleaning-projects.git
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy openpyxl
   ```

3. Place your source CSV files in the project folder and update the file paths in each notebook.

4. Run cells top to bottom in Jupyter Notebook or VS Code.

---

## Tools & Libraries

- Python 3.x
- pandas
- numpy
- openpyxl (for Excel export)
- Jupyter Notebook

---

## About

These projects are part of my data analytics learning journey. The datasets used are publicly available (Kaggle / open data sources). Raw data files are not included in this repo only the cleaning logic.

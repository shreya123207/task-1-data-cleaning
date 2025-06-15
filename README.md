# task-1-data-cleaning
 Internship Project: Data Analyst Task

# Dataset Used:
Mall Customer Segmentation Data (`Mall_Customers.csv`)
## Steps I Performed:
1. Loaded the raw dataset using Pandas
2. Checked for missing values using `.isnull().sum()`  
   →  No missing values found
3.Checked for duplicates using `.duplicated().sum()`  
   →  Duplicates removed using `.drop_duplicates()`
4.Cleaned column names to lowercase and removed spaces
5. Standardized categorical values  
   → For example, made all `Gender` values start with a capital letter
6. Checked and corrected data types for numeric columns
7. Saved the cleaned data as `cleaned_mall_customers.csv`
#  Cleaned Output:
- `cleaned_mall_customers.csv` – Ready-to-use dataset
- No missing or duplicate values
- Consistent formatting and structure
Tools Used:
- Python
- Pandas
- Jupyter Notebook

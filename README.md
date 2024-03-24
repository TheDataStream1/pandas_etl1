# pandas_etl1
## Data Cleaning and Processing Script

This script performs data cleaning and processing on a Pandas DataFrame. It includes functions to fill missing values with the mean, drop duplicate rows based on a specified column, and remove outliers using a 2-standard deviation approach. The script then processes the DataFrame using these functions and prints the processed DataFrame.

### Usage

1. **Import Libraries:** The script imports NumPy and Pandas libraries.

2. **Create DataFrame:** A sample DataFrame `df` is created with columns 'id', 'A', 'B', and 'C'.

3. **Data Cleaning Functions:**
   - `fill_missing_values(df)`: Fills missing values in numeric columns with their mean.
   - `drop_duplicates(df, column_name)`: Drops duplicate rows based on the specified column.
   - `remove_outliers(df, column_list)`: Removes outliers from specified columns using a 2-standard deviation approach.

4. **Process DataFrame:** The script processes the DataFrame `df` using the defined functions in a chained manner using the `pipe` method.

5. **Print Result:** The processed DataFrame `df_processed` is printed to the console.

### Example Output

The script processes the sample DataFrame `df` to fill missing values, drop duplicates based on the 'id' column, and remove outliers from columns 'A' and 'B'. The processed DataFrame is then printed to the console.

### Requirements

- Python 3.x
- Pandas
- NumPy

# Packages

## Pandas
Definition: designed for data manipulation and analysis

### Handling Missing Data
- Is Null: df.isnull().sum() Counts null values per column
- Drop NA: df.dropna(subset=\[col], how='any') Removes rows with missing values
- Fill NA: df.fillna(value, method='ffill') Replace missing values with specified value
- Set Index: df.set_index() Restructures dataset based on set index values

### Data Cleaning & Transformation
- Drop Duplicates: df.drop_duplicates(subset=\[col]) Remove duplicate rows from a DataFrame
- Rename: df.rename(columns={'old' : 'new'}) Rename columsn using dictionary mapping
- As Type: df\[col].astype('category') Convert column data types
- Replace: df\[col].replace(\[old], \[new]) Replace values in DataFrame
- Reset Index: df.reset_index() Reset index to default numeric sequence
- Drop: df.drop(\[col], axis=1) Removes specified columns
- Strip: df.columns.str.strip() Strip whitespace from column names
- Interpolate: df.interpolate(method='linear')
- Sort Index: df.sort_index() Sort by Index
- Unique: df.unique() Get all unique values from a column or array
- Reshape: df.reshape() Reshapes arrays without changing data
- Nan to Num: df.nan_to_num() Reoplace NaN with a numeric value

### Time Series Data
- Resample: df.resamle('M').mean() Returns monthly average
- Rolling: df.rolling(window=7).mean() 
- Shift: df.shift(periods=1) Shifts values
- Date Range: pd.date_range('2024', periods=12, freq='M')
- As Frequency: df.asfreq('D', method='ffill')
- String Format Time: df\['date'].dt.strftime('%Y-%M-%D')

### Filtering
- Loc: df.loc\['row', 'col'] Selects data by labels/conditions
- ILoc: df.iloc\[index] Access data using integer positions
- Conditional Filtering: df\[df\['col'] > value] Filters rows based on a condition
- Query: df.query('column' > value) Filter using a condition
- Is In: df\['col'].isin(\['val1', 'val2']) Selects rows based on multiple values

### Importing
- Read CSV: pd.read_csv('file.csv') Loads data directly for a CSV
- Read Table: pd.read_table()  Loads data directly from a Table
- Read Excel: pd.read_excel('file.xlsx', sheet_name='name') Loads data directly from Excel
- Read SQL: pd.read_sql(query, connection) Loads data directly from a database
- Read Json: pd.read_json('file.json') Loads data directly from JSON
- Read Parquet: pd.read_parquet('file.parquet) Loads data from a parquet 
- Read HTML: pd.read_html() Loads web data directly from the web

### Local Data Initialization
- DataFrame: pd.DataFrame() Creates local dataset structure
- Series: pd.series() Creates sequences of data

### Merging Multiple Datasets
- Concat: pd.concat(\[df1, df2]) Concatenates multiple DataFrames
- Merge: pd.merge(df1, df2, on='key', how='left') Merges two DataFrames on a key column
- Join: df1.join(df2) Joins DataFrame on index
- Append: df1.append(df2) Appends rows of df2 to df1
- Pivot Tables: df.pivot_table(values, index, columns) Creates pivot table from data
- Pivot: df.pivot() Reshapes a DataFrame
- Melt: df.melt() Stack from wide to long
- Stack: df.stack() Pivot columns into indexes
- Group By: df.groupby('col').agg(\['mean']) Groups and applies aggregation function
- Sort Values: df.sort_values('col', ascending=False) Orders data by column values
- Apply: df.apply(lambda x: x\*2) Apply's a function to rows or columns

### Data Inspection
- Head: df.head() Shows first five rows of a DataFrame
- Tail: df.tail() Shows the last five rows of a DataFrame
- Info: df.info() Displays DataFrame info and data types
- Describe: df.describe() Shows summary statistics of numeric columns
- Shape: df.shape Returns dimensions of the DataFrame

### Data Statistics
- Mean: pd.mean() 
- Median: pd.median()
- Count: pd.count() Returnsa count of all non-null values
- Standard Deviation: pd.std()
- Maximum: pd.max()
- Minimum: pd.min()
- Correlation: df.corr(method='pearsons') Returns a correlation matrix
- Value Counts: df\[col].value_counts(normalize=True) Count unique values in a column
- Covariance: df.cov() Covariance matrix
- Quantile: df.quantile(\[0.25, 0.5, 0.75])
- Agg: df\[col].agg(\['mean', 'median', 'std'])

### String Operators
- Contains: df\['col'].str.contains('pattern')
- Extract: df\['col'].str.extract()
- Split: df\['col'].str.split(',').str\[0]
- Lower: df\['col'].str.lower()
- String: df\['col'].str.strip()
- Replace: df\['col'].str.replace()

## NumPy
Definition: Foundational package for scientific computing

## Seaborn
Definition: Designed for statistical graphics and works seamlessly with Pandas DataFrames.

## MatPlotLib
Definition: Creates static, animated, and interactive visualizations
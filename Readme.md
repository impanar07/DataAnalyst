The dataset, `car_prices.csv`, includes detailed information about used car listings such as:

- `year`: Year of manufacture
- `make`, `model`, `trim`, `body`, `transmission`: Vehicle specifications
- `vin`: Vehicle Identification Number
- `state`: Location of sale
- `condition`: Numeric rating of car condition
- `odometer`: Mileage of the car
- `color`, `interior`: Exterior and interior colors
- `seller`: Seller name or dealership
- `mmr`: Market value estimate
- `sellingprice`: Actual transaction price
- `saledate`: Date of sale

- Data Cleaning Process

Steps performed in the notebook:
- Loaded the dataset using `pandas`
- Checked for and handled missing values
- Dropped duplicate records
- Standardized categorical text fields (lowercase, no whitespace issues)
- Converted date columns (e.g., `saledate`) to datetime format
- Verified and fixed data types for numerical and date fields

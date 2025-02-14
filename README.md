#### *NAME* : AMAN KUMAR
#### *COMPANY* :  CODTECH IT SOLUTIONS
#### *INTERN ID* : CT12DS3015
#### *DOMAIN* : DATA SCIENCE
#### *DURATION* : DECEMBER 15th, 2024 to FEBRUARY 15th, 2025
#### *MENTOR* : NEELA SANTHOSH

# ETL Pipeline for Data Preprocessing, Transformation, and Loading

## Objective
This project provides an automated ETL (Extract, Transform, Load) pipeline using Python, Pandas, and Scikit-Learn. The script reads raw data from a CSV file, preprocesses it by handling missing values and scaling features, transforms categorical variables, and then saves the cleaned data for further analysis or modeling.

## Key Activities

#### Steps in the ETL Process

### 1. Extract: Load Data
- The script reads the raw data from a CSV file (`data.csv.csv`).
- Displays an initial summary including column types, missing values, and sample records.

### 2. Transform: Data Preprocessing
- Identifies numerical and categorical features.
- Prepares a preprocessing pipeline:
  - **Numerical Data:** Imputes missing values with the mean and scales using `StandardScaler`.
  - **Categorical Data:** Imputes missing values with the most frequent value and encodes using `OneHotEncoder`.
- Applies transformations to the dataset.

### 3. Load: Save Processed Data
- The transformed dataset is converted into a DataFrame.
- Saves the processed data into a new CSV file (`processed_data.csv`).
- Prints confirmation that the ETL process has been completed.

## Prerequisites
Ensure you have the following Python libraries installed:
```bash
pip install pandas scikit-learn
```

## Running the ETL Pipeline
1. Place the raw data file (`data.csv.csv`) in the correct directory.
2. Run the script:
   ```bash
   python etl_pipeline.py
   ```
3. The processed data will be saved as `processed_data.csv`.

## Key Insights
- The cleaned and transformed dataset is saved as `processed_data.csv`.
- Ready for further analysis, modeling, or visualization.

## Contact
For any questions or improvements, feel free to contribute or reach out!

# Experiment 13: Data Wrangling

## Aim
To understand and implement data wrangling techniques using Python. The goal of this experiment is to clean, preprocess, and transform raw data into a structured and usable format by handling missing values, correcting inconsistencies, and standardizing data for further analysis.

## Theory
Data wrangling, also known as data preprocessing, is a crucial step in the data analysis pipeline. Raw data collected from various sources is often incomplete, inconsistent, and noisy. Without proper cleaning and transformation, such data can lead to incorrect analysis and misleading results.

This experiment focuses on key concepts of data wrangling:

### 1. Missing Data Handling
Missing data is a common issue in datasets and can occur due to various reasons such as data entry errors or incomplete data collection. It is important to identify and handle missing values effectively.
- Detection of missing values is performed using logical checks.
- Missing values can be removed or replaced depending on the situation.
- Common strategies include filling missing values with statistical measures such as mean or median.

### 2. Data Cleaning
Data cleaning involves identifying and correcting errors or inconsistencies in the dataset.
- Invalid entries such as special symbols or placeholders are replaced with appropriate values.
- Duplicate or incorrect entries are handled to maintain data integrity.
- Ensures that the dataset is accurate and reliable.

### 3. Data Type Conversion
In many datasets, numerical values may be stored as text due to improper data entry.
- Converting such values into appropriate numeric formats is essential for analysis.
- Errors during conversion are handled carefully to avoid data loss.

### 4. Data Transformation and Standardization
Data often contains inconsistencies in formatting, especially in categorical and textual data.
- Text values are standardized to maintain uniformity (e.g., converting all text to uppercase).
- Date formats are converted into a consistent and readable structure.
- These transformations help in better interpretation and analysis of data.

### 5. Statistical Imputation
When handling missing numerical data:
- Mean is used when the data is evenly distributed.
- Median is preferred when the data contains outliers.
This ensures that the dataset remains balanced and meaningful.

### 6. Importance of Data Wrangling
- Improves data quality and reliability
- Enhances accuracy of analysis
- Makes data suitable for visualization and modeling
- Saves time in later stages of data processing

## Conclusion
This experiment demonstrates the importance of data wrangling as a foundational step in data analysis. By applying various preprocessing techniques, raw and unstructured data was transformed into a clean, consistent, and structured format.

The process included identifying missing values, replacing invalid data, converting data types, and standardizing formats. These steps significantly improved the quality and usability of the dataset.

Overall, data wrangling ensures that datasets are accurate, complete, and ready for further analytical tasks such as visualization, machine learning, and decision-making. Mastering these techniques is essential for anyone working in the field of data science and analytics.

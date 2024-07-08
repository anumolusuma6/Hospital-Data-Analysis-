# Hospital-Data-Analysis-Project
### Purpose
This project involves analyzing simulated hospital data related to patient admissions across surgical and medical departments. The goal is to perform data preprocessing, merging, and analysis to derive meaningful insights from the dataset.

### Project Overview
In this assessment, you will work with three main datasets:

- admissions_surg.csv: Contains information about patients admitted to the surgical department.
- admissions_med.csv: Contains information about patients admitted to the medical department.
- imaging.csv: Provides medical imaging data results collected during patient admissions.
### Tasks Covered
- Data De-identification

Read in the CSV files and perform de-identification to replace personal health identifiers with unique IDs for privacy reasons.
De-identify the datasets (admissions_surg.csv, admissions_med.csv, imaging.csv) and display the first few rows of each.
- Data Merging and Calculation

Create a merged dataframe (admissions_img) consisting of admissions data from surgical and medical departments, merged with imaging data using the new unique IDs (DE_ID).
Calculate the mean length of stay for each department based on admission and discharge dates.
- Data Transformation and Filtering

Filter the imaging data to retain only the first performed test for each test name and transform it into wide format.
Remove rows from admissions_img with significant missing data and report the missing rates.
- Data Quality Assessment

Analyze the admdad file for possible data quality issues related to hospital admissions and patient characteristics.
Propose solutions to remediate identified data quality issues.
### Getting Started
To replicate the analysis:

Clone this repository.
Install the necessary dependencies and libraries (Python/R packages as required).
Execute the scripts or notebooks provided in each task's directory to perform data preprocessing, merging, analysis, and quality assessment.
Files Included
admissions_surg.csv
admissions_med.csv
imaging.csv
Q7_admdad.csv (for data quality assessment)
Technologies Used
Python/R (Pandas, NumPy, etc.)
Jupyter Notebook (optional)
Git (version control)
### Contributions
Contributions and feedback are welcome! Feel free to submit issues or pull requests for improvements.

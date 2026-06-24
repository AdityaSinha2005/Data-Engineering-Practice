# ETL Pipeline using Python

## Overview

This project demonstrates a basic ETL (Extract, Transform, Load) pipeline using Python and Pandas.

The pipeline extracts data from multiple source files, performs data cleaning and transformation operations, and generates a consolidated dataset for further analysis.

This project was developed as part of my Data Engineering learning journey to understand the fundamentals of data ingestion, transformation, and processing.

---

## Objective

The goal of this project is to:

* Extract data from multiple file formats
* Transform and standardize the data
* Consolidate information into a single dataset
* Generate execution logs
* Export the transformed data

---

## Technologies Used

* Python
* Pandas
* XML Processing
* JSON Processing
* CSV Processing

---

## Source Files

The project processes data from multiple source formats:

### CSV Files

```text
source1.csv
source2.csv
source3.csv
```

### JSON Files

```text
source1.json
source2.json
source3.json
```

### XML Files

```text
source1.xml
source2.xml
source3.xml
```

---

## ETL Workflow

### 1. Extract

Data is extracted from multiple source files:

* CSV
* JSON
* XML

The extracted datasets are loaded into Pandas DataFrames.

```text
Source Files
     ↓
Pandas DataFrames
```

---

### 2. Transform

The extracted data is cleaned and standardized.

Typical transformation operations include:

* Data formatting
* Unit conversion
* Data normalization
* Data consolidation

```text
Raw Data
     ↓
Cleaning
     ↓
Transformation
     ↓
Standardized Data
```

---

### 3. Load

The transformed dataset is exported into a final output file.

Output:

```text
transformed_data.csv
```

Execution logs are also maintained in:

```text
log_file.txt
```

---

## Project Structure

```text
01_ETL_Pipeline/
│
├── data/
│   ├── source1.csv
│   ├── source1.json
│   ├── source1.xml
│   ├── source2.csv
│   ├── source2.json
│   ├── source2.xml
│   ├── source3.csv
│   ├── source3.json
│   └── source3.xml
│
├── etl_code.py
├── transformed_data.csv
├── log_file.txt
└── README.md
```

---

## How to Run

### Install Dependencies

```bash
pip install pandas
```

### Execute the Script

```bash
python etl_code.py
```

---

## Output Files

### Transformed Dataset

```text
transformed_data.csv
```

Contains the final processed and consolidated dataset.

### Log File

```text
log_file.txt
```

Tracks ETL execution details and timestamps.

---

## Learning Outcomes

Through this project, I practiced:

* ETL Pipeline Development
* Data Extraction
* Data Transformation
* Data Loading
* Pandas Data Processing
* Working with CSV, JSON, and XML files
* Logging and Monitoring

---

## Author

Aditya Sinha

B.Tech CSE | KIIT University

Learning Data Engineering, Backend Development, and Software Engineering.

# NumPy Matrix Analyzer

A command-line tool for reading numeric data from CSV files, converting them into NumPy matrices, and generating statistical summaries.

## ## Features

- Validates input file availability
- Reads and parses CSV data
- Converts strings into numeric lists
- Builds NumPy 2D arrays
- Generates:
  - Whole dataset summary
  - Column-wise statistical summary
- Configurable delimiter
- Command-line arguments support

---

## ## Project Structure

```
NUMPYMATRIX_ANALYZER/
│
├── main.py
├── utils/
│   ├── os_utils.py
│   ├── list_utils.py
│   ├── type_utils.py
│   ├── numpy_utils.py
│
├── assets/
│   ├── numpy_random_numbers.csv
│
└── README.md
```

---

## ## Installation

### ### 1. Clone or extract the project

```
unzip NUMPYMATRIX_ANALYZER.zip
cd NUMPYMATRIX_ANALYZER
```

### ### 2. Install dependencies

```
pip install -r requirements.txt
```

---

## ## Usage

### ### Run with default CSV file

```
python main.py
```

### ### Run with custom input file

```
python main.py --input_file "path/to/file.csv"
```

### ### Run with custom delimiter

```
python main.py --delimiter ";"
```

---

## ## Output Includes

✅ File availability status  
✅ NumPy matrix display  
✅ Aggregated dataset statistics  
✅ Column-wise summaries  
✅ Transposed first-column formatted output  

---

## ## Requirements

See `requirements.txt`

---

## ## Author

aadhimarumalla@gmail.com


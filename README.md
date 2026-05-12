# Data Scraping Python

## Overview

This project uses Python to scrape and process data on the largest companies in the Philippines from Wikipedia.

The workflow includes extracting HTML table data, cleaning and organizing the dataset with Pandas, and exporting the final dataset into CSV format for analysis and reporting.

Built and tested using Jupyter Notebook.

---

## Features

* Extracts company data directly from Wikipedia
* Parses HTML tables using BeautifulSoup
* Cleans and structures data using Pandas
* Exports processed data into CSV format
* Runs entirely in Jupyter Notebook

---

## Technologies Used

* Python
* BeautifulSoup4
* Requests
* Pandas
* Jupyter Notebook

---

## Data Source

Wikipedia – List of Largest Companies in the Philippines

https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_Philippines

---

## Project Structure

```text
data-scraping-python/
│
├── data/
│   └── Top_Company_PH.csv
│
├── notebook/
│   └── TopCompaniesInPH_WebScraping.ipynb
│
└── README.md
```

---

## Installation

Install the required libraries:

```bash
pip install beautifulsoup4 requests pandas notebook
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/cjbugtong/data-scraping-python.git
```

### 2. Open the Project Folder

```bash
cd data-scraping-python
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the Notebook File

```bash
notebook/TopCompaniesInPH_WebScraping.ipynb
```

### 5. Run the Notebook Cells

Execute the notebook step by step to scrape, process, and export the dataset.

---

## Output

Processed dataset exported as:

```text
data/Top_Company_PH.csv
```

---

## Skills Demonstrated

* Web Scraping
* Data Extraction
* Data Cleaning
* Data Processing
* CSV Exporting
* Working with HTML Tables
* Python Data Analysis Workflow

---

## Author

Christian Joy D. Bugtong

---

## Notes

This project was developed to strengthen practical skills in Python web scraping and data processing using real-world datasets.

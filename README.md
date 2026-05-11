# Data Scraping Python

Python web scraping project that extracts data on top companies in the Philippines from Wikipedia using BeautifulSoup, Requests, and Pandas. The project collects, cleans, organizes, and exports structured company data into CSV format for analysis and reporting.

## Features

* Scrapes company data directly from Wikipedia
* Extracts table headers and company records
* Cleans and formats scraped data
* Stores data in a Pandas DataFrame
* Exports results into a CSV file

## Technologies Used

* Python
* BeautifulSoup4
* Requests
* Pandas

## Website Source

Data scraped from:

[Wikipedia - List of Largest Companies in the Philippines](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_Philippines?utm_source=chatgpt.com)

## Installation

Install the required libraries:

```bash
pip install beautifulsoup4 requests pandas
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/cjbugtong/data-scraping-python.git
```

2. Open the project folder:

```bash
cd data-scraping-python
```

3. Run the script:

```bash
python scraping.py
```

## Output

The scraped data will be exported as:

```bash
Top_Company_PH.csv
```

## Purpose

This project focuses on:

* Web scraping from Wikipedia
* Extracting structured table data
* Cleaning raw HTML data
* Converting data into CSV format using Pandas

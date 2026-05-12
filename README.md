# Data Scraping Python

## About This Project

In this project, I used Python to scrape data about the largest companies in the Philippines from Wikipedia.

The project focuses on collecting company data from an HTML table, cleaning and organizing the information, and exporting the final dataset into CSV format using Pandas.

The project was built and tested inside Jupyter Notebook.

---

## What I Did

### Web Scraping

I used Python libraries such as BeautifulSoup and Requests to extract company information directly from Wikipedia.

The scraping process includes:

* Sending requests to the website
* Reading the HTML content
* Locating the target table
* Extracting table headers and rows
* Converting the extracted data into a structured format

---

### Data Cleaning and Processing

After scraping the data, I cleaned and organized it using Pandas.

This includes:

* Formatting table data properly
* Removing unnecessary spaces or values
* Organizing the dataset into rows and columns
* Converting the data into a Pandas DataFrame

---

### Exporting the Dataset

After processing the data, I exported the final dataset into a CSV file for future analysis and reporting.

---

## Files in This Project

* `TopCompaniesInPH_WebScraping.ipynb` – Main Jupyter Notebook file containing the web scraping process
* `Top_Company_PH.csv` – Exported CSV dataset

---

## Technologies Used

* Python
* BeautifulSoup4
* Requests
* Pandas
* Jupyter Notebook

---

## Website Source

Data scraped from Wikipedia:

```text
https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_Philippines
```

---

## What I Learned

* How web scraping works using Python
* How to extract HTML table data using BeautifulSoup
* How to clean and organize data using Pandas
* How to export datasets into CSV format
* How to work with Jupyter Notebook for data projects

---

## How to Run

1. Install the required libraries

```bash
pip install beautifulsoup4 requests pandas notebook
```

2. Clone the repository

```bash
git clone https://github.com/cjbugtong/data-scraping-python.git
```

3. Open the project folder

```bash
cd data-scraping-python
```

4. Start Jupyter Notebook

```bash
jupyter notebook
```

5. Open the notebook file

```bash
TopCompaniesInPH_WebScraping.ipynb
```

6. Run the notebook cells step by step

---

## Output

The project exports the scraped data into:

```bash
Top_Company_PH.csv
```

---

## Sample Data Collected

* Company Name
* Industry
* Revenue
* Headquarters
* Rank

---

## Notes

This project is part of my practice in improving my Python, web scraping, and data processing skills.

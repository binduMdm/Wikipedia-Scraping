# Wikipedia Web Scraping Project

This project demonstrates how to scrape data from Wikipedia using Python and the BeautifulSoup library.

## Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library

## How to Run

1. Clone the repository: git clone https://github.com/binduMdm/Wikipedia-Scraping.git
2. Install the required libraries: pip install requests beautifulsoup4
3. Run the Python script to start scraping: webscraping_1.ipynb
   
## Description

This script scrapes data from the [Wikipedia page](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue) 
to extract company data, such as rank, name, industry, revenue, etc.


Project Overview
In this project, I scrape a table from the Wikipedia page on the largest companies in the United States by revenue. The table includes the following columns:

Rank: The company's position based on revenue.

Name: The name of the company.

Industry: The sector in which the company operates.

Revenue (USD millions): The annual revenue in millions of dollars.

Revenue growth: The percentage growth of the company’s revenue.

Employees: The number of employees working at the company.

Headquarters: The location of the company’s headquarters.

I used the BeautifulSoup library to parse and extract this information from the HTML content of the page.

Description
This script:

Fetches the HTML content of the Wikipedia page using the requests library.

Parses the HTML with BeautifulSoup to find the relevant table.

Extracts the data from the table rows and columns.

Stores the data in a Pandas DataFrame and writes it to a CSV file for easy access.

The CSV file contains the list of companies and their relevant data.

Code Structure
webscraping_1.ipynb: This is the main Jupyter notebook containing the Python code to scrape and process the data.

Wiki_Companies3.csv: This is the CSV file that stores the extracted data from the Wikipedia page.





# Web-Crawling-Task


## Overview

This project is designed to scrape contractor data from the Muqawil website, a resource for finding contractors in various fields. Utilizing Python libraries such as `requests`, `BeautifulSoup`, and `Selenium`, the project aims to collect vital information about contractors, including their names, membership numbers, city names, and email addresses. 

## Requirements

To run this project, you will need to have Python 3.x installed, along with the following libraries:

- `requests`
- `BeautifulSoup`
- `Selenium`
- `pandas`
- `markdown`
- `chromadb`
- `HuggingFaceEmbeddings`
- `langchain`



# Usage

The project begins by scraping contractor data from multiple pages of the Muqawil website. The code fetches data for a defined number of pages, allowing you to change this parameter based on your needs.


# Data Scraping
The scraping process is initiated by defining the base URL and then looping through each page to gather contractor information. Each contractor's details, including their company name, membership number, city, and email, are extracted and stored in a list. The collected data is then saved to a CSV file named Test.csv.

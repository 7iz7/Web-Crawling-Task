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



## Usage

The project begins by scraping contractor data from multiple pages of the Muqawil website. The code fetches data for a defined number of pages, allowing you to change this parameter based on your needs.


## Data Scraping
The scraping process is initiated by defining the base URL and then looping through each page to gather contractor information. Each contractor's details, including their company name, membership number, city, and email, are extracted and stored in a list. The collected data is then saved to a CSV file named Test.csv.


## Markdown File Generation
In addition to saving the data as a CSV file, the project generates individual markdown files for each contractor. This makes it easier to format and process the information later on.
The following code creates a directory for the markdown files and writes the collected data into separate files:



## Embedding and Querying
The project leverages embeddings to create a searchable database of the markdown files. This allows users to query the database efficiently. The query function utilizes the Chroma database and retrieves similar documents based on user queries.


## Challenges Encountered

During the development of this project, I faced several challenges. Initially, I attempted to extract email addresses using Selenium but encountered various issues that hindered my progress. Additionally, I struggled with implementing Streamlit for creating an interactive user interface.


# Conclusion

This project serves as a foundational approach to web scraping and data querying using modern techniques such as RAG. While it successfully collects contractor data from the Muqawil website, there is room for further enhancement. Future improvements could focus on expanding the scope of data scraping and refining the user interface for better interaction.

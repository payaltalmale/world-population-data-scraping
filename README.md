# world-population-data-scraping

This project aims to scrape population data from the Worldometer website using Python and BeautifulSoup. The extracted data includes country name, population count, yearly change, and land area.

## Project Overview

- The project uses the `requests` library to send a GET request to the target URL and retrieves the HTML content.
- The HTML content is then parsed using BeautifulSoup to extract the desired population data from the table.
- The extracted data is stored in a CSV file named `population_data.csv`.
- The project utilizes the `csv` library to create and write the extracted data to the CSV file.
- The CSV file is encoded in UTF-8 to support different character sets.
- The project is implemented in Python and uses the popular BeautifulSoup library for web scraping.

## Dependencies

The project has the following dependencies:

- Python 3
- BeautifulSoup
- requests


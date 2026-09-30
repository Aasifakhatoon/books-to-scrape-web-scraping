# Books to Scrape — Web Scraping Project

A Python web scraping project that collects book titles and prices from the Books to Scrape website and exports the data to Excel.

## Project Overview

This project demonstrates a basic end-to-end web scraping workflow:

- Scrape book data from 50 pages
- Extract book titles and prices
- Store the scraped data in a Pandas DataFrame
- Clean and convert price data to numeric values
- Validate the collected data
- Export the final dataset to Excel

## Data Collected

- Book title
- Book price

## Tools Used

- Python
- Requests
- BeautifulSoup
- Pandas

## Output

The project produces an Excel file containing 1,000 scraped book records:

`books_data.xlsx`

## Files

- [Web_scraping.ipynb](./Web_scraping.ipynb) — scraping and data-processing workflow
- [books_data.xlsx](./books_data.xlsx) — final scraped dataset

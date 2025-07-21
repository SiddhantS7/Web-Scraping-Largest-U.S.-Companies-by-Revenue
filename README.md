# Web Scraping: Largest U.S. Companies by Revenue

This project extracts structured data from the Wikipedia page [List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue) using Python. The script is implemented in a Jupyter notebook optimized for Google Colab and utilizes the `requests`, `BeautifulSoup`, and `pandas` libraries.

## Objective

To automate the extraction of tabular data containing the largest U.S. companies ranked by revenue and store the data in a clean, structured CSV format for further analysis or integration.

## Technologies Used

- Python 3
- BeautifulSoup (bs4)
- requests
- pandas
- Google Colab (runtime environment)

## Features

- Sends an HTTP request to the target Wikipedia page.
- Parses the HTML content to identify and extract the relevant table.
- Extracts column headers and row data.
- Stores the results in a pandas DataFrame.
- Exports the data as a CSV file.
- Provides download functionality within Google Colab.

## File Structure

- `scrape_companies.ipynb`: Notebook containing the full scraping and export workflow.
- `Companies.csv`: Output file containing the extracted data.
- `README.md`: Project documentation.

## How to Use

1. Open the `scrape_companies.ipynb` notebook in [Google Colab](https://colab.research.google.com/).
2. Execute all cells sequentially.
3. The CSV file (`Companies.csv`) will be generated and downloaded to the local system.

## Installation (Local Environment)

To run this script outside of Colab:

```bash
pip install beautifulsoup4 requests pandas


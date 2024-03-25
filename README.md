# Web Scraping Project: QuotesToScrape

## Overview
This project is a web scraping exercise focused on extracting data from the QuotesToScrape website (https://quotes.toscrape.com/). It retrieves quotes along with their authors, author IDs, tags, and author links. The scraped data can be used for various purposes such as analysis, building databases, or developing applications related to quotes and authors.

## Features
- Scrapes quotes, author names, author IDs, tags, and author links from the QuotesToScrape website.
- Outputs the scraped data into a structured format for further processing or storage.

## Requirements
- Python 3.11.5
- Libraries:
  - BeautifulSoup4
  - Requests

## Usage
### Running the Jupyter Notebooks
If you prefer using Jupyter Notebooks, follow these steps:

1. Open Jupyter Notebook by running the following command in your terminal or command prompt:

    ```bash
    jupyter notebook
    ```

2. Navigate to the directory where you cloned this repository.

3. Open each of the `.ipynb` files:
    - `page_scraper.ipynb`
    - `scrape_quotes.ipynb`
    - `scrape_entire_website.ipynb`

4. Follow the instructions within each notebook to execute the code cells and perform the scraping process.

#### Note:
- In `page_scraper.ipynb`, the notebook is responsible for making a request to the website and storing the HTML content in the `main.html` file.
- In `scrape_quotes.ipynb`, the notebook scrapes quotes from a single webpage of the website.
- In `scrape_entire_website.ipynb`, the notebook scrapes quotes from multiple pages of the website, extracting data from the entire website.

## Output
The scraped data will be saved in a structured format (e.g., CSV, JSON) within the project directory. The specific output format can be customized based on requirements.

## Contributing Guidelines
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request. Before contributing, please read the [Contributing Guidelines](CONTRIBUTING.md) for instructions on how to contribute to this project.

## References
- This project was inspired by the QuotesToScrape website created by ScrapingHub (https://quotes.toscrape.com/).
- Special thanks to the creators of BeautifulSoup and Requests for their invaluable contributions to web scraping in Python.


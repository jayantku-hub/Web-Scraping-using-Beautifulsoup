# Web-Scraping-using-Beautifulsoup

# Books.toscrape.com Web Scraper

## Project Purpose
This project is a simple web scraper designed to extract book titles and their corresponding prices from the website [books.toscrape.com](https://books.toscrape.com/). The extracted data is then organized and saved into a CSV file for easy access and analysis.

## Setup Instructions
To set up and run this project, you need to have Python installed. Additionally, you will need the following Python libraries:

*   `requests`: Used for making HTTP requests to fetch web page content.
*   `beautifulsoup4` (bs4): Used for parsing HTML and XML documents.
*   `pandas`: Used for data manipulation and creating DataFrames.

YouYou can install these libraries using pip:

```bash
pip install requests beautifulsoup4 pandas
```

## How to Run
1.  **Clone the repository (if applicable) or save the Python script.**
2.  **Ensure all required libraries are installed** as per the setup instructions.
3.  **Execute the Python script.** For example, if your script is named `scraper.py`, run it from your terminal:

    ```bash
    python scraper.py
    ```

Upon successful execution, the script will perform the web scraping process and generate a `books_data.csv` file in the same directory.

## Output File: `books_data.csv`
The `books_data.csv` file contains the scraped data in a structured format. Each row in the CSV represents a single book, with the following columns:

*   **Book Title**: The title of the book.
*   **Price**: The price of the book, including its currency symbol.



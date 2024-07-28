# Gardena Product Scraper

This project is designed to scrape product details from the Gardena website's "combisystem" section. Using Selenium and BeautifulSoup, the script extracts information such as product titles, descriptions, specifications, and images, and stores the data in an Excel file.

## Features

- Handles cookie popups.
- Scrolls and loads more products dynamically.
- Extracts product titles, descriptions, specifications, and images.
- Saves the scraped data into an Excel file.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Selenium
- BeautifulSoup
- Requests
- Pandas
- WebDriver for your browser (e.g., ChromeDriver for Google Chrome)

## Installation

1. Clone this repository:
    ```bash
    [git clone https://github.com/your-username/gardena-product-scraper.git](https://github.com/AneesFayyaz/Gardena-Web-Scraper/tree/main)
    ```

2. Navigate to the project directory:
    ```bash
    cd gardena-product-scraper
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Ensure you have the WebDriver for your browser installed and available in your PATH.

2. Update the `base_url` and product page URL in the script if necessary.

3. Run the script:
    ```bash
    python scrape_gardena.py
    ```

4. The script will open the browser, navigate to the Gardena "combisystem" section, and start scraping product details.

5. The scraped data will be saved into an Excel file named `combisystem.xlsx` in the project directory.

## Project Structure

- `scrape_gardena.py`: The main script containing the web scraping logic.


## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project uses the following open-source libraries:

- [Selenium](https://selenium.dev/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- [Pandas](https://pandas.pydata.org/)


# Selenium Web Crawler - Price Tracker

## Overview
This project is a Selenium-based web crawler that scrapes vehicle price and details from the website [https://om.digitalmall.app/](https://om.digitalmall.app/). It automates browser interactions to navigate the site, extract vehicle information, and save the data into a CSV file.

## Features
- Uses Selenium WebDriver with Chrome to automate browsing.
- Extracts vehicle details including title, model year, transmission, fuel type, location, price, and publish date.
- Handles dynamic page content with explicit waits and scrolling.
- Avoids duplicate URL visits during scraping.
- Saves data incrementally to `car_data.csv`.

## Requirements
- Python 3.x
- Selenium
- BeautifulSoup4
- pandas
- lxml
- ChromeDriver compatible with your Chrome browser version

## Installation
1. Clone the repository.
2. Install the required Python packages:
3. Download ChromeDriver from [https://sites.google.com/chromium.org/driver/](https://sites.google.com/chromium.org/driver/) and ensure it is accessible in your system PATH or project directory.

## Usage
Run the script with:
```bash
  python selenium_web_crawler_-_price_tracker.py
```
The script will open a Chrome browser, navigate the target website, and scrape vehicle data. The results will be appended to `car_data.csv`.

## Notes
- The script relies on specific page structure and CSS selectors; changes to the website may require updates to the code.
- Ensure the ChromeDriver version matches your installed Chrome browser version.
- The script includes delays and scrolling to handle dynamic content loading.

## License
This project is open-source and free to use.

## Author
- M Burhan ud din

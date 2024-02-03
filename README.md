# Google Maps Scraper

This Python script uses Selenium WebDriver to scrape data from Google Maps based on user-defined search keywords. The data includes names, statuses, addresses, URLs, and geographical coordinates (latitude and longitude) of the locations found in the search results.

## Features

- Search Google Maps using custom keywords.
- Automatically scroll through search results to gather more data.
- Extract detailed information including name, status (e.g., Open or Closed), address, and URL of each location.
- Retrieve geographical coordinates (latitude and longitude) for each location.
- Export the collected data to a CSV file for further analysis or usage.

## Requirements

- Python 3
- Selenium WebDriver
- Pandas library
- A WebDriver compatible with your browser (e.g., ChromeDriver for Google Chrome, EdgeDriver for Microsoft Edge)

## Installation

1. Ensure Python 3 is installed on your system.
2. Install Selenium:
   ```bash
   pip install selenium
   ```
3. Install Pandas:
   ```bash
   pip install pandas
   ```
4. Download the appropriate WebDriver for your browser and ensure it's in your PATH or specify its path in the script.

## Usage

1. Run the script.
2. Enter your search keyword when prompted.
3. The script will automatically begin scraping data from Google Maps.
4. After completion, a CSV file containing the scraped data will be saved in the specified path.

## CSV File Output

The output CSV file will have the following columns:

- `Name`: The name of the location.
- `Status`: The current status (e.g., Open, Closed, etc.).
- `Latitude`: Geographical latitude of the location.
- `Longitude`: Geographical longitude of the location.
- `Address`: The physical address of the location.
- `URL`: The Google Maps URL of the location.

## Disclaimer

This script is intended for educational purposes only. Ensure compliance with Google Maps Terms of Service before using this script for scraping data.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/fatimaazfar/Google-Maps-Scraper/issues) if you want to contribute.

## Acknowledgments

- Selenium WebDriver for providing the tools to automate web browser interaction.
- The Python community for continuously supporting and enriching the Python ecosystem.

## Author

- **Fatima Azfar** - *Initial work* - [fatimaazfar](https://github.com/fatimaazfar)

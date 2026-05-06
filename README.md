# Amazon Web Scraping

Web scraping using Python to extract product information from Amazon.

## Overview

This project demonstrates web scraping techniques to collect product data (title, price, description) from Amazon. The scraped data is saved to a CSV file and can be monitored over time.

## Features

- Scrapes product title, price, and description from Amazon
- Stores data in CSV format with timestamps
- Monitors price changes over time
- Email notification system when prices drop below target threshold
- Automated price checking at scheduled intervals

## Libraries Used

- **BeautifulSoup4** - HTML parsing and web scraping
- **requests** - HTTP requests to fetch web pages
- **pandas** - Data manipulation and CSV operations
- **csv** - CSV file reading and writing
- **datetime** - Date and time handling
- **smtplib** - Sending email notifications
- **time** - Time-based operations and delays

## Installation

```bash
pip install beautifulsoup4 requests pandas
```

## Usage

1. Update the Amazon product URL in the script
2. Configure email credentials for price alerts (optional)
3. Run the Jupyter Notebook or Python script
4. Data will be saved to `Amazon Web scrap.csv`

## Files

- `Amazon Web Scraping Code.ipynb` - Main scraping script (Jupyter Notebook)
- `Amazon_Web_Scraping.ipynb` - Detailed implementation
- `Amazon Web scrap.csv` - Output data file

## Legal Notice

This project is for educational purposes only. Ensure compliance with:
- Amazon's Terms of Service
- robots.txt guidelines
- Local data privacy regulations
- Respectful request rates to avoid overloading servers

## License

This project is open source and available for educational use.

# E-commerce Web Scraper

## Overview
This is a Python-based web scraper designed to extract product links from e-commerce websites like Ajio and Myntra. It uses Selenium for dynamic content loading and BeautifulSoup for HTML parsing.

## Features
- Supports multiple e-commerce websites (Ajio, Myntra)
- Handles both infinite scrolling and paginated navigation
- Extracts product links from category pages
- Uses headless browsing for efficiency

## Requirements
Ensure you have the required dependencies installed:

```sh
git clone git@github.com:ChetanSinha/ecommerce_webscrapper.git
cd ecommerce_webscraper
pip install -r requirements.txt
```

## Usage
Run the scraper by specifying the target website:

## Configuration
The scraper configurations for different websites are stored in the script:

- `base_url`: The homepage of the target site
- `categoryListClass`: Class name for category listing
- `isInfiniteScroll`: Boolean indicating infinite scrolling
- `pageClass`: Class for product listing container
- `linkClass`: Class for extracting product links
- `nextPageClass`: Class for pagination button

If a new domain needs to be added, simply add its configuration to the script.

## Output
The scraper will return a list of product links extracted from the specified e-commerce website.

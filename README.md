# Infinite Image Scroll Scraper

This project is a web scraper designed to extract image data from an infinitely scrolling webpage. It uses Selenium for automated scrolling and BeautifulSoup for data extraction. The script downloads images and saves metadata such as tags, likes, and comments into a CSV file.

## Features

- Automates infinite scrolling on a webpage.
- Extracts image URLs, tags, likes, and comments.
- Downloads images to a local directory.
- Saves metadata into a CSV file.

## Requirements

Make sure you have the following dependencies installed:

```bash
pip install selenium beautifulsoup4 pandas tqdm requests

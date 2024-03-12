# Quotes Scraper

This project is a web scraper that collects quotes from "https://quotes.toscrape.com/". It uses Scrapy, a powerful web-crawling framework, to extract quotes, authors, and tags, as well as detailed information about authors. The scraped data is saved into JSON files for easy access and manipulation.

## Features

- Scrapes quotes, their authors, and tags.
- Collects detailed author information including fullname, birth date, and description.
- Pagination support to crawl through all pages of quotes.
- Saves scraped data into two separate JSON files: `quotes.json` and `authors.json`.

## Requirements

- Python 3
- Scrapy

## Installation

Ensure you have Python 3 installed on your system. Then, install Scrapy using pip:

```bash
pip install scrapy

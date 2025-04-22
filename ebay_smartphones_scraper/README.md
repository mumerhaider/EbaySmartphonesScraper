# 📱 eBay Refurbished Smartphone Scraper

A Python web scraping project that scrapes refurbished smartphone listings from eBay across multiple pages.

## 🚀 Features

- Scrapes multiple pages
- Extracts:
  - Title
  - Price
  - Rating
  - Items Sold
  - Condition (from title)
  - Timestamp
- Saves results to a CSV file

## 📊 Sample Output

| Title | Condition | Price | Rating | Items Sold | TimeStamp |
|-------|-----------|-------|--------|------------|-----|

## 🛠 How to Run

```bash
pip install -r requirements.txt
cd src
python scraper.py
```

The scraped data will be saved in `data/ebay_smartphones.csv`.

Here’s a preview of the scraped data stored in the CSV:

![Sample CSV Output](screenshots/sample_output.png)


## 📦 Tech Stack

- Python
- BeautifulSoup
- Requests

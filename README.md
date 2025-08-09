# WHO-disease-outbreak-scraper

## Overview
This project aims to scrape data from the **WHO Disease Outbreak News** page using Python and BeautifulSoup. The intended output is a structured CSV file, which can later be used for SQL analysis and dashboard creation in Power BI.

> **Note:** Web scraping is in progress. Currently, the code is capable of fetching the WHO page and displaying the HTML via `soup.prettify()`. Extraction logic will be refined in future iterations.

## Project Structure

## Steps Taken
1. **Fetch WHO page** using `requests.get`:
   ```python
   response = requests.get("https://www.who.int/emergencies/disease-outbreak-news")

## Parse HTML with BeautifulSoup:

soup = BeautifulSoup(response.content, "html.parser")
## Preview HTML structure using:

print(soup.prettify())
## Dependencies
pip install requests beautifulsoup4



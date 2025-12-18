# Web Scraping & API Data Extraction Projects (Python)

This repository contains hands-on Python projects demonstrating practical web scraping, API consumption, data extraction, automation, and basic analysis.  
The projects showcase my ability to work with **HTML pages, REST APIs, structured and unstructured data**, and transform scraped data into **usable datasets for analysis and reporting**.

---

## Tools & Libraries Used
- Python
- Requests
- BeautifulSoup (bs4)
- Pandas
- Seaborn & Matplotlib
- JSON
- REST APIs

---

## Projects Overview

### 1 Microsoft Fabric Region Availability Web Scraping

**Objective:**  
Scrape regional availability data directly from Microsoft Learn documentation and convert it into a structured dataset.

**Key Steps:**
1. Sent an HTTP request to the Microsoft Learn webpage using `requests`.
2. Parsed the HTML content using `BeautifulSoup`.
3. Located and extracted the relevant HTML `<table>` containing region availability.
4. Extracted column headers (`<th>`) and table rows (`<td>`).
5. Cleaned and structured the data into a Pandas DataFrame.
6. Exported the final dataset to a CSV file for reuse.

**Skills Demonstrated:**
- HTML parsing
- Table extraction
- Data cleaning
- Converting unstructured web data into structured datasets

**Output:**  
A clean CSV file containing Microsoft Fabric region availability data.

---

### 2 Cryptocurrency Data Extraction & Automation (CoinMarketCap API)

**Objective:**  
Collect real-time cryptocurrency market data using CoinMarketCap’s API and automate periodic data extraction for trend analysis.

**Key Steps:**
1. Connected to the CoinMarketCap REST API using authenticated requests.
2. Retrieved live cryptocurrency listings in JSON format.
3. Normalized nested JSON data into a flat Pandas DataFrame.
4. Added timestamps to track when each data pull occurred.
5. Built a reusable function (`api_runner`) to automate data collection.
6. Scheduled repeated API calls using time intervals (`sleep`) for continuous data capture.
7. Stored results in a CSV file with append logic.
8. Performed basic cleaning and formatting of numerical columns.
9. Aggregated and analyzed percentage price changes across time windows.
10. Visualized price trends and percentage changes, including Bitcoin price movement over time.

**Skills Demonstrated:**
- REST API consumption
- Authentication & headers handling
- JSON normalization
- Automation & scheduling
- Time-series tracking
- Data aggregation & visualization

**Output:**  
A continuously updated cryptocurrency dataset suitable for market trend analysis.

---

### 3 Wikipedia Web Scraping: Largest U.S. Companies by Revenue

**Objective:**  
Scrape tabular company data from Wikipedia and convert it into a structured dataset.

**Key Steps:**
1. Requested the Wikipedia page containing company rankings.
2. Parsed the HTML using `BeautifulSoup`.
3. Identified and extracted the main sortable table.
4. Retrieved table headers and row-level data.
5. Converted extracted data into a Pandas DataFrame.
6. Exported the cleaned dataset to a CSV file.

**Skills Demonstrated:**
- Web scraping from public sources
- Handling large HTML tables
- Data extraction consistency
- Data export for downstream analysis

**Output:**  
A CSV file containing the list of the largest U.S. companies by revenue.

---

##  What This Repository Demonstrates

- Ability to scrape data from **static web pages**
- Ability to work with **authenticated APIs**
- Data cleaning and structuring using Pandas
- Automation of data collection pipelines
- Transforming raw web data into analysis-ready datasets
- Visualization of extracted data for insights


---

## Disclaimer
All data was collected from publicly available sources and APIs for **learning and educational purposes only**.


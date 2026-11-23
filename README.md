# Web Scraping using Python

Link; https://roadmap.sh/projects/job-listings-scraper

## Project Overview

This project focuses on learning the basics of Web Scraping using Python.

The goal was to collect job listing information from the Fake Python Jobs website and store the extracted information in a structured CSV file.

This project helped me understand how data can be collected directly from websites for further data analysis.

## Website

[Fake Python Jobs](https://realpython.github.io/fake-jobs/)

## Technologies & Libraries Used

- Python
- Requests
- BeautifulSoup (BS4)
- CSV
- Pandas

## Project Workflow

1. **Send HTTP Request:** Used the Requests library to fetch webpage content.
2. **Parse HTML:** Used BeautifulSoup to parse and navigate the HTML structure.
3. **Inspect HTML Elements:** Identified relevant HTML tags and CSS classes containing job information.
4. **Extract Data:** Collected job details from individual job listing elements.
5. **Handle Missing Values:** Used conditional checks to handle missing fields.
6. **Organize Data:** Stored extracted information using Python dictionaries and lists.
7. **Export Data:** Saved the collected job listings into a CSV file.

## Data Extracted

The following information was collected from each job listing:

- Job Title
- Company Name
- Location
- Job Details URL

## Project Files

- `Web_Scraping.ipynb` – Jupyter Notebook containing the web scraping code.
- `job_listings.csv` – CSV file containing the extracted job listings.

## Key Learnings

- Understanding the basics of Web Scraping.
- Sending HTTP requests using Python Requests.
- Understanding HTML structure and webpage elements.
- Parsing HTML using BeautifulSoup.
- Finding elements using HTML tags and CSS classes.
- Extracting structured information from websites.
- Handling missing fields using conditional statements.
- Exporting scraped data into CSV format.

## Conclusion

This project gave me a practical introduction to Web Scraping and helped me understand the basic process of collecting data from websites.

I also learned how web scraping can support Data Analytics by providing data that can later be cleaned, processed, analyzed, and visualized.

Looking forward to learning more advanced web scraping techniques and exploring more real-world applications.

# Job-Listings-Web-Scrapping

## Overview
This project is a Python-based web scraper that extracts job listing data from the Shine.com website. The scraper collects the following information for each job posting:

- Job Title
- Employer
- Job Location
- Required Experience
- Number of Positions Available

## Requirements
The following Python libraries are required to run this script:

- `requests`
- `BeautifulSoup4`
- `pandas`

3. The script will output a CSV file named `shine_job_listings.csv` containing the extracted job data.

## Data Extraction
The script uses the `requests` library to fetch the HTML content of the Shine.com website, and the `BeautifulSoup4` library to parse the HTML and extract the relevant job information.

The script first navigates to the Shine.com homepage and then follows the links to the job listings page. It then iterates through the job listings on the page, extracting the job title, employer, location, experience, and number of positions for each listing.

The extracted data is then stored in a Pandas DataFrame and written to a CSV file.

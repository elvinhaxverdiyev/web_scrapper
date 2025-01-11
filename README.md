# Product Information Scraping and Sending Application - README

## Overview
This application is designed to scrape product information from a website, save the data into a JSON file, and share it via email. It is developed in Python and utilizes technologies such as HTTP requests, HTML parsing, JSON operations, and the SMTP protocol.

## Features
1. Fetch HTML data from a specified URL and extract desired information using CSS selectors.
2. Organize and save the collected data into a JSON file.
3. Read the data from the JSON file and send it to a recipient via email.

## Installation and Execution
1. Install the required Python libraries:
   ```bash
   pip install httpx selectolax
   ```
2. Update the `sender_email` and `sender_password` fields in the code with your Gmail account credentials.
3. Enable the "Allow less secure apps" option in your Gmail account settings.
4. Run the application with the following command:
   ```bash
   python scraper.py
   ```

## Usage
1. Update the website URL and the CSS selectors for the information you want to scrape.
2. The application will save the scraped information into a JSON file and then send the data to the specified email address.

## Notes
- Ensure the CSS selectors are accurate. Incorrect selectors may prevent data extraction.
- Keep your Gmail account credentials secure and do not share them.
- Verify that the JSON file is created in the specified directory.


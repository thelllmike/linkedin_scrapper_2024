# LinkedIn Profile Scraper

This project provides a script for scraping LinkedIn profiles using Selenium and BeautifulSoup. It's designed to extract professional information such as name, company, location, experience, and education details from specified LinkedIn profiles.

## Disclaimer

This tool is for educational purposes only. Web scraping LinkedIn profiles can violate LinkedIn's terms of service. Users should ensure they comply with LinkedIn's terms and conditions. The creator of this script does not take any responsibility for how it is used or potential consequences.

## Prerequisites

Before running the script, ensure you have the following installed:
- Python 3.x
- Selenium
- BeautifulSoup4
- pandas

Additionally, you will need:
- ChromeDriver that matches the version of your Chrome browser.
- A LinkedIn account.

## Setup

1. **Install Required Python Packages**

Run the following command to install the necessary Python packages:


2. **ChromeDriver**

Download ChromeDriver from https://sites.google.com/a/chromium.org/chromedriver/downloads. Extract the executable and place it in a known directory.

3. **Configuration File**

Create a `credentials_and_urls.json` file in the project directory with the following structure:

```json
{
  "login_credentials": {
    "username": "your_linkedin_email",
    "password": "your_linkedin_password"
  },
  "profile_urls": [
    "https://www.linkedin.com/in/profileurl1",
    "https://www.linkedin.com/in/profileurl2"
    // Add more profile URLs as needed
  ]
}

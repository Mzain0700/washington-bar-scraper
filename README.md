# WSBA Attorney Scraper 🕵️‍♂️

This project scrapes data of **active attorneys** from the [Washington State Bar Association (WSBA) directory](https://www.mywsba.org/PersonifyEbusiness/Default.aspx?TabID=1536&ShowSearchResults=TRUE&Status=Active). The scraper extracts relevant information from the public-facing search results and stores it for further use.

## 📂 Project Structure

- `Scrapper.ipynb`: Jupyter notebook containing the web scraping logic, including:
  - Automating browser interaction with Selenium.
  - Navigating through paginated search results.
  - Extracting data like Name, WSBA Number, Email, Phone, and Address.
  - Saving data in a structured format (e.g., CSV or Excel).

## 📌 Features

- Scrapes all pages of active attorneys listed on the WSBA website.
- Uses **Selenium** for dynamic content rendering.
- Stores the data in a readable file format for easy access.
- Designed for **educational** and **research** purposes.

## 🔧 Requirements

- Python 3.x
- Jupyter Notebook
- ChromeDriver (compatible with your browser)
- The following Python libraries:
  ```bash
  pip install selenium pandas openpyxl

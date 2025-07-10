# 📚 Book Scraper with Python & BeautifulSoup

This project is a simple web scraper built in Python using `requests`, `BeautifulSoup`, and `pandas`. It extracts book information from the website [books.toscrape.com](https://books.toscrape.com/) — a sandbox site for practicing web scraping.

## 🚀 Features

- Scrapes the **title**, **price**, **availability**, and **rating** of books from the homepage.
- Cleans the scraped data and stores it in a structured format.
- Saves the output to a CSV file (`books_basic.csv`).

## 🧪 Technologies Used

- `requests` – to make HTTP requests
- `BeautifulSoup` – to parse and navigate HTML
- `pandas` – to store and export the data in CSV format

## 📦 Installation

Make sure you have Python installed, then install the required libraries:

```bash
pip install requests beautifulsoup4 pandas

▶️ How to Run
Clone or download the repository.

Run the script:

python book_scraper.py


The output will be saved in a file named books_basic.csv.

📁 Output Example
 Title	        Price	        Availability	  Rating
A Light 	      51.77	        In stock	      Three

📝 Notes
Currently, the scraper only works on the homepage of books.toscrape.com.

You can extend the script to scrape multiple pages by adding pagination support.

💡 License
This project is open source and free to use for educational and practice purposes.



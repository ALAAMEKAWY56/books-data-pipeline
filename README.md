# books-data-pipeline
Python ETL pipeline that scrapes 1000+ books and loads them into a MySQL database.
# 📚 Books Data Pipeline

This project demonstrates how to build a mini ETL (Extract, Transform, Load) pipeline in Python by scraping real-world book data and storing it in a MySQL relational database.

## 🔧 What This Project Does

- 🕸 Scrapes 1000+ books from [books.toscrape.com](http://books.toscrape.com/)
- 📄 Saves data to a clean CSV file
- 🛢 Creates a structured MySQL database with two tables: `categories` and `books`
- 🧠 Loads and stores scraped data into the database using Python

## 🗂 Tech Stack

- Python (BeautifulSoup, requests, pandas, mysql-connector)
- MySQL
- Jupyter Notebook
- Git & GitHub

## 📁 Project Structure

books-data-pipeline/
│
├── data/ # CSV scraped data
├── scripts/ # Python scripts for scraping and database loading
├── schema/ # ERD diagram and schema visuals
├── README.md # Project documentation
└── requirements.txt # Python dependencies

## 🚀 How to Run

1. Clone the repo  
2. Install requirements: `pip install -r requirements.txt`  
3. Run `web_scraper.py` to extract data  
4. Run `db_loader.py` to create tables and load into MySQL  

## 🧠 What I Learned

- Web scraping with BeautifulSoup
- Structuring data with relational models
- Writing SQL in Python
- Basic ETL design and implementation

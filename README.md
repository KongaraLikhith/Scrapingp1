# 🕸️ Quotes Web Scraper

A simple yet effective Python project for scraping data from quotes websites using **Requests** and **BeautifulSoup**. This tool extracts quote information based on specific tags and was originally prototyped in Jupyter/Colab before being converted into a standalone script.

## 🚀 Features

* **Targeted Scraping:** Extracts quotes based on specific HTML tags.
* **HTML Parsing:** Uses BeautifulSoup for efficient DOM navigation and data extraction.
* **File Handling:** Capable of saving scraped results into structured formats (CSV/JSON).
* **Lightweight:** Minimal dependencies, making it fast and easy to execute.

## 📂 Project Structure

    Scrapingp1/
    │
    ├── src/
    │   └── scraping_prac_file_handling.py   # Main scraping script
    │
    ├── requirements.txt                     # Project dependencies
    ├── README.md                            # Documentation
    └── .gitignore                           # Ignored files

## 🛠️ Prerequisites

Ensure you have Python installed along with the required libraries.

**Install Dependencies:**
Run the following command to install `requests` and `beautifulsoup4`:

    pip install -r requirements.txt

*(If you don't have a requirements file yet, you can create one with: `requests` and `beautifulsoup4`)*

## ⚙️ Usage

1.  **Clone the repository:**
    
        git clone https://github.com/yourusername/Scrapingp1.git
        cd Scrapingp1

2.  **Run the script:**
    Navigate to the source directory and execute the Python file:

        python src/scraping_prac_file_handling.py

3.  **View Results:**
    The script will output the scraped data to the console or save it to a file (depending on your specific configuration in the script).

## 🧩 Technologies Used

* **Language:** Python 3.x
* **HTTP Requests:** `requests` library
* **Parsing:** `beautifulsoup4` (bs4)

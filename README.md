
# 📚 Book Listing Web Scraper

A Python-based web scraping project that extracts essential data from an online bookstore. This scraper collects book titles, prices, ratings, and stock availability.

---

## 🔍 What It Does

* Scrapes book information from a website
* Extracts:

  * 📖 **Title**
  * 💵 **Price**
  * ⭐ **Rating**
  * ✅ **Availability (In stock/Out of stock)**
* Stores the data in a structured format (e.g., CSV or DataFrame)

---

## 🛠 Tech Stack

* **Python**
* **BeautifulSoup** (for parsing HTML)
* **Requests** (for sending HTTP requests)
* **Pandas** (for data handling)

---

## 💡 What I Did

* Identified HTML structure of the book listing pages
* Parsed book data using BeautifulSoup
* Cleaned and standardized extracted text (e.g., removing currency symbols)
* Exported the final dataset into a readable format

---

## 🚀 How to Run

1. Clone the repository or copy the script
2. Install required packages:

   ```bash
   pip install requests beautifulsoup4 pandas
   ```
3. Run the script:

   ```bash
   python book_scraper.py
   ```
4. View the extracted data in `books.csv` or a displayed table

---

## ✅ Output

The output includes:

* `Title`: Book name
* `Price`: Price in currency format
* `Rating`: Text-based rating (e.g., Three, Five)
* `Availability`: "In stock" or "Out of stock"

---

## 📌 Notes

* This project is for educational use and respects the target website’s `robots.txt` and terms of service.
* Dynamic websites may require tools like Selenium instead of BeautifulSoup.

---


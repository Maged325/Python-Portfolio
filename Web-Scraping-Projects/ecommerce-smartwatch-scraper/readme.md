
# 🛒 **E-commerce Smartwatch Scraper - Egypt 🇪🇬**

This project scrapes smartwatch product data from **Jumia Egypt** and **Noon Egypt** using `requests + BeautifulSoup` and `Selenium`, respectively. It collects data such as product name, price, rating, discount, and link—then exports it to a CSV file.

---

## 📌 **Features**

- Extracts product name, price, rating, discount, and product link.
- Scrapes from:
  - 🟠 Jumia Egypt (using BeautifulSoup)
  - 🟡 Noon Egypt (using Selenium)
- Exports clean product data to a `.csv` file.
- Shows the first 5 products for quick viewing.
- Filter logic can be added later (e.g., by discount or rating).

---

## 🔨 **Built With**

- `Python`
- `BeautifulSoup`
- `requests`
- `Selenium`
- `pandas`
- `webdriver_manager` (auto-manages ChromeDriver)

---

## 🗂️ **Project Structure**

📁 ecommerce-smartwatch-scraper

├── 📄 jumia_scraper.ipynb

├── 📄 noon_scraper.ipynb

├── 📄 jumia_smart_watches.csv

├── 📄 noon_smart_watches.csv

└── 📄 README.md



# Web Scraping Quotes with Python (Beginner Project)

## 📌 Overview
This project demonstrates a simple web scraper built using **Python**, **requests**, and **BeautifulSoup**.  
The scraper extracts data from **https://quotes.toscrape.com**, a website intentionally designed for practicing web scraping.

The script collects:
- ✅ Quote text  
- ✅ Author name  
- ✅ Tags associated with each quote

This is a beginner-friendly project and a foundation for learning more advanced scraping techniques.

---

## ⚙️ Technologies Used
- Python 3
- requests
- BeautifulSoup (bs4)

---

## 🚀 What the Script Does
1. Sends a GET request to the website
2. Parses the HTML using BeautifulSoup
3. Locates all `<div class="quote">` containers
4. Extracts:
   - `<span class="text">` → Quote
   - `<small class="author">` → Author
   - `<a class="tag">` → Tags (list)
5. Stores each quote as a dictionary inside a list
6. Prints a sample result

# Hacker News Web Scraper using Python (requests + BeautifulSoup)

## 📌 Overview
This project demonstrates how to scrape **live data from Hacker News** using Python.  
It extracts the following details for each story on the front page (and can be extended for multiple pages):

- ✅ Rank (1, 2, 3, …)
- ✅ Title of the story
- ✅ Link (URL to the story)
- ✅ Source website (e.g., github.com, medium.com)
- ✅ Score / Points (e.g., 123 points)
- ✅ Author (user who posted it)
- ✅ Age (how long ago it was posted)
- ✅ Number of comments

This is a real-world example of web scraping on a popular website with a consistent HTML structure.

---

## 🛠️ Technologies Used
- **Python 3**
- `requests` – to download the HTML
- `BeautifulSoup (bs4)` – to parse the HTML and extract data
- `urllib.parse` – to handle absolute URLs (urljoin)

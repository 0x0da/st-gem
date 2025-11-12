# st-gem - Link Scraper

A robust and polite **Python-based web link scraper** that extracts all hyperlinks (`<a href="">`) from a given webpage — or crawls an entire site up to a configurable depth.  

It supports domain filtering, robot.txt compliance, retries, timeouts, rate limiting, and multiple output formats (CSV, JSON, TXT).

---

## 🚀 Features

✅ Extracts all hyperlinks (`<a>` tags) from any HTML page  
✅ Optionally **crawls multiple pages** up to a given depth (BFS traversal)  
✅ **Respects `robots.txt`** directives  
✅ Deduplicates and normalizes URLs  
✅ Supports **same-domain-only** filtering (with or without subdomains)  
✅ Polite crawling with optional **delay between requests**  
✅ Export results as **CSV**, **JSON**, or **TXT**  
✅ Clean CLI and well-structured output  

---

## 🧰 Requirements

- Python 3.8+
- The following libraries:
  ```bash
  pip install requests beautifulsoup4
  ```

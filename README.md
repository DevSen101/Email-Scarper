# **Email Scarper using Python**
A simple Python script that crawls a website and extracts email addresses using BeautifulSoup and Requests.

````md
# Email Scraper using Python

This is a simple Python tool that scans a given website URL and extracts email addresses by crawling internal links.

The script uses `requests` to fetch web pages and `BeautifulSoup` to parse HTML content.

---

## 🔧 Features

- Crawls internal website links
- Extracts email addresses using regex
- Avoids duplicate URLs and emails
- Stops automatically after scanning 100 pages
- Easy to understand and modify

---

## 📦 Requirements

Make sure Python is installed, then install required libraries:
---

## 🚀 How to Use

1. Clone the repository:

```bash
git clone https://github.com/DevSen101/Email-Scarper.git
```

2. Navigate to the project folder:

```bash
cd email-scarper
```

3. Run the script:

```bash
python scarper.py
```

4. Enter the target URL when prompted:

```text
[+] Enter Target URL To Scan: https://example.com
```

---

## 🧠 How It Works

* Starts from the given URL
* Collects internal links using `<a href>`
* Scans each page for email patterns
* Stores unique emails and URLs
* Prints all found email addresses at the end

---

## ⚠️ Disclaimer

This tool is for **educational purposes only**.
Do not use it on websites without permission.

---

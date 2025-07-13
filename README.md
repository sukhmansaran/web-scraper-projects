# 🌐 Web Scraping Experiments:

This repository contains two experimental web scraping projects designed to extract structured data from public web pages. The goal was to automate data collection for insights, lead generation, and education research purposes.

---

## 📌 Project 1: GMB Profile Extractor (Google Search Page)

**Objective:**  
Extract basic business profile information from Google search result pages (not Google Maps) for a given list of company names or keywords.

### 🔍 Extracted Data Fields:
- Business Name  
- Address  
- Phone Number  
- Website URL  
- Operating Hours  
- Review Count  
- Social Media Links (if available)

### 🛠 Tools & Libraries:
- Python  
- BeautifulSoup  
- Requests  
- Regex  
- Pandas

### ⚠️ Disclaimer:  
This scraper works on Google's search page layout as of the time of development and may break if the structure changes. It was built for educational and experimental purposes only.

---

## 🎓 Project 2: TalentEdge Course Catalog Scraper

**Objective:**  
Scrape detailed course information from TalentEdge, an edtech platform, for analysis and cataloging.

### 🔍 Extracted Data Fields:
- Course Title  
- Course URL  
- Description  
- Duration  
- Start Date  
- What You Will Learn  
- Skills Covered  
- Target Audience  
- Eligibility Criteria  
- Course Content  
- Faculty Names & Designations  
- Institute Name  
- Fees (INR & USD)

### 🛠 Tools & Libraries:
- Python  
- BeautifulSoup  
- Requests  
- Pandas  
- LXML

---

## ✅ Status
Both scripts are functional and have been tested on a limited number of inputs. They serve as experimental prototypes and may require updates to work on new website layouts.

---

## 📌 Notes
- Ensure appropriate headers and delays when scraping public websites.
- Avoid high-frequency scraping to prevent IP bans or ToS violations.
- Always respect site robots.txt and legal usage.

---

## 🚀 Future Improvements
- Add proxy support and error handling.
- Convert output to JSON/DB-ready format.
- Integrate with a lead generation or course recommendation tool.

---

## 📄 License
This project is for educational purposes only and does not promote scraping restricted or copyrighted content.



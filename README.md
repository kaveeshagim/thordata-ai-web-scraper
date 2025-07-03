## 🕸️ Thordata AI Web Scraper

A clean, browserless web scraper built with Python using the [Thordata Universal Scraping API](https://www.thordata.com/). Based on the Python AI Web Scraper Tutorial by Tech With Tim, but reworked to use Thordata instead — no need for Selenium, browsers, or headless infrastructure.

### 🛠️ Tech Stack

- **Streamlit** – for building the web UI
- **LangChain** – to connect LLMs with tools and documents
- **LangChain-Ollama** – integrates Ollama's local LLMs (using LLaMA 3 in this project)
- **BeautifulSoup4** – for HTML parsing
- **LXML** & **html5lib** – HTML parsers for BeautifulSoup
- **Selenium** (optional/debug) – used during experimentation only
- **python-dotenv** – to manage your Thordata API key securely

### 🔧 Features

- HTML scraping with JavaScript rendering (via `js_render`)
- Replaces Bright Data with Thordata's API
- No ChromeDriver, Selenium, or Puppeteer needed
- Lightweight and production-ready scraping setup

### 📹 Based on this tutorial

[Python AI Web Scraper Tutorial - Use AI To Scrape ANYTHING](https://youtu.be/Oo8-nEuDBkk?si=03IazmwFF8877Dtl) by [Tech With Tim](https://www.youtube.com/@TechWithTim)

### 🧪 Usage

```bash
streamlit run main.py
```

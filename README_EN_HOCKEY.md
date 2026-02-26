# Hockey Team Statistics

This project scrapes historical NHL team statistics from the web and analyzes them to understand team performance over multiple seasons. The end goal is a simple betting odds model that groups teams into performance tiers based on their win rates.

> **Note:** Code comments and notebook descriptions are written in Czech, as this project was built during a Czech data analytics training program.

## What this project does

1. Downloads raw HTML pages with NHL team statistics using Selenium
2. Parses the data with BeautifulSoup and saves it as JSON
3. Cleans and transforms the data into a structured CSV
4. Runs statistical analysis and creates visualizations
5. Calculates betting odds for each performance tier

## Project structure

```
Workshop_-_files/
├── data/
│   ├── raw/               # Downloaded HTML files
│   ├── interim/           # Parsed JSON data
│   └── processed/         # Final CSV file
├── notebooks/
│   ├── 00_Intro.ipynb
│   ├── 01_DataDownload.ipynb            # Scraping
│   ├── 02_DataProcessing.ipynb          # Cleaning
│   ├── 03_DataAnalysis.ipynb            # Analysis & charts
│   └── 04_BusinessRecommendations.ipynb # Betting odds
└── drivers/               # Selenium Chrome driver
```

## Tools used

Python, Selenium, BeautifulSoup, Pandas, Matplotlib, NumPy

## How to run it

Open the root project folder in VS Code, then run the notebooks in order starting from `01_DataDownload.ipynb`. All file paths are relative to the project root, so no manual path configuration is needed.

## Author

Boris – Data Analytics Portfolio Project

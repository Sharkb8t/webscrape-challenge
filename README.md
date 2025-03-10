# webscrape-challenge

# Mars Data Web Scraping and Analysis
Web Scraping and Data Analysis of Mars News and Weather Data

## 📌 Project Overview
This project focuses on scraping and analyzing data related to Mars using Python web scraping techniques. The project is divided into two main parts:

  1. **Scraping Mars News:** Extracting article titles and preview text from the Mars News website.

  2. **Scraping and Analyzing Mars Weather Data:** Collecting weather data from an HTML table, storing it in a Pandas DataFrame, performing analysis, and visualizing key insights.

## 📂 Files in This Repository

### 1️⃣ Jupyter Notebooks:

> `part_1_mars_news.ipynb` → Scrapes Mars news article titles and previews using BeautifulSoup and Splinter.

> `part_2_mars_weather.ipynb` → Scrapes Mars weather data from an HTML table and performs data analysis using Pandas and Matplotlib.

### 2️⃣ Output Files:

> `mars_weather.csv` → The cleaned and structured Mars weather dataset, extracted from the web page.

## 🚀 Technologies & Libraries Used

  > **Splinter** - Automated browsing for web scraping.

  > **BeautifulSoup** - HTML parsing to extract specific elements.

  > **Selenium** - Web automation for Edge browser integration.

  > **Pandas** - Data manipulation and analysis.

  > **Matplotlib** - Data visualization.

## 📜 Methodology

🔹 Part 1: Mars News Scraping:

1. Automated browsing is used to visit the Mars news site.

2. A BeautifulSoup object extracts article titles and preview text.

3. The scraped data is stored in a Python list of dictionaries.

4. The results are printed in the notebook and optionally exported.

🔹 Part 2: Mars Weather Scraping and Analysis:

1. Scrape the Mars weather data from an HTML table.

2. Convert the scraped data into a Pandas DataFrame.

3. Perform data type conversions for proper numerical operations.

4. Analyze the dataset:

  - Identify the coldest and warmest months on Mars.

  - Determine the months with highest and lowest atmospheric pressure.

  - Estimate the length of a Martian year using temperature cycles.

  - Visualize the data using bar charts and line plots.

## 📊 Key Results:

- Coldest month: Martian March (**Month 3**) with an average *-83°C*.

- Warmest month: Martian August (**Month 8**) with an average *-68°C*.

- Highest pressure month: **Month 9** (*~920 Pascals*).

- Lowest pressure month: **Month 6** (*~750 Pascals*).

- A Martian year is approximately *687* Earth days, confirmed by temperature cycles.

## 💻 How to Run the Notebooks

### 1️⃣ Install Required Libraries

Before running the notebooks, install the dependencies:
```bash
pip install splinter selenium beautifulsoup4 pandas matplotlib webdriver-manager
```

### 2️⃣ Run Jupyter Notebook

Launch Jupyter Notebook:
```bash
jupyter notebook
```
Open `part_1_mars_news.ipynb` and `part_2_mars_weather.ipynb`, then run all cells in sequential order.

## ⚠️ Notes

- The scraping process requires an active internet connection.

- Microsoft Edge WebDriver should be properly installed and match the browser version.

- Ensure that chromedriver.exe or msedgedriver.exe is correctly configured.


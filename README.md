# Moving-Average-Crossover-Signals
This Python script focuses on generating **Buy and Sell signals** for stocks based on a classic **Moving Average Crossover** strategy.  

## Description

This Python script focuses on generating **Buy and Sell signals** for the **Magnificent 7 (Mag 7)** stocks, based on a classic **Moving Average Crossover** strategy.  

The specific stocks analysed by default are: `GOOGL`, `AMZN`, `AAPL`, `META`, `MSFT`, `NVDA`, and `TSLA`. Feel free to modify the script and replace these ticker symbols with others you wish to analyse.  

The core logic involves:
1.  Fetching the last year's worth of **daily adjusted close** price data from Yahoo Finance (`yfinance`).
2.  Calculating the 50-day and 200-day Simple Moving Averages (SMA).
3.  Generating **'Buy' signals** when the 50-day SMA crosses above the 200-day SMA.
4.  Generating **'Sell' signals** when the 50-day SMA crosses below the 200-day SMA.

The script then visualises the results, plotting the closing price, the SMAs, and clearly marking the generated Buy/Sell signals on the chart for each stock using `matplotlib`.

This project serves as a practical demonstration of implementing a basic trading signal strategy in Python. It uses historical daily data fetched from **Yahoo Finance (`yfinance`)**. As with any free data source, occasional inaccuracies might be present.  

**Disclaimer:** This tool is for educational and demonstration purposes only. The generated signals are based on a simple historical analysis and **do not constitute financial or investment advice**. Trading stocks involves significant risk.

## Features

* Fetches historical **daily adjusted close** data for the Mag 7 stocks (GOOGL, AMZN, AAPL, META, MSFT, NVDA, TSLA) over the past year.
* Calculates 50-day and 200-day Simple Moving Averages (SMA).
* **Generates Buy/Sell signals** based on the 50/200 SMA crossover points.
* Visualises the stock price, SMAs, and signals clearly on a chart.
* Includes basic error handling for data fetching.

## Requirements

* Access to **Google Colab** OR a local **Python 3.x** environment 
* Required Python libraries:
    * `yfinance`
    * `pandas`
    * `matplotlib`

## Usage (in Google Colab)

1.  **Open the Notebook:**
    * Click the badge below to open this notebook directly in Google Colab:
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tunjis/Moving-Average-Crossover-Signals/blob/main/Moving_Average_Crossover_Signals.ipynb)  
2.  **Run the Cells:**
    * Once the notebook is open in Colab, run the code cells sequentially from top to bottom (you can use `Shift+Enter` or click the 'Run' button for each cell).
3.  **View Output:**
    * As the code runs, it will process each stock ticker. For each one, it will display a plot showing the price history, moving averages, and the calculated **Buy (^) and Sell (v) signals**.

## Example Output
![Example Plot Showing Buy/Sell Signals](image/signal_plot_example.png)  


Created by [tunjis](https://github.com/tunjis)  

*Data’s the new oil. I’m the refinery.*


* 🌍  Based in <a href="https://maps.app.goo.gl/hMxhRX5ptQAAkL7NA/" target="_blank"> **London**
* 🖥️  See my portfolio at [Coded-Portfolio](http://github.com/tunjis)
* ✉️  Contact me at [jstunjis@gmail.com](mailto:jstunjis@gmail.com)
* 🧠  Learning Data Science
* 🤝  Open to collaborating on interesting projects
* ⚡  AI enthusiast   


### 🛠️ Technical Skills
<a href="https://www.python.org/" alt="Python" title="Python"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="36" height="36"/> **Python** </a> 
<a href="https://www.microsoft.com/en-us/microsoft-365/excel" target="_blank"><img src="https://img.icons8.com/color/24/000000/microsoft-excel-2019--v1.png" width="36" height="36"/> **Microsoft Excel** </a> 
<a href="https://www.mysql.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="36" height="36"/> **MySQL** </a> 
<a href="https://www.tableau.com/" target="_blank"><img src="https://img.icons8.com/color/24/000000/tableau-software.png" width="36" height="36"/> **Tableau** </a> 
<a href="https://powerbi.microsoft.com/" target="_blank"><img src="https://img.icons8.com/color/24/000000/power-bi.png" width="36" height="36"/> **Power BI** </a> 
<a href="https://cloud.google.com/" target="_blank"><a href="https://cloud.google.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="36" height="36"/> **Google Cloud** </a> 
<a href="https://azure.microsoft.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width="36" height="36"/> **Microsoft Azure** </a> 
<a href="https://colab.research.google.com/" target="_blank"><img src="https://img.icons8.com/color/48/000000/google-colab.png" width="36" height="36"/> **Google Colab** </a>  


### Socials

<a href="https://www.github.com/tunjis/" target="_blank" rel="noreferrer" style="margin-right: 5px; vertical-align: middle;">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" />
    <img alt="GitHub Profile" src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" />
  </picture>
</a>


<a href="https://linkedin.com/in/justincraciun/" target="_blank" rel="noreferrer" style="margin-right: 5px; vertical-align: middle;">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" />
    <img alt="LinkedIn Profile" src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" />
  </picture>
</a>
  
### Support Me

<a style="display: inline-block; margin-right: 0.25rem;"><a href="https://www.buymeacoffee.com/tunjis"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="150"/></a></li>  


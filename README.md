# Moving-Average-Crossover-Signals
This Python script focuses on generating **Buy and Sell signals** for the **Magnificent 7 (Mag 7)** stocks based on a classic **Moving Average Crossover** strategy. The specific stocks analysed are in this case the Mag7: GOOGL, AMZN, AAPL, META, MSFT, NVDA, and TSLA.
# Magnificent 7 Moving Average Crossover Signals

## Description

This Python script focuses on generating **Buy and Sell signals** for the **Magnificent 7 (Mag 7)** stocks based on a classic **Moving Average Crossover** strategy. The specific stocks analysed are: GOOGL, AMZN, AAPL, META, MSFT, NVDA, and TSLA.

The core logic involves:
1.  Fetching the last year's worth of **daily adjusted close** price data from Yahoo Finance (`yfinance`).
2.  Calculating the 50-day and 200-day Simple Moving Averages (SMA).
3.  Generating **'Buy' signals** when the 50-day SMA crosses above the 200-day SMA.
4.  Generating **'Sell' signals** when the 50-day SMA crosses below the 200-day SMA.

The script then visualises the results, plotting the closing price, the SMAs, and clearly marking the generated Buy/Sell signals on the chart for each stock using `matplotlib`.

This project serves as a practical demonstration of implementing a basic trading signal strategy in Python.

**Disclaimer:** This tool is for educational and demonstration purposes only. The generated signals are based on a simple historical analysis and **do not constitute financial or investment advice**. Trading stocks involves significant risk.

## Features

* Fetches historical **daily adjusted close** data for the Mag 7 stocks (GOOGL, AMZN, AAPL, META, MSFT, NVDA, TSLA) over the past year.
* Calculates 50-day and 200-day Simple Moving Averages (SMA).
* **Generates Buy/Sell signals** based on the 50/200 SMA crossover points.
* Visualises the stock price, SMAs, and signals clearly on a chart.
* Includes basic error handling for data fetching.

## Requirements

* Python 3.x
* Required Python libraries:
    * `yfinance`
    * `pandas`
    * `matplotlib`

## Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/tunjis/Mag7-MovingAverage-Signals.git](https://github.com/tunjis/Mag7-MovingAverage-Signals.git)
    cd Mag7-MovingAverage-Signals
    ```

2.  **Install the required libraries:**
    ```bash
    pip install yfinance pandas matplotlib
    ```
    *(Remember to activate your virtual environment first if you're using one)*

## Usage

1.  Navigate to the project directory in your terminal.
2.  Run the script:
    ```bash
    python your_script_name.py
    ```
    *(Replace `your_script_name.py` with the actual name of your Python file, e.g., `ma_signal_generator.py`)*

The script will then execute for each of the Mag 7 stocks. For every stock, it will display a plot showing the price history, the moving averages, and markers indicating the calculated **Buy (^) and Sell (v) signals**. You'll need to close each plot window before the script moves on to the next stock.

## Example Output

*(Strongly recommended!)*

Adding a screenshot of a generated plot makes it immediately clear what the script produces.
1.  Run your script.
2.  Take a screenshot of one of the charts showing the signals.
3.  Save the image (e.g., `signal_plot_example.png`) in the project folder.
4.  Include it here using this Markdown line:
    ```markdown
    ![Example Plot Showing Buy/Sell Signals](signal_plot_example.png)
    ```

---

Created by [tunjis](https://github.com/tunjis)  

*Data’s the new oil. I’m the refinery.*


* 🌍  Based in <a href="https://maps.app.goo.gl/hMxhRX5ptQAAkL7NA/" target="_blank"> **London**
* 🖥️  See my portfolio at [Coded-Portfolio](http://github.com/tunjis)
* ✉️  Contact me at [jstunjis@gmail.com](mailto:jstunjis@gmail.com)
* 🧠  Learning Data Science
* 🤝  Open to collaborating on interesting projects
* ⚡  AI enthusiast   


| 🛠️ Technical Skills                                                                                                                            | Description                             |
|---------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------|
| <a href="https://www.python.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="36" height="36"/> **Python** </a> | Data analysis, scripting, automation    |
| <a href="https://www.microsoft.com/en-us/microsoft-365/excel" target="_blank"><img src="https://img.icons8.com/color/24/000000/microsoft-excel-2019--v1.png" width="36" height="36"/> **Microsoft Excel** </a> | Data wrangling, pivot tables, dashboards |
| <a href="https://www.mysql.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="36" height="36"/> **MySQL** </a> | Database querying & management          |
| <a href="https://www.tableau.com/" target="_blank"><img src="https://img.icons8.com/color/24/000000/tableau-software.png" width="36" height="36"/> **Tableau** </a> | Interactive data visualization          |
| <a href="https://powerbi.microsoft.com/" target="_blank"><img src="https://img.icons8.com/color/24/000000/power-bi.png" width="36" height="36"/> **Power BI** </a> | Business intelligence dashboards        |            |
| <a href="https://cloud.google.com/" target="_blank"><a href="https://cloud.google.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="36" height="36"/> **Google Cloud** </a> | Cloud services & APIs                   |
| <a href="https://azure.microsoft.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" width="36" height="36"/> **Microsoft Azure** </a> | Cloud computing & services              |                     |
| <a href="https://colab.research.google.com/" target="_blank"><img src="https://img.icons8.com/color/48/000000/google-colab.png" width="36" height="36"/> **Google Colab** </a> | Interactive Python notebooks in the cloud |


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

<ul style="list-style-type: none; margin: 0;">

<li style="display: inline-block; margin-right: 0.25rem;"><a href="https://www.buymeacoffee.com/tunjis"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="150"/></a></li>

</ul>


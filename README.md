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

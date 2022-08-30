# Project_1_Dashboard

## Project Overview
We‘re developing our first financial application, a portfolio-analyzer using python and its libraries. 

Ideally, we wanted to use our newly learned skills as well as get experience exploring new python libraries on our own. 

Skills / Technologies Used:
Git
Jupyter Notebook
Importing Libraries
APIs
Cleaning / Preparing Pandas DataFrames
Applying Financial Algorithms
Creating an Interactive Dashboard
Creating Interactive Widgets
Linking widgets to Interactive Visualizations
Organizing / Customizing a Dashboard
Launching the Dashboard

## Requirements
Jupyter Notebook
### Python Libraries (pip install)
yfinance
panel
numpy
pandas
hvplot.pandas

## Usage
The entire program is built to be modular so that you can change the list tickers=[] to create any portfolio you want, as long as its data is on Yahoo Finance.
Once you choose your tickers and run all a dashboard will open in your internet browser.
The panel dashboard includes functionality via panel widgets to adjust; tickers displayed, y-axis, and/or x-axis.
You can also view different plots by clicking on the desired tab. 

### Analysis
Many kinds of analysis are included for each ticker in the program including; 
Time-Series, Daily Returns, Return Distribution, Cumulative Returns, and Sharpe ratios.
Time-Series shows price over time.
Daily Returns helps visualize volatility.
Return Distribution's hvplot is of interest because it uses a violin graph.
Violin graphs can be thought of as an inverted 2-sided bell curve. In this case the graph helps visualize volatility.
Cumulative Returns shows you the return you'd net since the start date of the data.
Sharpe ratio is compared to the first ticker in the tickers list (ticker[0]). This helps you visualize ticker performance vs benchmark ().


###### By: David Garcia, Dylan Olsen, & Khalid Abdulkadir

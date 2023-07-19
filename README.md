## Module 5 Challenge - Financial Planning with APIs and Simulations

### User Story

`UCB Fintech Credit Union, NPO` that focuses on projects to benefit local communities is developing a prototype financial checkup tool so their members are able to perform two basic tasks and sent to CTO for initial feedback for further improvements and enhancements.

To make this all safe, we begin by adding a link to the 'legal disclaimer' that should stop anyone reading here from acting on the advice as this is truly for educational and novelty purposes: 

        + <p style="text-align:center">WARNING !! Before proceeding, read our <font color="red"><ins>*[LEGAL DISCLAIMER](Images/legal_disclaimer.png)* </ins><--- CLICK HERE NOW !! WARNING 

                                                         
*Main features of prototype requested by CTO* 

1) Assess monthly budget and holdings, simulate and forecast a reasonably effective retirement plan based on their current holdings, we visualize and run some scenarios.

     ![Pie Chart of Member Asset Allocation](/Images/portfolio_composition.png)
2) A financial planner for emergencies includes multiple ways to check prices for holdings in 'markdown' code and another for retirement shows 2 main scenarios that could be modified and expanded after feedback from CTO received.

    ![Monte Carlo 30yr Simulation - Distribution](/Images/MC_hist_30.png)
    ![Monte Carlo 10yr Simulation - Distribution](/Images/MC_hist_10.png)

----

### Member Holdings
+ [SPDR S&P 500 ETF Trust (ticker: SPY)](https://finance.yahoo.com/quote/SPY) 
+ [iShares Core US Aggregate Bond ETF (ticker: AGG)](https://finance.yahoo.com/quote/AGG)
+ [Bitcoin](https://finance.yahoo.com/quote/BTC-USD)
+ [Ethereum](https://finance.yahoo.com/quote/ETH-USD?p=ETH-USD&.tsrc=fin-srch)


## Technologies

Libraries, Modules, Methods, Objects

+ *`os`* built-in python module used to interact with the operating system
+ *`requests`* a library used for HTTP requests
+ *`pandas`* a library used for data manipulation and analysis
+ *`alpaca_trade_api`* library used to interact with 'Alpaca API' and collect data
+ *`dotenv`* library for loading `.env` files
+ `MCForecastTools` is a custom package containing Monte Carlo Simulations
+ `watermark` documents code utilized in program/environment
+ `%matplotlib inline` allows placement of visuals in-line with code and display plots/visualizations

``` 
Python version       : 3.7.13
requests        : 2.28.1
pandas          : 1.3.5
alpaca_trade_api: 3.0.2
json            : 2.0.9
```
Methods and Objects

`load_dotenv` is a method from *`dotenv`* module for loading `.env` files

+ [Incorporated font and style changes for notebook Learning some Markdown Code](https://www.markdownguide.org/)

+ [Pie Charts with `matplotlib`](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.pie.html)

+ [Save Figures with `matplotlib`](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.savefig.html)


## Installation Guide

You must have the required libraries and packages installed before running the notebook in your `dev` environment Python 3.7 or higher.

if your current Python environment does already not have all libraries installed: 
        
        pip install requests
        pip install alpaca-trade-api
        conda install jmcmurray json
        conda install python-dotenv -c conda-forge
        conda install watermark -c conda-forge

You will need to [create your Trading API account](https://app.alpaca.markets/signup) in order to copy them into your `.env` file 

## Usage

Navigate inside the repo '05_financial_planner_prototype', clone the repo locally, launch Jupyter Notebook using: 

```
    $ jupyter lab --ContentsManager.allow_hidden=True
   
```
Using the above command will allow you to locate the .env file that contains the keys to alpaca_trade_api

Next open the financial_planning_tools.ipynb file

It will call the `MCForecastTools.py` program to import `MCSimulation` which is how we run Monte Carlo Simulations by and use modular code style.

You can run through the program once ready to proceed from here.

---
## Visualizations




---

## Usage



Navigate inside the repo '05_financial_planner_prototype'
Enter following code in GitBash to launch `jupyter lab`: 

```
    $ jupyter lab --ContentsManager.allow_hidden=True
   
```
## Contributors

Mark Beers: 
[Linked In](https://www.linkedin.com/in/markwbeers/)
---

## License

MIT 

    
---


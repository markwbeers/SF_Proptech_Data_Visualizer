## 06_san_francisco_housing
Module 6 Challenge



conda install -c conda-forge nodejs
# Data Story 
Disclaimer: This data story does not constitute financial advice and is for informational purposes only.
Research and seek professional financial advice before making any investment decisions, 
## especially in... SAN FRANCISCO REAL ESTATE!  

*Housing Units per Year:*
2011 to 2016, the total number of residential units has been steadily increasing year over year with no pull back, showing strong demand and price stability, yet not without risk.  If there were a glut of housing available, there would not likely be a continual increase in units available for residential properties.  Bay Area prices are also very high when considering the median home values, so if markets become volatile and earning sufficient income is difficult, we typically see a boom and bust cycle in San Francisco that normally comes with a spike in interest rates coupled with slow wage growth over the last few economic downturns.  Not a city to be over leveraged if plan to stay in the game.

*Average Prices per Square Foot:*
Prices per square foot consistently rose from 2010 to 2016 overall, though some neighborhoods experience more growth faster and others stall out which can lock up capital and create more risk if underfunded.
+ Proven appreciation exists in neighborhoods like Twin Peaks, Telegraph Hill, and Presidio Heights for long-term value
+ Bayview and Visitacion Valley offer opportunities at lower price point for entry or possibly as a hedge to balance risk

* Interactive Neighborhood Map *
Use the interactive map's hover tool to explore location of high and low priced areas and check history and local plans for their future when performing your due diligence.

* Investment Strategies:
1) Buy turn key properties at lower cost to purchase areas and get renters in fast.  wait for potential capital gains to spike and trade out to a new property or builsd a portfolio using a 1031 exchange.

2) Buy and hold luxury property long term and sell when ready to retire for a great way to diversify retirement assets, income, and funding.

3) House  or Condo Flips, buy distressed or fixer upers near the highest end properties and cash in on your sweat equity as fast as you can do the work and sell.

     
Instructions
Use the san_francisco_housing.ipynb notebook to visualize and analyze the real-estate data.

Navigate to my github repo `https://github.com/cannabbeers/06_san_francisco_housing`
Copy the URL for HTTPS or SSH, clone the repo locally, open in a jupyter notebook

Run code starting with...

Import Dependencies: 
pandas
numpy
hvplot.pandas
holoviews
seaborn
matplotlib
watermark
pathlib

If any are missing from your environment, you may `pip` install them, but recommend:

     $ conda install -c pyviz hvplot
     $ conda install -c conda-forge holoviews
     $ conda install -c conda-forge seaborn
     $ conda install -c conda-forge <other_packages_insert_here>

     



### Technology 


### Locale
**[`locale`](https://docs.python.org/3/library/locale.html)**
locale.currency(val, symbol=True, grouping=False, international=False)
Formats a number val according to the current LC_MONETARY settings.

The returned string includes the currency symbol if symbol is true, which is the default. If grouping is True (which is not the default), grouping is done with the value. If international is True (which is not the default), the international currency symbol is used.

`locale.setlocale(https://docs.python.org/3/library/locale.html#locale.setlocale)

## Code References and Sources for segments in notebook: 

https://stackoverflow.com/questions/1823058/how-to-print-a-number-using-commas-as-thousands-separators/10742904#10742904
https://stackoverflow.com/questions/35019156/pandas-format-column-as-currency
https://stackoverflow.com/questions/320929/currency-formatting-in-python
https://docs.python.org/3/library/locale.html
https://docs.python.org/3/library/locale.html#locale.setlocale



https://hvplot.holoviz.org/user_guide/Customization.html

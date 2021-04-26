# Interim Progress Report
Our project is dealing mainly with the stock of the companies from S&P500 (as of 04/13/2020) to see if the pandemic COVID-19 has a large influence on our selected companies and to give recommendations to individual investors. 

We find data from yahoo finance historical data (from 04/13/2017 to 04/13/2020). The companies are chosen randomly from 11 sectors, each with 10 companies (110 companies in total). In the data processing step (check dataProcessing.py and sp500.xlsx), only date and adjusted close are selected and pasted onto one .xlsx workbook. For each sector, we get the percentage change. (Prof. Groner, you can check this result from output.csv, and temp.csv is just the transpose of it). 

What we are planning to do:
1.    Draw line chart for each sector based on pct_change value (in output.csv) from Jan. 2018 to Apr. 2018, Jan.2019 to Apr.2019, and Jan.2020 to Apr. 2020. Since the outbreak of coronavirus is started in December (in China) and January (globally), and we are now in April. We want to compare “normal year” like 2018, 2019 with “coronavirus year” 2020 to justify that the different large stock movement is caused by the spreading virus. Also, comparing those months from 2018 to 2019 and get the stock trend to get a sense of “normal” stock fluctuating stage. 

Questions and concerns: 
a.    Do we need to choose more years, like 5 years, to justify the “normal” stock fluctuating stage? Now we just have data in the year 2018 and 2019. 
b.    If the number of 110 companies in the sp500 is too less, and we have to select more of them? 
c.    Is inflation a significant noise in our analysis? 

2.    Find data on the gold price and perhaps bond. It is reasonable from either news or common sense, that more investors prefer investing in gold and bond as coronavirus spreads out. We want to create a statistical model and some visualization models, such as heatmap, on gold or bond price to justify that, and compare this trend to the selected companies in sp500 or the sp500 as a whole. 

Questions and concerns: 
a.    Where is the best website or database that we can download or scrape out the gold and price?
b.    What kind of bond do you think is better for us to analyze?

3.    Find data from SARS, including stock and gold prices. Comparing with the history, global disease spreading out in 2003, we care about similarities and differences with coronavirus. So that we can tell the investors what to avoid and what to do. And we will do some predictions in the following months if coronavirus wouldn’t end in April.  
Also, do you mind we just do descriptive analysis, not involving predictive analysis? 

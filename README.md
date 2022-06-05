# Lesson_7
# Primary application file

Produce a Jupyter notebook A Jupyter notebook that contains analysis of an exchange traded fund (ETF) analyzyer. The analysis will be complete with professionally styled and formatted interactive visualizations. As well as deploy the notebook as a web application using teh Voilia library.



---

## Technologies

The following Technologies were used to develop this program:

Python 
    Version 3.9.7

Terminal
    Version 2.12.5 (444)

Visual Studio Code
    Version: 1.66.2 (Universal)
    Commit: dfd34e8260c270da74b5c2d86d61aee4b6d56977
    Date: 2022-04-11T07:49:20.994Z
    Electron: 17.2.0
    Chromium: 98.0.4758.109
    Node.js: 16.13.0
    V8: 9.8.177.11-electron.0
    OS: Darwin x64 21.4.0
    
Jupyter Lab 
    Version 3.2.9

---

## General information about analysis.

The firts part of the project you pull only the pay pal data set and create a dataframe to visualize daily returns and then cumulative returns for pay pal.  The cumulative retruns shows a slight increase from 2017 to 2020. In the beginning of 2020 you see a drop but then a very strong rise in the cumulative returns for pay pal.  The next two steps involve pulling close amounts for pay pal over $200 and the top ten daily returns for pay pal.

The second part you pull the daily returns for all four data sets and create a dataframe showing four coulmns of results.  You then get the average daily returns for the four datasets and create the etf_portfolio_returns dataset.  After that you annualize the returns and then produce a cumulative return dataset that you then create a visualization for the cumulative amounts.  The cumulative amounts are similiar to the pay pal visualizaiton.  Slight rise in 2017 and 2018 then fairly stable for 2019 with a drop early in 2020 followed by a sharp increase.

The final part of the project was to deploy the notebook as a web application using Voila libray and it is attached below.



[![Voila]]([https://youtu.be/T-D1KVIuvjA](https://youtu.be/PSxz_AhPqgA))









---

## Information about datasets

etf database contains four datasets:

GDOT, GS, PYPL, SQ

Data frame containing pay pal information:

pypl_dataframe 

Paypal close prices higher than 200:

pypl_higher_than_200

Top ten return values for Pay Pal:

pypl_top_10_returns

Daily returns for all 4 data sets:

etf_portfolio

Average returns for the four datasets:

etf_portfolio_returns

Cumulative returns of the four datasets:

etf_cumulative_returns






---

## Libraries used in analysis

pandas

numpy

hvplot

SQLalchemy



---

## Contributors


**Chris Miskovich**

Contact Information:

Email: cmiskovich@verizon.net

[LinkedIn](https://www.linkedin.com/in/christopher-miskovich-9a61b0234/) 

---

## License

[MIT](/license.txt)

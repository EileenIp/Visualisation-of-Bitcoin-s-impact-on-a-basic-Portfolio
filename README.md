# Visualisation of Bitcoin's impact on a basic Portfolio 
---

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit_Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Scipy](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)
![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff&style=for-the-badge)

---

## Problem Overview

### As an investment firm we are facing the question whether an allocation to Bitcoin could improve our fund's performance?

To help answer this question, this report will analyze Bitcoin's performance since 2014, alongside the two other major asset classes in our fund, US equities and gold. In doing so we will answer several questions:

- How does the performance of Bitcoin (i.e. risk and returns) compare to the S&P 500 and the price of gold?
- How does the inclusion of Bitcoin change a portfolio's characteristics and can it help improve a portfolio's performance?
- Could Bitcoin be used as a hedge against inflation? (as claimed by crypto bros)

In the light of our fund's goal to minimize risk: What is the minimum volatility portfolio, consisting of these three asset classes? And for comparison: Which portfolio would maximize risk-adjusted returns?

**In this project, required to do:**

*   Exploratory Data Analysis.
*   Bitcoin and Inflation Analysis
*   Porfolio Allocation and Analysis
*   Portfolio Optimisation

---

## Project Summary

This dataset consists of information of bitcoin, S&P 500, gold from Yahoo Finance database, and also information of US consumer price index from FEUD. Bitcoin is another one of the cryptocurrency investment. Through 2013-2017, Bitcoin has reached unbelievable heights. It will be interesting to explore what all other insights can be obtained from comparing to S&P 500, gold prices and US Consumer Price Index.

---

## Conclusion

**Q1) How does the performance of Bitcoin (i.e. risk and returns) compare to the S&P 500 and gold?**

Bitcoin outperforms both S&P 500 and Gold by a significant margin. This outperformance came at the expense of significantly higher risk (across a range of measures like volatility, Value-at-Risk, drawdown or daily trading range). Still, risk adjusted returns of bitcoin (sharpe ratio .77) exceeded those of gold (.28) and equities (.56).

**Q2)  How does the inclusion of Bitcoin change a portfolio's characteristics and can it help improve a portfolio's performance?**

Bitcoin inclusion into our porfolio will increase both the risk and returns significantly. Bitcoin doesn't offers any diversification advantages as we found it to be positively correlated (correlation coeff. of 0.34) with equities thus only increasing returns at the expense of larger risk.

**Q3) Could Bitcoin be used as a hedge against inflation?**

No, there has been no consistent relationship between monthly changes in the general US consumer price level and the price of Bitcoin. During high inflation period bitcoin has performed at its lowest since becoming mainstream which can be seen in the box plot in earlier section. Though, one has to carefull as the low performance can't only attributed to rising interest rate for Bitcoin as there can be a case made that this low performance is due to malpractises in the crypto industry which has been highlighted in the news lately.

## Recommendation

**In the light of our fund's goal to minimize risk: What is the minimum volatility portfolio, consisting of these three asset classes? And for comparison: Which portfolio would maximize risk-adjusted returns?**

Historically, the portfolio minimizing volatility consisted of 42% US equities, 58% gold and no Bitcoin. This portfolio achieved a volatility of 5.8% p.a. since 2014 and a Sharpe ratio of close to 0.56. The maximum Sharpe ratio of 1.46 would have been achieved with an allocation of 47% to US equities, 35% to gold and 18% to Bitcoin. This portfolio's volatility was 19.4% p.a.

Given the very high historic volatility of Bitcoin and its limited diversification value vs. equities, there is no place for Bitcoin, when the goal is to strictly minimize the fund's volatility. But to acknowledge the superior returns and high Sharpe ratio that Bitcoin has shown so far, we still recommend to consider a small fixed allocation of 5% to Bitcoin, alongside 35% in US stocks and 60% in gold. Since 2014 such an allocation would have increased volatility relatively little compared to the minimum volatility portfolio (from 10% to 11%), while significantly improving returns (from 5.8% to 9%) and the Sharpe ratio (from .56 to 0.72).  

---

## Author

- [Eileen Ip](https://www.linkedin.com/in/eileen-ip/)

# FinTech-ETF-Analyzer

A Python &amp; SQL based analysis on a hypothetical exchange traded fund.

Analysis begins with the creation of SQL based dataframes and the plotting of daily / cumulative returns for an individual asset.

A refinement of the inital analysis is then performed for the extraction of closing prices exceeding 200 and top 10 daily returns.

Utlizing the rest of the portfolio, a SQL INNER JOIN is performed, combining all assets on the basis of the GDOT asset's time column.

Calculations are then made to determine the portfolio's daily / annualized / cumulative returns.

---

## Technologies

This analysis runs on python version 3.7, with the following add-ons:


* [voila](https://voila.readthedocs.io/en/stable/index.html) - For conversion of jupyter notebooks into interactive webpages.


---

## Installation Guide

Before running the analysis, the following packages must be installed:

*    pip install SQLAlchemy
*    conda install -c conda-forge voila


---

## Example

For a visual reference as to how voila web interface package works, please refer to the below animation:

![ETF Analyzer Movie](resources/voila_demo.gif)


---

## Contributors

Santiago Rosas


# Credit Union Financial Planner App

## *Introduction*

This app will carry out two primary tasks: **1)** to serve as a financial planner for emergencies, and **2)** to serve as a retirement financial planner.  We will be utilizing API calls to get the most current info on cryptocurrencies, stocks, and bonds to help credit union members come up with the best performing portfolio that can be offered.

---

## Technologies

**Python 3.7.9** was used to code this program, and the code is held in a **Jupyter Notebook** file.  A lot of Python libararies have been utilized to make this program possible: **Pandas, os, requests, json, Alpaca Trade API, Monte Carlo Forecast Tools, and Matplotlib.**

---

## Installation Guide

Since this is a **Jupyter Notebook** file, please open **Jupyter Lab** to run this file.

---

## Usage & Examples

This app will grab API calls using the **requests** library and **json** to get current prices on cryptocurrencies:

![use1](https://user-images.githubusercontent.com/80929342/116836123-36484d80-ab7a-11eb-9a0b-6f95ec4e2ca2.JPG)

---

We will also use **Alpaca API keys** to get current prices on stocks and bonds:

![use2](https://user-images.githubusercontent.com/80929342/116836170-609a0b00-ab7a-11eb-9bb2-3af8806420f3.JPG)

---

The app will then see if the portfolio funds will be enough to fund an emergency portfolio:

![use3](https://user-images.githubusercontent.com/80929342/116836252-abb41e00-ab7a-11eb-86d4-e6895e89ab10.JPG)

---

The next section of the app will run **Monte Carlo simulations** by grabbing 10 years of historical data on stocks on bonds to forecast 30-year and 10-year returns:

![use4](https://user-images.githubusercontent.com/80929342/116836332-f46bd700-ab7a-11eb-90ed-97b012f9f50b.JPG)

![use5](https://user-images.githubusercontent.com/80929342/116836362-19604a00-ab7b-11eb-8d8b-3d461c82b981.JPG)

---

After running the simulations, we will plot the results, and look at the **95% confidence intervals** to determine which weight of stocks and bonds would be best for the credit union members to retire on:

![use6](https://user-images.githubusercontent.com/80929342/116836431-4c0a4280-ab7b-11eb-9575-197ddfbd6d88.JPG)

---

## Contributors

**I would like to thank and acknowledge my UCB FINTECH Class for their questions and input that contribute to the success and knowledge base for the class!**

---

## License

No license is needed to use this app.

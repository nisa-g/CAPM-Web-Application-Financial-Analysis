# CAPM Web Application | Financial Analysis Project

⚙️ **Tool** : Python <br>
💻 **Frameworks** : Streamlit <br>
🗂️ **Source Dataset** : SP500

## 📂 **Project Overview**

This project showcases a web application that is designed to perform CAPM calculations for different stocks. The application uses Python programming language and its libraries such as Pandas, NumPy, Streamlit and Plotly, to gather stock data from Yahoo Finance and perform calculations to determine expected returns.

<br>

---

## 📂 **Task 1 - Project Understanding**

### **Background Information**

#### **CAPM**

- CAPM is a model that describes the relationship between the expected return and risk of securities.
- CAPM indicates that the expected return on a security is equal to the risk-free return plus a risk premium.

<br>

<p align="center">
  <kbd><img width="400" src="https://github.com/nisa-g/Medical-Inventory-Optimization-and-Forecasting/assets/139193734/54878d70-c2e3-4da6-9cb6-f1a4438dbeed"></kbd> <br>
  Figure 1 — CAPM Formula
</p>
<br>

#### **Risk Free Asset Return**

- A risk free asset could be a US Government 10 year Treasury bill.
- Investors who are extremely risk averse would prefer to buy the risk free asset to protect their money and earn a low return.
- If investors are interested in gaining more return, they have to bear more risk compared to the risk free asset.

#### **Market Portfolio Return**
- Market portfolio includes all securities in the market. A good representation of th emarket portfolio is the S&P 500.
- Market portfolio return is the average return of the overall return of the SP500.

#### **Beta**
It is a measure of a stock's risk (volatility of returns) reflected by measuring the fluctuation of its price changes relative to the overall market.

ß = 0: No Market Sensitivity <br>
ß < 1: Low Market Sensitivity <br>
ß = 1: Same as Market (Neutral) <br>
ß > 1: High Market Sensitivity <br>
ß < 0: Negative Market Sensitivity <br>

**Project Objective:** 
- To develop a wep application for CAPM financial model analysis.
- To evaluate the risk associated with different investment options by using CAPM to calculate the expected rate of return for each investment.

---

## 📂 **Task 2 - Development of Web Application**

### **Background Information**

We developed a web application using Python with Streamlit framework to quickly create interactive and data-driven web application. Streamlit is known for its simplicity and ease of use, making it a best choice for us looking to deploy data applications without extensive web development expertise. Here's the methodology to develop the web application using Streamlit:

**1. Application Code:**
- Create CAPM_Returns.py and capm_funtions.py to write the code for our web application.
- Import the necessary libraries, including streamlit, pandas, yfinance, datetime and pandas-datareader.
- Define the layout and functionality of our application, including text inputs.

**2. Data Integration:**
- Get input from user and download data for SP500.
- Create functions to normalize prices based on the initial price, calculate daily returns and beta value.

**3. Run Application:**
- Open cmd terminal, navigate to our project directory, and run the application using streamlit run CAPM_Returns.py

---

## 📂 **Task 3 - Web Deployment**

### **Result**

<br>

<p align="center">
  <kbd><img width="900" src="https://github.com/nisa-g/Medical-Inventory-Optimization-and-Forecasting/assets/139193734/a47a0d59-b3a6-409c-be4e-fae8ecfbd796"></kbd> <br>
  Figure 2 — Dataframe head and dataframe tail with 4 selected stocks (Tesla, Apple, Amazon & Google).
</p>
<br>

<br>

<p align="center">
  <kbd><img width="900" src="https://github.com/nisa-g/Medical-Inventory-Optimization-and-Forecasting/assets/139193734/bbbf3332-dd96-494a-9fa3-b809a57252f1"></kbd> <br>
  Figure 3 — Price of all stocks before and after normalizing.
</p>
<br>

<br>

<p align="center">
  <kbd><img width="900" src="https://github.com/nisa-g/Medical-Inventory-Optimization-and-Forecasting/assets/139193734/fda77db4-04d1-4795-ba0b-963636571727"></kbd> <br>
  Figure 4 — Calculated Beta value and CAPM return value.
</p>
<br>




### BANK MARKETING CAMPAIGN Tim Alpha JCDS03 Batam Final Project

Nilam Ayu Rosari,
Novaldi Halomoan

Business Context:

This case delves into one of the banking products known as term deposits. A term deposit is a type of investment where an individual puts a certain amount of money into a bank for a certain period of time and earns an interest rate. Banks utilize the funds from term deposits to lend money to other customers in the form of loans. Essentially, the bank acts as an intermediary and generating income through the interest charged on these loans. The interest rate offered to depositors is lower than the interest rate charged on loans, allowing the bank to make a profit from the difference, known as the interest rate margin or commonly known as the net interest margin (NIM). Net interest income, on the other hand, represents the total revenue derived from these interest-earning activities. NIM and net interest income are closely linked to profitability indicator. Therefore, having larger term deposits allow bank to have more capital available for lending, which in turn, can lead to higher interest income and contribute positively to a bank's profitability. The dataset For this case is based in Portugal and in 2023, bank profits soared 50% from 2022. This result was achieved due to the increase in net interest income (source: https://www.theportugalnews.com/news/2023-07-30/portuguese-banks-profit-soar/79877).

Problem Statement

So how bank get larger term deposits? One effective strategy to achieve this is to attract customers to subscribe to a term deposit is through marketing campaigns. A bank marketing campaign serves as a bridge between financial institutions and customers, enabling banks to promote their products and services. When executed effectively, a bank marketing campaign for term deposits benefits both the bank and its customers by increaing business to potential higher profit for bank and potential saving with interest rate for customers.

Therefore the bank should be able to conduct a marketing campaign targeting the right customers who are likely to subscribe term deposit and should minimize the possibility of targeting customers who are not willing to make a deposit because it can incur several costs for a bank such as wasted resources like money and time and also miss the opportunity to engage with the right custumers. There are various type of marketing campaign and one of it is via telemarketing. Telemarketing is a direct marking strategy method in which a salesperson acquires the prospective customers’ willingness to purchase products or services over phone calls (Palaniappan et al., 2017). Notably, many financial services providers adopted telemarketing strategy to reach out to the new customers, providing better services to existing customers and meeting their specific needs (Moro et al., 2014).

Goals

Based on the problem statement above, the bank aims to identify customers who have a higher chance of subscribing to a term deposit and focus marketing efforts on such clients. By seeking the ability to predict prospective subscribers, the bank aims to direct its marketing campaigns solely towards individuals genuinely interested in subscribing. This strategy aims to minimize costs and seize income-generating opportunities efficiently. Furthermore, the bank seeks to identify the primary features influencing subscription to deposits. This approach will enable the bank to streamline focus on these crucial attributes in future operations.

Customer will be divided into two targets class, as follows:

Target

0: Customers unlikely to subscribe term deposit.

1: Customers likely to subscribe term deposit.

We will build a classification model to help the bank predict whether a customer will subscribe term deposit or not. Metric we choose is Precision because we want to minimuze False Positive.


In this notebook the of content will be

List of contents:
- Business Context and Problem Statement
- Data Understanding
- Data Cleaning
- Exploratory Data Analysis
- Data Preprocessing
- Machine Learning Modelling
- Hyperparameter Tuning
- Model Implementation
- Conclusion and Reccommendation

Based on Data is highly imbalance 88% class no, therefore we conducted startisfied random sampling before going to deep analysis and modelling. And from data cleaning and EDA inferential statistical test, we drop column anomaly of 'euribor3m' and statistically not significant column 'loan'. In the end, we find logistic regression model is the most optimum model. as precision after tuning for train data is 86.25% to test score as 86.27%. After modelling, we concluded that our solution will save around 48.9% marketing cost.

# Personal Finance Dashboard
A full-stack personal finance application designed to consolidate financial data 
from multiple banking and credit card accounts into a centralized dashboard. 
The application aims to help users track transactions, understand spending habits,
manage budgets, and monitor credit card debt. Future plans include 
a custom machine learning model to automatically categorize transactions 
and provide deeper insights into spending patterns.

## Why I'm Building This

If you're anything like me, your money probably moves through multiple financial institutions,
making it time-consuming to understand where your money is going and what your biggest expenses are.

I'm building this application to simplify that process and make it easier to understand 
my overall financial health. Although I'm initially building it for myself, 
I hope others who face the same challenges will find it useful too.

## Project Overview

## Problem Statement
### 1. What is frustrating about your current process?

Managing finances across multiple banks and credit card accounts can be tedious. Each institution has its own app or website, so getting a complete picture of my finances means constantly switching between platforms. While each institution provides its own transaction history and spending summaries, there's no convenient way to see everything together.

### 2. What information is difficult to see across all your accounts?

The biggest challenge is understanding my overall spending habits. I want to know how much I'm spending each month,
which categories account for the largest portion of my expenses, and how those patterns change over time. 
It's also difficult to get a consolidated view of my credit card balances, outstanding debt, 
and overall financial position without manually comparing information across accounts.

### 3. What decisions would become easier with this application?

Having all my financial information in one place would make it easier to identify unnecessary expenses,
establish realistic budgets, and prioritize paying down credit card debt. 
I'd also be able to recognize changes in my spending habits earlier and make adjustments 
before they become bigger problems. Ultimately, I want to spend less time figuring out where my money went 
and more time deciding what to do with it.

## Project Goals

The primary goal of this project is to create a centralized platform that simplifies personal financial management and provides meaningful insights into spending habits.

1. **Centralize Financial Information**
    - Consolidate banking and credit card account information into a single dashboard.
    - Automatically synchronize account balances and transactions where supported.
    - Minimize the need to manually review multiple financial applications.

2. **Provide Meaningful Spending Insights**
    - Track and organize transactions across connected financial accounts.
    - Visualize spending by category, merchant, and time period.
    - Identify recurring expenses and changes in spending habits.

3. **Improve Budgeting and Debt Management**
    - Allow users to establish and monitor monthly budgets.
    - Track outstanding credit card balances and debt repayment progress.
    - Help users make informed financial decisions through spending analysis and debt payoff projections.

4. **Develop Intelligent Transaction Categorization**
    - Build a custom machine learning model to automatically categorize transactions.
    - Allow users to review and correct transaction categories.
    - Improve categorization accuracy over time using user-provided corrections.

5. **Build a Reliable and Secure Application**
    - Protect sensitive financial information and account credentials.
    - Maintain accurate financial records while avoiding duplicate transactions.
    - Design an application that is maintainable, testable, and capable of supporting additional financial institutions and features in the future.

## MVP Features
The initial version of the Personal Finance Dashboard will focus on securely retrieving financial data from supported institutions and presenting a consolidated view of a user's finances.

Core Features

1. Financial Account Integration
   - Connect supported bank and credit card accounts using Plaid.
   - Retrieve account balances and transaction histories.
   - Support manual refreshing of financial data.

2. Financial Data Processing
   - Persist account and transaction information in PostgreSQL.
   - Normalize and validate financial data.
   - Prevent duplicate transactions.
   - Calculate financial metrics using Python and SQL.

3. Financial Overview Dashboard
   - Display connected financial institutions and their respective accounts.
   - Aggregate total checking and savings balances.
   - Aggregate outstanding credit card balances.
   - Calculate net cash position.
   - Display account-level balances and refresh timestamps.

4. Transaction Analytics

    - View transactions across connected accounts.
    - Filter transactions by account and date. 
    - View monthly spending totals. 
    - Visualize spending by transaction category.

MVP Success Criteria
The MVP will be considered complete when:
    - A user can connect at least one simulated financial institution through Plaid Sandbox.
    - The application can retrieve and persist account balances and transactions. 
    - Repeated synchronization does not produce duplicate financial records. 
    - Financial data can be transformed into accurate aggregate metrics.
    - The dashboard displays individual account balances, total banking balances, total credit card debt, and net cash position.
    - Users can view their transactions and understand their spending by category.
    - The complete application can run locally using free development tools.

## Tech Stack

## Future Enhancements
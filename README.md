# Building a Stock Analysis System with Buy/Sell Recommendations

## Description
This notebook implements a rule-based stock analysis system that fetches financial data for a given company (e.g., AAPL) from multiple APIs, processes the data, calculates a score based on financial metrics, and provides a Buy/Sell recommendation with reasoning. The system uses weighted scoring logic to evaluate the company's performance and generate actionable insights.
While the current implementation is deterministic and rule-based, it serves as a foundation for creating an AI agent by adding autonomy, learning capabilities, and natural language interaction.

## 1. Prerequisites
Install required libraries:
### pip install transformers requests

## 2. Input Parameters
1. API Key: Used to authenticate API calls.
2. Company Name: The stock ticker symbol (e.g., AAPL) for which the analysis is performed.

## 3. Workflow
Step 1: Fetch Data from APIs <br>
The notebook fetches data from 7 APIs provided by Financial Modeling Prep:

API 1: Real-time stock price and basic metrics.

API 5, API 6, API 7: Historical financial statements (income statement, cash flow statement).

# 📞 Megaline Telecom Plan Analysis

## 📝 Project Overview
The project involves a preliminary analysis of two prepaid mobile plans offered by the telecom operator Legaline - Surf and Ultimate. The company's commerical department is looking to determine which plan generates more revenue, in order to make informed decisions about advertisting budget allocation. 
The dataset consists of data on 500 Megaline clients for the year 2018, including usage data (calls, messages, internet) and user demographics. 

## 📂 Datasets
- megaline_calls.csv - records of call durations per user
- megaline_messages.csv - number of messages sent
- megaline_internet.csv - megabytes used in each web session
- megaline_users.csv - client profiles and their subscribed plan 
- megaline_plans.csv - plan details for Surf and Ultimate

## 💼 Description of Plans
### Surf Plan:
  - Monthly Fee: $20
  - Includes: 500 minutes, 50 texts, 15 GB data
  - Extra Charges:
      - Calls: $0.03/min
      - Texts: $0.03/msg
      - Data: $10/GB
### Ultimate Plan:
  - Monthly Fee: $70
  - Includes: 3000 minutes, 1000 texts, 30 GB data
  - Extra Charges:
      - Calls: $0.01/min
      - Texts: $0.01/msg
      - Data: $7/GB
  Note: 
  - Call durations are rounded up to the nearest minute.
  - Total data usage per month is rounded up to the nearest gigabyte (1GB = 1024 MB).

## 📊 Key Findings
### 📈 User Behavior Analysis
- Call Patterns:
    - Surf and Ultimate users make a similar number of call, with close usage distributions.
- Messages and Internet:
    - Surf users tend to send more messages and use more internet compared to Ultimate users.
- Seasonal Trends:
    - Both messages and internet usage show an increase toward December suggesting end-of-year digital activity spikes.

## 💵 Revenue Analysis
- Despite heavier usage, Surf users generate less revenue due to lower overage charges and monthly fees.
- Ultimate users generate higher average monthly revenue, supported by the higher plan fee and modest overage charges.

## 📓 Instructions to Reproduce
Run the analysis in a Jupyter Notebook. Include:
  - Code in code cells
  - Explanations in Markdown cells
  - Appropriate use of visualizations, descriptive statistics, and hypothesis testing

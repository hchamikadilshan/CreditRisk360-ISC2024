# CreditRisk360-ISC2024

## Overview
This project analyzes credit application data to detect potential fraud and financial risk. The dataset consists of 7,000 observations, each representing an individual who applied for credit. It includes a combination of demographic, financial, and behavioral variables.

## Dataset Information
- **Number of Observations:** 7,000
- **Purpose:** Fraud detection and risk assessment

## Description of Variables

### Personal & Demographic Details
- **Account_open_date:** Date on which the account was opened.
- **Age:** Age of the customer.
- **Location:** Customer's location.
- **Occupation:** Customer's occupation.
- **Income_level:** Customer's income level.

### Credit & Financial Information
- **Fico_score:** Credit score (300–850) assessing borrower's creditworthiness.
- **Delinquency_status:** Number of days a customer is late in making payments.
- **Number_of_credit_applications:** Total credit applications submitted by the customer.
- **Debt_to_income_ratio:** Ratio of debt to income, indicating financial stress.
- **Max_balance:** Highest account balance ever recorded.
- **Avg_balance_last_12months:** Average account balance over the past year.
- **Number_of_delinquent_accounts:** Count of accounts with missed payments.
- **Number_of_defaulted_accounts:** Count of accounts where the customer has defaulted.

### Behavioral & Risk Indicators
- **Earliest_credit_account:** Date of the first credit account opened.
- **Recent_trade_activity:** Date of the most recent transaction activity.
- **New_accounts_opened_last_12months:** Number of new accounts opened in the last year.
- **Multiple_applications_short_time_period:** Boolean indicating multiple applications in a short period.
- **Unusual_submission_pattern:** Boolean indicating irregular transaction behavior.
- **Applications_submitted_during_odd_hours:** Boolean indicating transactions outside standard business hours.
- **Watchlist_blacklist_flag:** Boolean indicating if the user is flagged as high risk.
- **Public_records_flag:** Boolean indicating if the user has records affecting creditworthiness.

### Target Variable
- **Charge Off Status:** Boolean variable:
  - **True:** Account has been charged off due to non-payment over an extended period (typically 120–180 days).
  - **False:** Account is active or has not reached charge-off status.

## Competition Submission
This initial solution was submitted for the **International Statistics Conference 2024 (ISC 2024)**, organized by the **Institute of Applied Statistics, Sri Lanka (IASSL)**. The event will take place on **December 28–29, 2024, at Cinnamon Lakeside Colombo, Sri Lanka**.

In conjunction with ISC 2024, a case study poster competition is being held to provide undergraduates and recent graduates with an opportunity to showcase their analytical and presentation skills. Teams must collaborate to analyze real-world data and present their findings.

For more details, visit the competition website: [ISC 2024 Case Study](https://thiyangt.github.io/ISC2024.case.study/).

## Authors & Acknowledgments
- **Author 1:** Chamika Dilshan Hapuarachchi
-  **Author 2:** Purani Rashmika Annasiwatte
- **Affiliation:** University of Sri Jayewardenepura

  
- **Acknowledgments:** Special thanks to ISC 2024 organizers and dataset providers.

## License
This project is open-source and available under the MIT License.

## Contact
For inquiries, please reach out via hchamikadilshan@gmail.com.


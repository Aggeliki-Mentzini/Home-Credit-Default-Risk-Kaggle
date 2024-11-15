# Home-Credit-Default-Risk-Kaggle [https://www.kaggle.com/competitions/home-credit-default-risk/data]



This project was created as part of my learning journey. It may include code snippets or examples sourced from tutorials, open-source repositories, or other educational materials. 

I have made efforts to attribute these sources appropriately wherever applicable. If you notice missing or incorrect attributions, please feel free to reach out or open an issue.

Disclaimer: This code is intended for educational purposes and may not be fully optimized or suitable for production.







In this competition, I am tasked with predicting clients' future payment behaviors based on raw data that includes application details, demographics, and historical credit information. Rather than working with pre-processed, aggregated data, I am starting with detailed monthly and credit-level data. This format allows me to explore various ways of structuring the data and to experiment with different levels of feature engineering. My approach will involve carefully selecting and crafting features to capture meaningful trends and patterns in client behavior, as well as testing different machine learning models to see if advanced feature engineering, or a simpler model approach, yields better results. To assist with this process, I am using the provided column descriptions to ensure I make informed decisions when creating and selecting features.



Dataset Description

application_{train|test}.csv: Main data table. Train file includes target labels, test file does not. Each row represents one loan.

bureau.csv: Records of clients’ previous credits with other institutions as reported to the Credit Bureau. Multiple rows per client, representing individual credits.

bureau_balance.csv: Monthly balance history for each credit listed in bureau.csv. Multiple rows per credit per month.

POS_CASH_balance.csv: Monthly snapshots of previous POS and cash loans from Home Credit. Multiple rows per loan per month.

credit_card_balance.csv: Monthly balance history of previous Home Credit credit cards. Multiple rows per credit card per month.

previous_application.csv: All prior applications for Home Credit loans. Each row represents one previous application.

installments_payments.csv: Repayment history for prior Home Credit loans, with one row per payment (or missed payment).

HomeCredit_columns_description.csv: Descriptions of columns in all datasets.




NOTES

- The XGBoost model (eXtreme Gradient Boosting) is a powerful, optimized implementation of gradient boosting, a machine learning algorithm used primarily for classification and regression tasks. It has become one of the most popular algorithms in data science and competitive machine learning because of its high performance, efficiency, and flexibility.

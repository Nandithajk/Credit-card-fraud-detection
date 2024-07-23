# Credit-card-fraud-detection
## Machine Learning | Logistic Regression | Decision Tree | Random Forest

## Introduction to Credit Card Fraud Detection
Credit card fraud poses a significant threat to both financial institutions and cardholders, leading to substantial financial losses and potential harm to individuals. In response to this challenge, advanced technologies and machine learning techniques have been employed to develop robust fraud detection systems.

## The Importance of Fraud Detection

#### Financial Loss Prevention: 
Fraudulent transactions result in financial losses for both credit card companies and their customers. Early detection allows for prompt action to mitigate these losses.

#### Customer Trust and Satisfaction:
Rapid detection and response to fraud contribute to maintaining customer trust. Prompt resolution of fraudulent activities enhances overall customer satisfaction.

#### Regulatory Compliance:
Financial institutions are subject to various regulations aimed at protecting consumers. Implementing effective fraud detection systems helps ensure compliance with these regulations.

## Dataset Overview:

The dataset comprises simulated credit card transactions, encompassing both genuine and fraudulent activities. The data is presented in CSV format, sourced from the Kaggle public dataset. Generated using the Sparkov Data Generation tool developed by Brandon Harris, the dataset spans from January 1, 2019, to December 31, 2020.               
link for the datset :- https://www.kaggle.com/datasets/kartik2112/fraud-detection/data

### Key Characteristics:

#### Transaction Volume: 
Approximately 1.3 million transactions are recorded in the dataset, involving 1000 customers and 800 merchants.

#### Features:
The dataset incorporates 21 features, providing diverse insights into each transaction. Key features include cc_num (credit card number), merchant, category, amount, gender, city_population, job, date of birth, is_fraud, city, state, zip, and others.
## Features in the Dataset:

1. trans_date_trans_time: Date and time of the transaction.
2. cc_num: Credit card number (potentially masked for privacy).

3. merchant: Name or identifier of the merchant involved.

4. category: Categorization of the transaction (e.g., retail, dining).

5. amt: Transaction amount.

6. gender: Gender of the cardholder.

7. city_pop: Population of the city where the cardholder is located.

8. job: Occupation or job of the cardholder.

9. dob: Date of birth of the cardholder.

10. is_fraud: Binary indicator (0 or 1) for fraudulent transactions.

#### These features play a crucial role in understanding and analyzing the dataset. They include transaction details, cardholder demographics, and a key indicator for fraud detection. Exploring relationships and patterns within these features is essential for deriving meaningful insights and building effective machine learning models.

11. first and last: The first and last name of the cardholder, providing personal identification details.

12. street: Street address of the cardholder, contributing to location specifics.

13. city, state, zip: Geographic details of the cardholder's residence, offering a comprehensive location profile.

14. lat and long: Latitude and longitude coordinates of the cardholder's and merchant's locations, enabling spatial analysis.

15. trans_num: Transaction number or identifier, aiding in unique transaction identification.

16. unix_time: Transaction time represented in Unix timestamp format, facilitating time-based analysis.

17. merch_lat and merch_long: Latitude and longitude coordinates of the merchant's location, essential for understanding transaction geographics.

#### These additional columns provide detailed information about the cardholder's residence, transaction-specific identifiers, and geographical  coordinates crucial for spatial analysis. Including these features in your analysis can contribute to a more comprehensive understanding of the dataset.


# Ecommerce-Purchases-Analysis
**Introduction**
The "Ecommerce Purchases Analysis" project is focused on exploring and analyzing a dataset of ecommerce transactions. 
This dataset, obtained from Kaggle, includes information about customers and their purchases, along with details such as credit card providers, 
job titles, languages, and more. This project aims to provide insights into customer behavior and preferences, uncover patterns in purchasing habits, and identify trends that could guide future business decisions.

**Data Loading and Overview**
The analysis begins by loading the dataset using the Pandas library and performing an initial data overview. 
The top and bottom rows are displayed for a quick snapshot of the data, including a review of the column data types, null values, and dataset dimensions. 
Any missing values or duplicates are handled, ensuring clean data for further analysis.

**Data Exploration and Visualization**
The data exploration step dives into the structure and completeness of the dataset. Here, the column data types are reviewed, 
and missing values are checked and addressed. Following this, a set of visualizations is created to provide a high-level understanding of customer demographics and purchase behaviors. 
Visualizations include:

     Distribution of Purchase Prices: A histogram that illustrates the spread of purchase amounts, showing where most transactions fall in terms of value.
     Language Distribution: A bar chart displaying the different languages spoken by customers, giving insight into the cultural diversity of the customer base.
      
**Purchase Price Analysis**
This section focuses on evaluating pricing patterns within the dataset:

      Highest and Lowest Purchase Prices: The maximum and minimum purchase values are identified to understand the price range.
      Average Purchase Price: The average purchase price is calculated, providing a baseline for typical spending amounts in the dataset.
      
**Customer Segmentation by Purchase Value**
To further explore purchasing behavior, customers are segmented based on purchase amounts into "Low", "Medium", and "High" spenders. 
This segmentation offers insights into customer types and their spending habits, which can help target promotions more effectively.

**Language and Job Title Analysis**
The analysis of customer language and job title distribution provides a deeper view into customer demographics:

       Language Distribution: The number of customers by language is analyzed, with specific focus on identifying customers who speak French.
       Job Title Analysis: Customers with "Engineer" in their job titles are identified to showcase the diversity of professions within the customer base.

**Email and Credit Card Analysis**
This analysis focuses on specific customer identification criteria:

      Email Lookup by IP Address: The email address associated with a given IP address is retrieved.
      High-Value Mastercard Purchases: Customers using Mastercard with purchases above $50 are identified, helping to analyze spending trends by payment type.
      Email by Credit Card Number: The project also retrieves email addresses based on specific credit card numbers, demonstrating targeted lookup capabilities.
 
**Time of Purchase Analysis (AM/PM)**
With only an AM/PM indicator for purchase times, the analysis examines transaction volume trends between morning and evening. This categorization gives a general view of customer activity, 
showing whether purchases are more likely to occur in the AM or PM.

**Credit Card Expiry and Email Provider Analysis**
This section provides insights into customer preferences and upcoming expiration trends:

**Credit Card Expirations**
Identifying customers with credit cards expiring in 2020 helps in understanding future renewal opportunities.
Top Email Providers: The top 5 most common email providers among customers are identified, offering insight into popular email domains that could be used for email-based marketing strategies.

**Credit Card Fraud Analysis**
A potential fraud analysis is conducted by filtering high-value purchases in the AM period, as such behavior might indicate unusual transaction patterns. 
This approach provides a preliminary method for fraud detection based on time and purchase amount.

**Conclusion**
This analysis offers a multi-faceted view of ecommerce customer data, highlighting key areas such as spending habits, demographic diversity, purchasing patterns by time, 
and credit card provider usage. The insights gained from this project can be valuable for understanding customer behavior, guiding marketing strategies, and
identifying potential high-value customers or unusual purchasing patterns for further investigation.

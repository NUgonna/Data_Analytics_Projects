## Project 1: Revenue and Customer Churn Analysis
### Goal: 
The client wants to improve customer retention by identifying high value customers and churn risks.  This project was able to explore this issue by using data to answer important questions and provide recommendations based on the insights. Before using the data for analysis, data cleaning was conducted to the best of my knowledge. 

### About the data: 
This is real business data of a Telecommunication company in California for Q2 2022 (The company has been kept anonymous). The data was provided publicly by Maven Analytics (https://www.mavenanalytics.io/data-playground). It is a Telecom Churn Dataset consisting of 2 tables. The first table is the Customer churn table which provides details of a customer demographic, location, subscription service, how long the customer has stayed with this company etc. and the second table (Zip Code Population). 

As I earlier said, the client wants to me to identify his high-value customers based on revenue  and churn risks. I approached this project by asking and answering the following questions:

### Question 1:	What is company's revenue for Q2 2022?
The company made $21.37M from all customers in this quarter and churned customers contributed 17.22% of the total revenue, which is $ 3.68M. 
![image](https://user-images.githubusercontent.com/51289316/182013091-e225f2f6-e088-4e65-b808-1df9ef538be6.png)


### Question 2:	Who are the company’s high-value customers by revenue?

![image](https://user-images.githubusercontent.com/51289316/182013388-60860502-e6f2-4581-8c24-c84b0c912058.png)


- 42.29% of the company’s revenue come from customers with a two-year subscription, 28.88% of its revenue comes from One-Year contract subscribers and 28.84% of its revenue come from Month-to-Month contract Subscribers.

- New subscribers were seen not to contribute to the company’s revenue in this quarter.
- Customers living in Los Angeles, San Diego, San Francisco, Sacramento, San Jose, and Fresno were high contributors to the two-year subscription revenue. 

### Question 3:	Which subscription/contract package witnessed the highest churn?
The month-to-month subscribers made up 88.55% of the total churned customers. Making the month-to-month subscription package the highest churned package.

![image](https://user-images.githubusercontent.com/51289316/182013404-2dfeb2ea-6289-41cc-89d6-cede8d5c4415.png)

### Question 4:	Why are customers leaving?

Based on Churn category, 45% of the customers moved to the competitors (due to better offers, better devices, offered more data and offered high download speed), 17.17% of the customers left out of dissatisfaction with products and network, 16.80% left due to poor attitude of service provider and support team, 11.29% due to price and 9.74% due reasons around death of customer and relocation.

![image](https://user-images.githubusercontent.com/51289316/182020772-a1032336-3534-4d20-8e89-c4c6b437e4f2.png)

### Question 5:	When are customers leaving?
In Q2 2022, the highest churn rate is 20.33% and the customers in this category are customers who joined the company between 1 - 2 months and subscribed to the monthly packages.

![image](https://user-images.githubusercontent.com/51289316/182014625-4e63ffac-ad62-4608-ac45-6bfe3fcffad6.png)

### Other insights important in this project
- 56.23% of customers who churned had no offers
-	Offer A experienced the lowest churned customers.
-	Offer E experienced a high churn rate of about 22.79%
-	San Diego and Los Angeles customers have the highest churned customers. 

![image](https://user-images.githubusercontent.com/51289316/182015226-c4c111fe-82f1-470b-b059-7af97d2c3e4b.png) ![image](https://user-images.githubusercontent.com/51289316/182015263-67778d0d-9270-4d2c-abc8-ab4635e855e6.png)

### Recommendations
1. 45% of churned customers are moving to competitors for better offers, better devices, stable networks and lower price offers. 
  a. Conduct competitor market research to find out what deals are your competitors offering, review current offers and see how you can match them while remaining        competitive.
  b. Carry out regular maintenance checks on the current network infrastructure to ensure network stability
  c. In cases where network infrastructure is beyond repair, invest in a better one.
  
2. 16.80% of customers left because of poor attitude from support staff: Emotional Intelligence training should be given to all employees, especially the support staff.

3. 56.33% of churned customers had no offers (This should not be neglected). Send promotional emails to newly joined customers especially customers living in San Diego and Los Angeles notifying them of Offer A since Offer A has the lowest churn rate compared to other offers. 

4. Encourage new customers to sign-up for 2-year contract packages, this will help increase customer retention as customers in this segment tend to stay longer with the company.

5. San Diego and Los Angeles customers are high priority customers and the most dissatisfied customers in this quarter. Increase marketing efforts in these cities.


## Project 2:  Sales Analytics Dashboard

### Overview
The sales analytics dashboard provides a unified view of sales for a certain company across three years (January 2018 - June 2020). 

Before designing the dashboard, these were the processes I took:
1. Selection of KPIs
2. Collection of Data (The dataset used for this dashboard is a free dataset from kaggle.com)
3. Data Cleaning
4. Data Modelling (I worked with 3 different tables in a CSV sheet, data was modelled in Data Studio)

### Insights

The first scorecard on the dashboard shows the company revenue in the current year (2020). The semi-annual revenue growth is up by 94.6% within the same period from the previous year. 

Furthermore, bikes contribute approximately 96% of the overall sales from 2018 to mid-2020, and the company's major markets are the United States and Australia, each contributing 31.7% and 29.5% respectively to overall sales.

View [interactive report here](https://datastudio.google.com/reporting/a865116c-b80a-4b38-9137-e90a79a167a3)

![image](https://user-images.githubusercontent.com/51289316/178504888-272ac566-b2a0-46a6-901d-b85a6b0d2f89.png)![image](https://user-images.githubusercontent.com/51289316/178505039-4f6401d5-cb17-4b97-bff0-aa6548366e00.png)

# PowerBI-CustomerChurnAnalysis
This is a PowerBI App which uses multiple datasets from a bank to gain powerful insights into its customer churn analysis

Churn definition-
The following from Investopedia is a suitable definition: "The churn rate, also known as the rate of attrition or customer churn, is the rate at which consumers discontinue transacting business with a firm." Churn makes me think of the leaky bucket predicament. Even if you add more water to the bucket (or in this case, more clients), your overall revenue won't increase if some of your current clients depart. Reducing churn is a primary priority for many firms because keeping current customers is easier than finding new ones.
![image](https://user-images.githubusercontent.com/87760177/212668302-ba350020-5c73-436d-a5fe-4c9378db0a8a.png)

Determining churn-
To calculate churn, divide the total number of customers by the number of customers who left. We have a 10% churn rate if we have 100 clients overall throughout that time period and 10 of them decide to leave. There are various ways to calculate churn, and they vary by industry. If a consumer hasn't made a purchase in the past year, a typical e-commerce platform would label them as churners.
The data- 
There are multiple data sets and I have tried to make a star schema for data modeling-
![image](https://user-images.githubusercontent.com/87760177/212669800-219942a2-dd69-4083-ae4e-1c8427fc5052.png)


Determining churn %
I have created it as a measure-
![image](https://user-images.githubusercontent.com/87760177/212668026-0499d7ce-fa4f-436d-b0cc-b2d696645e12.png)

Some Insights-
ExitCustomers and total previousmonthexitcustomers are positively correlated with each other.
Average Total Customers was higher for Active Member (429.25) than Inactive Member (404.08).
Total Customers for Active Member and Inactive Member diverged the most when the Month Name was Jul, when Active Member were 73 higher than Inactive Member.
ExitCustomers for Female (1139) was higher than Male (898)
Across all 5 CreditType, ExitCustomers ranged from 128 to 685.

I also found that maximum churn is from Germany using Maps-
![image](https://user-images.githubusercontent.com/87760177/212669001-19e88e64-1375-4698-963f-35e37e811c2b.png)


Further, I have also made a dashboard of my report to share with the organization.
I have also created an App which includes both Dashboard as well as the report together.For other useful insights my App is published for everyone as well-
check it out !
https://app.powerbi.com/groups/me/apps/8ad3c9b9-631a-4ab8-bb1e-cc0b29406261/dashboards/790b5955-c3bb-47e1-b2ca-c0bb4e977bc2


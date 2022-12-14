# Bank Customer Churn Analysis using Tableau

The Bank Customer Churn dataset consist of 13 columns and 10,000 rows. This particular bank has its branches in France, Germany & Spain. Dataset consist of number of customers who are the client of the bank, record of active as well as exited or customer who left the bank also includes information regarding how many customers are credit card holders and consist of information regarding tenure which basically shows that for how many years the customers were the client of the bank. Customers who were the client of bank for longer period of time are loyal and less likely to churn. Dataset also includes information regarding balance of customers in their account as well as their estimated salary, credit card score and customer’s age. Before analyzing the data the quality of the data has been checked. Tableau dashboard consist of filters and it is an interactive dashboard where user can interact with the dashboard to find answers to the business questions.
* **Purpose of Bank Customer Churn Analysis Project** is to analyze customer data and find out among male and female customers who are most likely to churn and why and also to find answers to some of the below business questions.
* Before analyzing the data the quality of the data has been checked.
* Used Business Intelligence tool Tableau the Bank Customer Churn Analysis dashboard has been created. The dashboard consist of filters and it is an interactive dashboard where user can interact with the dashboard to find answers to the business questions.

## **Finding answers to the following questions**: 

**Q.1) What is the total percentage of active customers?**

Ans. 

![Ans1)](https://user-images.githubusercontent.com/87359806/170265109-160ef346-77a9-4199-9dd4-3a64974266bb.PNG)

51.5% active customers are there out of total 10,000 customers.


**Q.2) Gender wise compare the active customers & exited customers.**

Ans.

![ans2](https://user-images.githubusercontent.com/87359806/170264133-de077b53-160f-4d04-8b29-aead12f19a90.PNG)

In the above dashboard we can use filter so we simply select male from the donut chart so that data get filtered according to that. Then we can observe that the total Male active customers are 2,867 and exited customers are 898. For Female customers we could select female in that donut chart to filter it out accordingly then we could observe that total active customers are 2,284 and exited customers are 1,139. 
We could observe that majority of male customers are active compare to female but compare to male majority of female customers have exited.

**Q.3) What percentage of customers hold credit card?**

Ans.

![ans3](https://user-images.githubusercontent.com/87359806/170264198-7eac0954-b59f-4784-a016-bcb00339cba8.PNG)

There are total 70.6% customers are there who hold credit card. 

**Q.4) How many customers are there for bank where branch location is france and also give the total percentage of active customers as well as total percentage of customers holding credit card?**

Ans.

![ans4](https://user-images.githubusercontent.com/87359806/170264259-b70418a2-070d-440d-9638-91e2e7449f5c.PNG)

In the above dashboard we could simply select france from the location filter then we can observe that the total number of customers are 5,014 where 51.7% are active customers where 70.7% of customers hold the credit card.

**Q.5) For branch of germany how many customers are there and what is the percent of active customers?** 

Ans.

![ans5](https://user-images.githubusercontent.com/87359806/170264321-40f8bd38-b4a8-4654-a1d8-f5d4b234f157.PNG)

In the above dashboard we could simply select Germany from the location filter then we can observe that the total number of customers are 2,509 where 49.7% are active customers.

**Q.6) How many customers are there for bank where location is spain how many customers are there and what is the active percentage of customers?**

Ans.

![ans6](https://user-images.githubusercontent.com/87359806/170277653-68a729e5-e6a3-464a-9ab2-23af14e3d0fd.PNG)

In the above dashboard we could simply select Spain from the location filter then we can observe that the total number of customers are 2,477 where 53.0% are active customers.

**Q.7) Among France , Germany & Spain which location has maximum active customers?**

Ans.

![ans7](https://user-images.githubusercontent.com/87359806/170277731-f20819cb-e00d-4dfb-bf96-baeeda2d5720.PNG)

In the above dashboard we could simply select location from the location filter one by one to observe the number of active customers. For France we have total 2,591customers, for Germany we have 1,248 customers and for Spain we have 1,312 customers. Maximum active customers are recorded from France.

**Q.8) How many customers were having tenure of 10 years and out of which how many are the active customers?**

Ans.

![ans8](https://user-images.githubusercontent.com/87359806/170277792-27a812fd-e604-44c2-beb8-15c68b291710.PNG)

In the above dashboard we could simply select the tenure of 10 years from the number of years of tenure filter. We could now observe that there were total 490 customers who were having tenure of 10 years with the bank and out of which 249 customers are active.

**Q.9) Among male and female customers how many customers exited or left having tenure of less than or equal to 1 year?**

Ans.

![ans9](https://user-images.githubusercontent.com/87359806/170277846-c2838198-e797-4aa6-bbed-1fa013367398.PNG)

In the above dashboard we could simply select the values 0,1 from the number of years of tenure filter because we want to find out that how many customers exited the bank having tenure less than 1 or between 1 and 0 that is less than 1 year. Then we would simply filter gender by selecting on the donut chart first we filter for male then for female to observe the values. We could now observe that there were total 142 male customers who exited and total 185 female customers who exited. So compare to male customers female customers have high churn rate when we compare for tenure of less than or equal to 1 year.

**Q.10) What is the age range in which female & male customers are most likely to churn?**

Ans.

![Ans10](https://user-images.githubusercontent.com/87359806/170277981-81637923-1d0a-470f-9e0b-d8b3637e51d7.PNG)

When we talk about age range for male & female so we could basically observe the color shades darker the color more number of customers exited from that age range so when we hover over the darker bar for female customers we could observe that from age range 45 to 50 maximum female customers are about to churn. And when we talk about male customer age range 40 to 45 is there where male customers are about to churn mostly. 

**Q.11) Among male and female compare the total estimated salary for customers percentage wise?**

Ans. 

![ans11](https://user-images.githubusercontent.com/87359806/170280203-33da12df-1985-4d4a-8431-13d5a0b46378.PNG)

From the above dashboard we could see that male customers have high total estimated salary having 54.34% whereas female customers has lower estimated salary compare to male customers having salary percentage of 45.66%.

**Q.12) Among male and female customers which customers are more likely to churn?**

Ans. From the above analysis we found that exit percentage of male customer is 16.5% which is lower than exit percentage of female customer which is 25.1%. Also from the above analysis which we did we observed that female customers have high churn rate compare to male customers when we observed for the tenure of less than or equal to 1 year. Female customers have high churn rate in age range 45 to 50. Also estimated salary of female customers is lower than male customers and also  balance as well as credit score of female customers is lower so having lower balance in account as well as having lower estimated salary and lower credit score might be the reason why female customers have high churn rate. So from the above observations we conclude that female customers are more likely to churn compare to male customers. 

# **Tableau dashboard** 

![Bank_Customer_Churn_Analysis_dashboard](https://user-images.githubusercontent.com/87359806/170280594-efdc44b0-2ea9-48fd-885a-ec532f493248.PNG)


**Tableau link :** https://public.tableau.com/views/BankCustomerChurnAnalysis_16534002111480/BankCustomerChurnAnalysisdashboard?:language=en-US&:display_count=n&:origin=viz_share_link

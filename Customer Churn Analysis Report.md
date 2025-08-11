# **Customer Churn Analysis Report**



### **Overview of Dashboard -**

* This Power BI dashboard delivers a rich, interactive overview of customer behavior, churn trends, and service utilization across a base of 7,032 customers.
* It leverages clear KPI cards, intuitive donut and bar charts, and dynamic slicers to highlight key patterns, enabling users to easily explore customer segments, identify factors influencing churn, and uncover actionable insights for improving retention and service strategy.





### **Key Performance Indicators -**

##### | Metric                Value     Insight

| Total Customers                   7,032          Total customer base.

| Total Charges                     ₹16,056,128    Total cumulative billing from all customers.  Shows how much revenue is retained on average from each customer.

| Average Total Charges             ₹2,283.29      Indicates customer lifetime value.

| Average Tenure (months)           32.42          Customers typically stay for nearly 3 years.

| Average Monthly Charges           ₹64.80         Reflects pricing plans; moderate monthly billing per customer.





##### **Slicers -**

 - Churn (Yes/No)

 - Partner (Yes/No)

 - Gender (Male/Female)





#### **Contract Type Distribution -**

\- Month-to-Month: 3,880 customers (55.11%)

\- One Year: 1,470 customers (20.93%)

\- Two Year: 1,682 customers (23.96%)



-- High reliance on month-to-month plans suggests volatility; customers on longer contracts exhibit greater stability.

-- Month-to-month customers dominate and typically have higher churn risk due to flexible exit terms.







##### **Technical Support Adoption -**

\- No Support: 3,472 customers (49.37%)

\- Support Subscribed: 2,039 customers (29.01%)

\- No Internet Service: 1,521 customers (21.62%)



-- Nearly half of customers lack tech support, indicating an opportunity to upsell support packages as a retention lever.

-- Many customers lack tech support, which could contribute to dissatisfaction and potential churn.







##### **Churn by Online Backup \& Dependents -**

 Online Backup Status          | Dependents |    Churned Customers |

 No                                 No                 1,036

 No                                 Yes                 197

 Yes                                No                  422

 Yes                                Yes                 101

 No Internet Service                No                  85

 No Internet Service                Yes                 28



-- Customers without an online backup and no dependents churn at the highest rate (1,036), signaling that data-protection offerings could improve stickiness, especially among solo  households.

-- Most churners don’t use Online Backup and don’t have dependents.

-- Customers with dependents and backups churn less.

-- Family-based or engaged customers with backups have lower churn.







#### **Streaming TV and Streaming Movies -**

**Streaming Services Usage -**

\- Streaming TV

\- Subscribed: 1,918 customers

\- Not Subscribed: 2,003 customers

\- No Internet Service: 1,521 customers



**Streaming Movies -**

\- Subscribed: 809 customers

\- Not Subscribed: 2,010 customers

\- No Internet Service: 1,521 customers



-- Streaming TV adoption (27%) outpaces streaming movies (11%), suggesting bundled streaming bundles could be optimized for cross-sell.

-- Customers using both streaming services are less likely to churn.

-- Those with no internet service show up significantly (1.5K).

-- Offering bundled digital services (TV/movies) may improve retention.







#### **Payment Method Breakdown -**

 **Payment Method**              **Customers**

 Electronic Check             2,408

 Mailed Check                 1,639

 Bank Transfer (Auto)         1,486

 Credit Card (Auto)           1,499



-- Electronic checks represent the largest cohort (34%), but they often correlate with higher churn—automated payments tend to lock in customers more effectively.

-- Electronic Check: 2.4K users – highest number.

-- Others like Mailed Check, Bank Transfer, Credit Card are nearly even (~1.5–1.6K).

-- Customers using electronic check appear most common — could be a churn risk group based on known patterns in churn modeling.





#### **Churn, Partner \& Gender Interplay -**

The view of churn status, partner presence, and gender reveals:

\- Customers without partners exhibit higher churn rates regardless of gender.

\- Female customers without partners churn slightly more than their male counterparts.

This insight underscores the value of personalized retention offers, particularly for single subscribers.





#### **Summary Insights-**

**Area**	                **Insight**

High Churn Groups	Month-to-month contract holders, no tech support, no backup users

Loyal Customers	        Two-year contracts, streaming users, those with dependents

At-Risk Payment Type	Electronic check users could be examined for early warning signals

Retention Factor	Bundled services and dependents seem to improve customer retention

Key Metric	        Average tenure: 32+ months – this can serve as a benchmark





##### **Recommendations -**

\- Encourage one- and two-year contracts through discounts or added benefits to reduce month-to-month churn.

\- Promote tech support subscriptions, highlighting faster issue resolution and premium service guarantees.

\- Bundle online backup with higher-risk segments (customers without dependents) to address data-protection anxieties.

\- Shift customers from electronic to automated payment methods by offering bill-pay incentives.

\- Develop tailored retention campaigns for single, no-partner customers, possibly offering community or loyalty programs.

-Target churn-prone customers (month-to-month, no dependents) with promotional offers or bundled services.

-Promote tech support and online backup to increase service attachment and reduce churn.

-Analyze churn further based on payment behavior to identify risk signals.

-- Through these targeted strategies, the organization can strengthen customer loyalty, optimize revenue streams, and meaningfully reduce churn across its service portfolio.







### **Second Page**

**Executive Summary -**

-This dashboard captures key churn metrics and customer behaviors for a telecom provider. Out of 7,032 customers, 1,869 have churned, representing a 27% attrition rate. Churned revenue stands at ₹3M, versus ₹13M retained.

-By dissecting tenure dynamics, service usage, payment methods, and contract types, we uncover actionable levers to curb churn and enhance lifetime value.





##### **Dashboard Metrics -**

**Metric**	                **Value**	                  **Insight**

Total Customers	        7032	       Entire customer base analyzed

Churned Customers	1869	       About 26.6% of customers have churned

Churn Rate	        0.27	       Indicates ~27% of total customers have churned

Churn Revenue	        ₹3M	       Revenue lost from churned customers

Retention Revenue	₹13M 	       Revenue retained from non-churned customers

Retention Rate	        0.73	       73% of customers have been retained





#### **Slicers -**

**Senior Citizen (Yes/No)**

-Contract Type (Month-to-month, One year, Two year)

-Internet Service (DSL, Fiber optic, None)

-Enables dynamic churn analysis based on demographics and services.





#### **Churn by Tenure -**

-0 months: 613 customers churned immediately after signup. Churn is highest at the beginning of customer tenure (peak at 1 month: 613 churns).

-80 months: 362 customers churned at the 6½-year mark.

-Two distinct churn “cliffs” appear at onboarding and at long-term milestones

-Another small spike at month 72+, possibly due to contract renewal time.

-Churn significantly drops after the first year, indicating risk is highest early in the lifecycle.



**-Suggestion:** bolster onboarding support and introduce loyalty rewards around months 78–80.

**-Insight:** The first few months are critical for retention. Implement welcome offers, early support, and onboarding campaigns.







##### **Churned Customers by Internet Service -**

**Internet Type	    Churned Customers**

Fiber Optic	      1,297 (Highest)

DSL	                459

No Internet	        113



**Insights -** 

-Fiber-optic customers churn nearly three times more than DSL subscribers. Investigate service quality or package value for fiber users

-Fiber optic users churn more, possibly due to higher expectations or competition. Evaluate service reliability and pricing.







##### **Customers by Payment Method and Churn -**

**Payment Method**	     **No Churn**	 **Churn**	  **Churn Rate**

Electronic Check	1,294	 1,071	      0.45

Mailed Check	        1,296	  308         0.19

Bank Transfer (Auto)	1,284	  258         0.17

Credit Card (Auto)	1,289	  232	      0.15 



**Insight:** - Electronic Check users have the highest churn rate.

&nbsp;        - Target these customers with loyalty programs or incentives to switch to auto-payment.





##### **Device Protection -**

**Device Protection Status**     **Count**	**% Share**

Yes	                     2,420	 34.39%                        

No	                     3,090	   44%                       

No Internet	             1,520	 21.62%



**Insight:-** Customers without device protection are more likely to churn. Offering bundled protection plans may reduce churn.

&nbsp;       - Over one-fifth of subscribers decline protection. Target upsell campaigns highlighting peace of mind and cost savings on repairs.







##### **Dependents \& Churn Rate by Payment Method** - 

| **Payment Method**       | **Dependents | Churn Rate** | 

| Electronic Check     |   2,408    |    45%     | 

| Mailed Check         |   1,639    |    19%     | 

| Bank Transfer (Auto) |   1,486    |    17%     | 

| Credit Card (Auto)   |   1,499    |    15%     | 





**Insights:** - Dependent customers paying by electronic check churn at alarmingly high rates. Family-focused incentives or bundle discounts could curb this risk.

&nbsp;         - Customers with dependents tend to churn less.

&nbsp;         - Electronic check users (often single or younger) show higher churn.

&nbsp;         - Family-oriented customers are more loyal. Segment marketing by demographic to increase effectiveness.  







##### **Contract Type \& Churn Patterns -** 

| **Contract Type    | Total Customers | Retained | Churned | Churn Rate** | **Insight**

| Month-to-Month   |      3,880      |  2,200   |  1,680  |   43.3%    | Highest churn — easy exit terms

| One Year         |      1,470      |  1,300   |    170  |   11.6%    | Moderate churn

| Two Year         |      1,682      |  1,680   |      2  |    0.1%    | Almost no churn — high loyalty



**Insight:-** Long-term contracts drastically reduce churn. Consider incentivizing customers to switch to plans of 1–2 years.

&nbsp;       - Longer-term contracts drive loyalty. Promote one- and two-year plans through tiered benefits and discounts









##### **Key Takeaways for Action -**

**Focus Area**	          **Recommendation**

Customer Onboarding	- Focus retention efforts on the first 3 months — loyalty discounts, surveys

Contract Strategy	- Incentivize upgrades to long-term plans

Payment Behavior	- Identify at-risk groups using electronic checks and offer auto-pay benefits

Tech Services	        - Investigate churn causes among fiber optic users

Demographic Targeting	- Promote bundled services and protection plans for customers without dependents





##### **Recommendations -**

\- Strengthen onboarding programs to reduce first-month churn

\- Introduce mid-term loyalty rewards near the 78–80-month milestone

\- Audit fiber-optic service quality and pricing to improve retention

\- Offer incentives for customers to switch to automated payments

\- Upsell device protection with bundled maintenance packages

\- Develop family-centric offers for dependent-heavy segments using electronic checks

\- Design contract-upgrade campaigns to migrate month-to-month customers to annual plans

By prioritizing these interventions, the organization can reduce attrition, increase recurring revenue, and deliver a more stable and satisfied customer base.







&nbsp;     


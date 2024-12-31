
# Credit Card Dashboard

## Problem Statement

This dashboard provides comprehensive insights into customer credit card behaviors, transaction trends, and outstanding balances. It helps financial institutions identify high-risk customers, understand usage patterns, and evaluate payment performance. These insights are crucial for improving service offerings, reducing delinquency rates, and optimizing credit card portfolios.
The analysis highlights customer spending categories, payment delays, and segments based on transaction trends. With actionable insights, banks can enhance customer satisfaction and streamline financial strategies.


### Steps followed 

•	Step 1: Imported the dataset into Power BI Desktop in .csv format.

•	Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

•	 Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

•	 Step 4 : It was observed that in none of the columns errors & empty values were present

•	Step 5:Handled null values in columns to ensure accuracy.

•	Step 6: Created calculated columns and measures using DAX for metrics such as average utilization ratio, total transactions, and delinquent account percentage.

•	Step 7: Designed a two-page interactive dashboard with slicers for filtering data by customer demographics and transaction categories.

•	Step 8: Added visuals including bar charts, pie charts, and KPI cards for total outstanding balance, monthly spending, and overdue percentage.

        


### Insights  

#### [1] Revenue Generated by Customers  
The total revenue generated by customers amounts to $56.5M. Male customers contribute a higher portion of the revenue at $30.9M, while female customers generate $25.6M. This indicates that male customers might have higher transaction volumes or higher spending tendencies compared to females.  

#### [2] Revenue by Age Group  
The age group 40-50 years generates the highest revenue, contributing $14M, showcasing this group as the most financially active segment. In contrast, the age group 20-30 years has the lowest contribution, generating only $1M. This could be due to limited financial independence or lower spending power among younger customers.  

![age](https://github.com/user-attachments/assets/73c5b7ac-d40a-43c7-a942-bb790cfbdfd9)



#### [3] Revenue by Quarter  
Revenue is fairly consistent across the quarters, with a slight upward trend in the last quarter of the year.  
- **Q1:** $14M  
- **Q2:** $13.8M  
- **Q3:** $14.2M  
- **Q4:** $14.5M  
The highest revenue of $14.5M in Q4 may be attributed to year-end spending, including festive seasons and holiday-related purchases.  

![Quater](https://github.com/user-attachments/assets/46b29cdc-b928-45da-b23e-be46889c6750)

#### [4] Revenue by Customer Job  
Among various professions, businessmen lead in revenue contribution, generating $17.7M, followed by white-collar employees with $10.3M.  
- **Businessman:** $17.7M  
- **White Collar:** $10.3M  
- **Self-Employed:** $8.5M  
- **Government Employees:** $8.3M  
- **Blue Collar:** $7M  
- **Retirees:** $4.6M  
This breakdown highlights that entrepreneurs and professionals are significant contributors, likely due to higher disposable incomes or frequent credit usage.  

![job](https://github.com/user-attachments/assets/35639c08-5e09-48a8-a9b5-a12e6d341fd7)


#### [5] Revenue by Card Category  
The Blue Card category is the most popular, generating $47M, which is significantly higher than other card categories.  
- **Blue:** $47M  
- **Silver:** $5M  
- **Gold:** $3M  
- **Platinum:** $1M  
The dominance of Blue Cards suggests its affordability and appeal to a broader customer base, while premium categories like Platinum and Gold have niche appeal with lower revenue contributions.  

![card ](https://github.com/user-attachments/assets/5c6e9376-4d53-41b1-ac94-9578189c4282)

### Conclusion  

The analysis of the credit card customer data provides valuable insights into revenue generation patterns and customer behaviors. The dashboard effectively identifies high-value customer segments, spending trends, and areas for targeted financial strategies.  

Key observations highlight the significant revenue contributions from male customers and the 40-50 age group, suggesting this demographic as a critical focus for marketing efforts. Quarter 4 consistently outperforms other quarters, emphasizing the importance of seasonal campaigns to capitalize on increased spending during year-end holidays.  

From a professional standpoint, businessmen and white-collar employees dominate revenue contributions, indicating a strong reliance on credit card usage in these segments. The analysis of card categories underscores the widespread appeal of the Blue Card, suggesting its role as the primary driver of revenue and customer engagement.  

These insights empower financial institutions to refine their service offerings, optimize card portfolios, and design targeted campaigns that address the needs of high-value customer groups while improving overall customer satisfaction and loyalty. By leveraging the trends and patterns identified, banks can minimize credit risks, boost revenue, and ensure a more streamlined approach to portfolio management.  


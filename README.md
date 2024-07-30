# Task
- Develop a CRM Sales Analysis Dashboard
- Users: Sales Managers
- Tools: Excel, Power BI

# Data
Owner :	Sales representative to whom the lead is assigned / owns the lead <br />
Lead acquisition date :	Date when the lead was entered into the CRM system for the first time <br />
Product :	Product that the organization is interested in <br />
Status :	Status of the lead. Each lead can be assigned statuses as follows: <br />
1. New - just added
2. Qualified - marketing has qualified the lead as valid
3. Sales Accepted - sales has accepted the qualified lead as valid.
4. Opportunity- sales is working with the lead
5. Customer - lead is converted to a customer
6. Churned Customer - customer has stopped using the product
7. Disqualified - marketing or sales has disqualified the lead as invalid (can happen at any stage).

Status sequence :	Column indicating the sequence of a step in the lead conversion process <br />
Stage :	Stage of the lead who is in the opportunity phase . Stage can be assigned as follows: <br />
1. Opened - sales is working on establishing the initial communication
2. Initial contact - initial communication is established
3. Nurturing - ongoing communication with the organization about the offer
4. Proposal sent - a proposal is sent to the organization
5. Won - organization has accepted the offer
6. Lost - organization won't become a customer

# Method
- Load data from Excel to Power BI
- Build a star model in Power BI
- Create new metrics to evaluate sales performance and the health of sales pipeline

# Result
![image](https://github.com/user-attachments/assets/73c01fcf-6950-4e4e-8104-e7c813e41456) <br/>
![image](https://github.com/user-attachments/assets/fdc90415-4d88-4aeb-8f4a-4aaff6027d04)  <br/>
![image](https://github.com/user-attachments/assets/cdc8f98c-4006-47b6-92c0-c958e93359ea)  <br/>

# Insights and Recommendations
> [!IMPORTANT]
> Key information users need to know

**Sales Performance** :
The total deal value drops significantly after excluding churned customers, suggesting that nearly half of the deal were associated with clients who eventually churned.
- Country :
Italy, Netherlands, Portugal and Spain have high conversion rate (Opportunities to Customers). Belgium, Germany and Switzerland achieved lower conversion rate but high average deal value
Austria and France performed low conversion rate and low average deal value
- Product: 
SAAS and Services are the dominant sources of income.
- Organization size: 
More than 50% of deal value comes from Medium companies. Other enterprises, each contributes to approximately 10% 
- Industry
Transportation, Banking and Government have the highest impact to the total deal value

The average deal value and number of closed deals fluctuate significantly from month to month. May and June both show high average deal value and high number of closed deals.

**Sales pipeline** :

Overall, sales pipeline shows good conversion rate between stages, except: Opportunity to Customer: There is only 348 leads transfer from Opportunity to Customer stage (CVR = 28.6%), suggesting room for improvements.
Customer to Churned Customer: High churn rate indicates potential issues with customer satisfaction, product fit or ongoing support.
Action: Regularly engage with customers through follow-ups and satisfaction surveys to identify and address issues 

- Detailed Opportunity Stage:
Opened to Initial Contact: Only a third of opened opportunities move to initial contact. 
Action: Deploy automated outreach tools to ensure timely follow-ups with all new opportunities.
Proposal sent to Won: Although more than half of proposal sent converts to win, there is still room for optimization.
Action: Analyze lost proposal to identify common objections and refine proposal strategies accordingly.

- Sales Agent:
Laura Thomson is the best sales agent with highest deal value and average churn rate. 
David Wilson has short sales cycle but low won rate and low deal value. Need to improve conversion techniques and increase  deal size by targeting higher value leads.
Emily Johnson achieved high won rate but high churn rate, suggesting potential issues in customer satisfaction. Focus to post-sales support to reduce churn.
Jessica Martinez has high deal value and good won rate but longer sales cycle. Streamline the sales process to shorten the sales cycle.







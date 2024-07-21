# Fixed Deposit Targeted Marketing Strategies: Insights from BCN Bank's Campaign Analysis

## Introduction
In a competitive banking environment, understanding customer behaviour and preferences is crucial for the successful launch of new financial products. BCN Bank Ltd recently introduced a new fixed deposit scheme aimed at attracting a diverse customer base. To ensure the success of this product, the bank initiated a comprehensive phone call campaign targeting over 45,000 customers. The primary goal of this campaign was to segment customers and identify those most likely to opt for the fixed deposit, thereby enabling the bank to tailor its marketing strategies effectively.

Through meticulous data analysis, this project seeks to uncover patterns and factors that influence customer decisions. By examining various demographic and financial attributes, we aim to provide actionable insights that will help BCN Bank optimize its marketing efforts, enhance customer targeting, and ultimately increase the adoption rate of the new fixed deposit scheme. This analysis will not only highlight the characteristics of potential fixed deposit buyers but also guide the bank in developing more personalized and impactful marketing campaigns.

## Objectives
The objectives of this project are:
- To analyze the campaign data and determine the percentage of customers who opted for the fixed deposit.
- To identify key factors influencing customers' decisions to buy fixed deposits.
- To segment customers based on age, education, marital status, account balance, and loan status.
- To develop a scoring system to rank customers based on their likelihood of buying a fixed deposit.

## Observations
### Story of Findings
BCN Bank Ltd recently conducted a comprehensive phone call campaign to promote its new fixed deposit scheme. The results from this campaign revealed that out of 45,211 customers contacted, 5,289 opted for the fixed deposit, accounting for 12% of the total. Conversely, 39,922 (88%) customers did not opt for the scheme, as shown in Figure 1.

#### Sampling Insights
Upon analyzing samples of the dataset, it was observed that, on average, 12 out of every 100 customers chose to buy the fixed deposit, with a minimum of 1 customer per 100 making the decision. This low conversion rate highlights the need for targeted marketing strategies to maximize resource efficiency and reach the right audience.

#### Age Influence
Figures 2 and 3 illustrate the relationship between age and the decision to buy a fixed deposit. Initially, the data appeared cluttered, prompting the grouping of ages into brackets for clearer segmentation. This revealed promising potential among customers aged 18-25 and those over 50. Figure 4 further refined this observation, indicating a higher conversion likelihood among customers aged 18-30 and those aged 54 and above.

#### Education's Impact
The analysis suggested that education significantly influences a customer's decision to purchase a fixed deposit. It is assumed that higher education levels instil better financial planning skills. The campaign predominantly featured customers whose highest education level was secondary school. By excluding data labelled 'unknown' to avoid ambiguity, Figure 6 demonstrated that education indeed impacts the decision to buy fixed deposits. Figure 7 confirmed this hypothesis, showing that tertiary-educated individuals are more likely to opt for fixed deposits. Hence, targeting these individuals would be a strategic move for the bank.

#### Marital Status
It was hypothesized that married individuals might be more inclined to invest in fixed deposits due to joint financial planning. Initial observations showed a higher number of married individuals in the campaign, but due to the population imbalance, this required careful consideration. Testing the hypothesis, Figure 9 indicated that marital status might not significantly influence the decision. Figure 10 revealed that single individuals are more likely to buy fixed deposits than divorced and married individuals.

#### Account Balance
The hypothesis that a higher account balance correlates with a higher likelihood of purchasing fixed deposits was supported by Figure 11. Customers with more money in the bank tend to invest more in fixed deposits.

#### Customer Status
Marketing strategies often suggest that it is easier to sell to existing customers compared to new ones. Figure 12 validated this by showing that existing customers were more inclined to buy fixed deposits than new customers.

#### Loan Influences
Figures 13 and subsequent analyses explored the impact of different types of loans on the decision to purchase fixed deposits. Customers without housing loans were more likely to buy fixed deposits (17%) compared to those with housing loans (8%). Similarly, those without personal loans were more likely to invest in fixed deposits. Defaulting on loans also influenced the decision negatively, as shown by the lower percentage of loan defaulters opting for fixed deposits.

#### Point System
To further refine customer targeting, a point system was developed to grade customers based on various factors. The system revealed that higher points correlated with a higher likelihood of purchasing fixed deposits, as illustrated in Figure 16. Incorporating customer status (old/new) into this point system enhanced its predictive accuracy, as shown in Figure 17.

### Conclusion
The analysis highlights critical factors influencing the decision to buy fixed deposits, including age, education, account balance, and customer status. By leveraging these insights, BCN Bank can optimize its marketing strategies to target the most promising customer segments, thereby increasing the adoption rate of its new fixed deposit scheme.

## Repository Structure
```plaintext
|-- README.md
|-- data/
|   |-- bank_campaign_data.csv
|   |-- ml_bank_campaign_data.csv
|-- notebooks/
|   |-- EDA - Fixed Deposit Targeted Marketing.ipynb
|-- results/
|   |-- Figure 1.png
|   |-- Figure 2.png
|   |-- ...
|-- Fixed Deposit Targeted Marketing Strategies- Insights from BCN Bank's Campaign Analysis.pdf

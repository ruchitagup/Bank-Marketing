# Bank-Marketing
A Portuguese bank had conducted a telemarketing campaign for a term deposit product somewhere around late 2010. 
Through the campaign, the bank had collected data about the prospects' demographics, other financial products they have purchased in the past (loans, deposits, etc.), the number of times they were called, etc. They also recorded the response data, i.e., whether the person had subscribed to the term deposit product, which is the target variable.  
The bank's marketing team wants to launch yet another telemarketing campaign for the same product.

Business Objective: 
- To reduce customer acquisition cost by targeting the ones who are likely to buy
- To improve the response rate, i.e., the fraction of prospects who respond to the campaign
- To achieving 80% of total responders at the minimum possible cost. 

Goal of Data analysis: 
- To build a logistic regression model using the 2017 data to assign a score between 0 and 1 to each of the prospects and it should be evaluated on the metric chosen in tune with the Business Objective.
- Divide the prospects into 10 equal bins on the basis of this score. Then find the Top X% of the responders who should be contacted to meet the Business Objective.
To find the cost of Acquisition of 80% of the responders using the model.


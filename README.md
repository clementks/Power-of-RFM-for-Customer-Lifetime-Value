# Power-of-RFM-for-Customer-Lifetime-Value


   RFM is a dynamic customer scoring methodology for assigning each customer a value based on historical purchase data. When required to determine customer lifetime value, RFM enables firms or brands to understand customers’ activities at a more granular, segmented level. In turn, the messaging and promotions can be tailored to the determined value in the RFM scoring methodology. In practice, we can bucket the segments into a value spectrum profiles based on variations of customer personas: VIP, Regular, and New Customer, Lost Customer, Big Spender which usually have to be aligned with the marketing programme. The gradations of customer type allow me to personalize content and messaging by bucket in a way that more closely aligns with the customer’s behavior.


**Example of RFM Framwork for Customer Lifetime Value**
![image](https://user-images.githubusercontent.com/32416129/128384542-5aa8be15-f2a5-4503-9cfa-0f2c78808490.png)

  Customer lifetime value insights at this level make it exponentially easier to quickly spot positive or negative movement along the RFM spectrum to strengthen relationships and mitigate churn.

   With the RFM scoring which enhances visibility into customer's behavioral data, it can provide insights make actionable decision to segment the customer base and apply for different marketing programs for different groups or clusters.

   To achieve this RFM Scoring analysis without much investment in cost of software licensing, it can be realized using software applications such as Tableau Desktop or Python which can be complemented with Bokeh libraries to achieve the interactivity for data exploration to be on par with Tableau. Public Tableau domain is free.

**Below is an illustration how RFM Scoring can be achieved using Transactional DataSet of a Canadian MegaStore for demonstration. 

(Disclaimer: data values are not actual for confidentiality purpose)

# Dataset Attributes or Features
![image](https://user-images.githubusercontent.com/32416129/128457373-cc7482a0-4fea-414b-af59-5ee2340ebff1.png)

**1.1 Time series of the number of transactions (daily)**

- Time series of the number of transactions (daily) between the stipulated time-frame (ie: from 2009 to 2013)

![image](https://user-images.githubusercontent.com/32416129/128457527-19b408ea-18d9-4066-93d6-9b9dc5109207.png)

**1.2 Sales Transaction Volume of each province and region in Canada**
 
![image](https://user-images.githubusercontent.com/32416129/128458081-b6b7fff0-1bbf-49d7-a7cd-e2c7c8bdf655.png)


**1.3 Typical inter-purchase time and IPT distribution (in histogram) & details for each customer**

 - To aid any firm in understanding their customer's purchasing behaviour and profile, below are the few examples showing how Python programming can achieve presenting customer's Number of Purchase(s) between Periods and Distribution of Customer(s)'s Purchase in histogram which cannot be realized using Excel standard features. It can be achieved using Excel VBA macro or VB.Net. the recent improvement in Tableau integration with Tableau Prep and TabPy Server enables Python script to be embedded for customized analysis according to business requirement to leverage on Tableau interactivity features. 

![image](https://user-images.githubusercontent.com/32416129/128458796-4bb8cc91-b7a7-472c-aae2-e7ea2d905535.png)


Distribution of IPT (Inter-purchase Time) in histogram:

![image](https://user-images.githubusercontent.com/32416129/128458837-0c08f5b9-ed53-4b65-b965-48020a8444d3.png)
 

- Below is an illustration on distribution of the number of purchases per customer :


![image](https://user-images.githubusercontent.com/32416129/128458694-96dc6091-c0df-4756-b267-6101183ef3fb.png)


- Below is a histogram of the customer's visits/patronization frequency to store, using the python lifetimes package & libraries

![image](https://user-images.githubusercontent.com/32416129/129558777-f3063a8a-5421-41d1-8953-50c301deda86.png)

- Using the python lifetimes package - plot_frequency_recency_matrix library allows us to visualize the store frequency recency matrix of this megastore's business 




- Distribution Plot on Probability of Customer alive (ie:active) &  tabular form details of each customer.

From this frequency and recency plot, with the probability showing that significant number of customers for this store has small distribution to be alive (ie: active)

![image](https://user-images.githubusercontent.com/32416129/129593831-8bcabf11-a97a-4f7b-ba03-8b5122f1b61a.png)




- Below is an illustration of me utilizing Tableau for RFM Analysis, with customer scoring assigned for each customer based on their historical purchase data

https://public.tableau.com/authoring/Sales_Trend_16277222014070/RFMScoring_1/RFM%20Dashboard#1



![image](https://user-images.githubusercontent.com/32416129/128471821-9373075c-246e-4c55-bf7e-1bee9619b9b1.png)


![image](https://user-images.githubusercontent.com/32416129/128516337-ee5ea802-2269-43be-a4ed-7b37bd83124e.png)

![image](https://user-images.githubusercontent.com/32416129/128520126-9a010416-dffd-45a8-96a2-13e0a88c52ee.png)

- Profiling customer(s) into the various personas group which has to be aligned with their CRM (Customer Relationship Management) strategy to tailor marketing messaging and promotions, marketing campaign or promotions for the respective customer personas: VIP, Regular, and New Customer. The gradations of customer type enables any firm to personalize content and messaging in a way that to strengthen & boost customer’s purchasing engagement as part of their CRM (Customer Relationship Management) strategy.


![image](https://user-images.githubusercontent.com/32416129/128520048-ae432499-d8b8-4fec-b04f-1b444fcd858c.png)

- After classifying or assigning all the customers into segments with their RFM profiles as shown above, we can then aggregate the population size of each RFM profile segment which i have tabulated using a simple bar chart. Another form of visualization is done using Treemap to illustrate the different RFM segments expressed in percentage (%).



 
![image](https://user-images.githubusercontent.com/32416129/128456781-cffd78ea-1064-4e3a-b956-de3816759bbf.png)

 ![image](https://user-images.githubusercontent.com/32416129/128523596-2d4d2ed4-2061-4e31-afa1-cc6b0974fed3.png)

- To ensure achieving success in reducing customer churn or rate of attrition, LIFT analysis can be used to measure the impact of any firm's marketing or promotional campaigns so that they can continue to make variation marketing strategies to improve their customer's engagement as part of their CRM programme. Market Basket Analysis is also an avenue to identify what assortment of products most frequently occur together in orders.  Using this relationship to increase profitability through cross-selling, recommendations, promotions, or even the placement of items on a menu or in a store to increase customer retention.


**1.4 Association Mining as part of Market Basket Analysis**

 - Association mining using FPGrowth algorithm or Apriori algorithm

![image](https://user-images.githubusercontent.com/32416129/128534207-4fd83c52-5445-434b-90b0-3cbfcedce402.png)


 One of most common approach to find patterns other than clustering is Market Basket Analysis, which is a key technique used by large retailers like Amazon, Flipkart, etc to analyze customer buying habits by finding associations between the different items that customers place in their “shopping baskets”. The discovery of these associations can help virtually any firms with diverse assortment of products to develop marketing strategies is by gaining insight into which items are frequently purchased together by customers. The strategies may include:

- Changing the store layout on assortment according to customer's pyschological shopping behaviour that appeals and attracts their attention
- Customer behavior analysis
- Cross marketing or Cross-selling as part of the recommender system
- Purchase with purchase (PWP) promotional campaign

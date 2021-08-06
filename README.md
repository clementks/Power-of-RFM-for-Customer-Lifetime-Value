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

![image](https://user-images.githubusercontent.com/32416129/128457527-19b408ea-18d9-4066-93d6-9b9dc5109207.png)

**1.2 Sales Transaction Volume of each province and region in Canada**
 
![image](https://user-images.githubusercontent.com/32416129/128458081-b6b7fff0-1bbf-49d7-a7cd-e2c7c8bdf655.png)


**1.3 Typical inter-purchase time and IPT distribution (in histogram) & details for each customer**

 - To aid any firm in understanding their customer's purchasing behaviour and profile, below are the few examples showing how Python programming can achieve presenting customer's Number of Purchase(s) between Periods and Distribution of Customer(s)'s Purchase in histogram which cannot be realized using Excel standard features. It can be achieved using Excel VBA macro or VB.Net.

![image](https://user-images.githubusercontent.com/32416129/128458796-4bb8cc91-b7a7-472c-aae2-e7ea2d905535.png)



![image](https://user-images.githubusercontent.com/32416129/128458837-0c08f5b9-ed53-4b65-b965-48020a8444d3.png)

- the recent improvement in Tableau integration with Tableau Prep and TabPy Server enables Python script to be embedded for customized analysis according to business requirement to leverage on Tableau interactivity features. 


![image](https://user-images.githubusercontent.com/32416129/128458694-96dc6091-c0df-4756-b267-6101183ef3fb.png)


- Below is an illustration of me utilizing Tableau for RFM Analysis, with customer scoring assigned for each customer based on their historical purchase data

https://public.tableau.com/authoring/Sales_Trend_16277222014070/RFMScoring_1#1

![image](https://user-images.githubusercontent.com/32416129/128456781-cffd78ea-1064-4e3a-b956-de3816759bbf.png)

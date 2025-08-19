# __Capstone: Marketing_And_Retail_Analytics__

## __Background and Problem Statement:__
OList, an e-commerce company has faced some losses recently and they want to reduce any unnecessary inventory costs.

To manage the inventory cost of the company OList, it is required to identify top products contributing to the revenue, identify items that are more likely to be purchased individually or in combination with some other products, identify the product categories which they can get rid of without significantly impacting business.

### In this capstone,
Only the cases having order status as '_delivered_' are considered.
EDA is performed to treat outliers and missing values carefully before making any inferences from the dataset.


## **Entity Relationship Diagram (ERD)**
<img width="590" height="889" alt="image" src="https://github.com/user-attachments/assets/19305084-64fb-41fd-9119-0b8e1848b3b2" />


## **Retail Dataset**
https://github.com/MalhotraUmang/Capstone_Marketing_And_Retail_Analytics/blob/main/Retail_dataset.xlsx
There are 5 tables in the dataset:
1. orders: The central table with unique order IDs, unique customer IDs, order status and information on purchase and delivery timestamps.
2. order_items: Connected with orders table based on order ID, containing unique product IDs, seller IDs, product prices, shipping charges etc.
3. products: Connected with order_items table based on product ID, containing product category and fields explaining product dimensions and weight.
4. customers: Connected with orders table based on customer ID, having information on customers address parameters suich as zip code, city and state.
5. payments: Connected with orders table based on order ID, with information on payment mode type and number of installments etc.


## **Project pipeline:**
1. *Data exploration and cleaning*: Identification and appropriate treatment of any missing/duplicate values, outliers and inconsistencies in various features.
2. *Data visualisation*: Appropriate visualisations to identify the most ordered products by quantity and revenue.
3. *Market basket analysis*: Identification and visualization of product category combinations ordered frequently.
4. *Dashboarding and Final PPT*: Dashboard with the important visualisations and an executive summary containing valuable insights and recommended steps of action.


## __Items for Submissions:__
1. A _cleaned_ retail _dataset_ (.xlsx).
2. A _dashboard file_ with all important visualisations (.twb).
3. A _PPT_ file with an executive summary for insights and recommendations for business (.ppt).
4. A _video_ explaining the presentation (.mp4).








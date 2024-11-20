## MONGODB-DASHBOARD

#### INTRODUCTION

The telecom customer churn dataset used in this project includes comprehensive information on 7,043 customers from a California-based telecom company in Q2 2022. It is specifically structured to analyse customer attrition (churn) and containing key metrics like customer tenure, monthly charges, total revenue, and churn status, along with demographic insights like location (city, geo points), gender, age, and subscribed offers.
By identifying key drivers contributing to churn, such as service dissatisfaction, competition, pricing sensitivity, and customer behaviour, this analysis aims to provide actionable recommendations to reduce attrition, enhance customer retention, and improve overall service quality, ultimately supporting targeted retention strategies.

<br>

#### <code style="color : blue"> "Every churned customer tells a story, Listening to it is the first step to growth." </code>


<br>

![image](https://github.com/user-attachments/assets/7d19fe5c-e923-4f12-8506-3f86c653b055)

<br>

#### DATASET : TELECOM CUSTOMERS CHURN 

<a href="https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics">Dataset Link</a>

![image](https://github.com/user-attachments/assets/eb382ba0-9d45-4a6f-b991-a90c229046bc)


Number of rows: <b>7043</b><br>
Number of columns: <b>38</b>
<br>
<br>

#### VARIABLE DESCRIPTION


- **Customer ID:** A unique ID that identifies each customer.
- **Gender:** The customer's gender: Male, Female
- **Age:** The customer's current age, in years, at the time the fiscal quarter ended (Q2 2022)
- **City:** The city of the customer's primary residence in California
- **Latitude:** The latitude of the customer's primary residence
- **Longitude:** The longitude of the customer's primary residence
- **Number of Referrals:** Indicates the number of times the customer has referred a friend or family member to this company to date
- **Tenure in Months:** Indicates the total amount of months that the customer has been with the company by the end of the quarter specified above
- **Offer:** Identifies the last marketing offer that the customer accepted: None, Offer A, Offer B, Offer C, Offer D, Offer E
- **Contract:** Indicates the customer's current contract type: Month-to-Month, One Year, Two Year
- **Monthly Charge:** Indicates the customer's current total monthly charge for all their services from the company
- **Total Revenue:** Indicates the company's total revenue from this customer, calculated to the end of the quarter specified above 
- **Customer Status:** Indicates the status of the customer at the end of the quarter: Churned, Stayed, or Joined
- **Churn Category:** A high-level category for the customer's reason for churning, which is asked when they leave the company: Attitude, Competitor, Dissatisfaction, Other, Price (directly related to Churn Reason)
- **Churn Reason:** A customer's specific reason for leaving the company, which is asked when they leave the company (directly related to Churn Category)

<Br>
<br>

### DASHBOARD

![image](https://github.com/user-attachments/assets/5c69759f-8d24-47eb-88c9-353553233f9e)

<br>
<br>

### CHARTS


1. What is the current churn rate?
   
    <ins>**Churn Rate Chart**</ins>

    **Description:** This chart provides a snapshot of the overall churn rate, showing the percentage of customers who have left the service relative to the total customer base.

    ![image](https://github.com/user-attachments/assets/801903a2-edaa-48bd-a651-ba79309951f0)



    ![image](https://github.com/user-attachments/assets/4932a235-9ee5-4f2e-91d8-5a48182537c0)


   <b>Insights:</b>  The churn rate of 26.5% indicates that over a quarter of the telecom company’s customer base has left the service. This high churn rate suggests underlying issues that may need addressing, such as customer satisfaction, competitive pricing, or service quality. Reducing churn should be a priority, as retaining customers is often more cost-effective than acquiring new ones.
<br>
<br>

2. Why are customers leaving the service?

   
    <ins> **a. Key Reasons for Customer Churn: Word Cloud** </ins>

   
    **Description:** This visualization highlights the most frequently cited reasons for churn, such as competitive pricing and services, network reliability, or customer service issues. Identifying the primary causes allows for targeted improvements to retain more customers.

    ![image](https://github.com/user-attachments/assets/16fb7169-9585-4c2d-abf0-a8d430100bd3)


    <b>Insights:</b> The word cloud reveals that competition, service quality, and customer support are major drivers of customer churn. Common reasons include competitors offering better devices and download speeds, as well as dissatisfaction with customer support and network reliability. Addressing these areas—especially by enhancing product offerings and improving support quality—could help reduce churn.
  
<br>
<br>

  <ins> **b. Churn Category Breakdown** </ins>

    
  **Description:** This grouped bar chart shows the distribution of churn reasons, helping to identify the primary factors driving customer attrition, such as competition, dissatisfaction, or pricing issues, to prioritize improvement efforts.

   ![image](https://github.com/user-attachments/assets/46f40a09-572e-441d-92c6-97a3ee258067)


   **Insights:**  Majority of customer churn is due to competition, with 841 customers leaving for competitor offerings. Other significant factors include general dissatisfaction, customer attitude, and pricing issues. Focusing on differentiating services and enhancing value could help retain customers and reduce competitive churn.
  
<br>
<br>

3. How does churn impact revenue over time?
   
   <ins> <B>Churned Revenue v/s Total Revenue</B> </ins>
    
   **Description:** This Gauge chart illustrates the financial impact of churn by comparing total cumulative revenue to revenue lost from churned customers. It helps quantify the revenue at risk due to attrition and emphasizes the importance of retention efforts.

   ![image](https://github.com/user-attachments/assets/9735aef6-953f-4ed4-ba6b-1f9d26b5f01b)


    **Insights:**   The churned revenue of 3,684K out of a total revenue of 21,371K highlights a substantial revenue loss due to customer churn, accounting for about 17% of the total revenue. This significant financial impact underscores the importance of implementing effective retention strategies to minimize revenue loss and stabilize overall financial performance. Retaining existing customers should be prioritized, as it directly correlates to maintaining the company’s revenue base.

<br>
<br>

4. Are certain demographics, locations, or service types associated with higher churn rates?
   
	  <ins> **a. Gender Breakdown of Churned Customers** </ins>
   
    **Description:** This grouped column chart displays the gender distribution among churned customers, offering insights into whether churn is disproportionately affecting one gender. Understanding the demographic profile of churned customers enables more personalized retention strategies. 

    ![image](https://github.com/user-attachments/assets/299cc9b9-6523-4690-8e99-f6242ae1503b)

   **Insights:** The gender breakdown of churned customers is nearly balanced, with 939 females and 930 males leaving the service. This indicates that churn is not heavily skewed towards one gender, suggesting that retention strategies may need to focus on factors beyond gender-specific preferences. Instead, understanding other behavioral or service-related factors influencing churn could be more effective in reducing overall attrition.
  
<br>
<br>

  <ins> **b. Revenue Distribution by Location** </ins>
    
  **Description:** This geographical heat map visualizes revenue concentration across different locations, helping identify regions that contribute the most to the company’s revenue and potentially guiding location-specific marketing and service expansion efforts.

   ![image](https://github.com/user-attachments/assets/96bf9f04-ecdb-4906-bd03-a85e3250d4a3)



  **Insights:** The revenue heat map reveals that the highest revenue concentrations are in Southern California, particularly around Los Angeles and San Diego, with additional moderate revenue from the San Francisco Bay Area. This distribution suggests that these regions are the strongest markets, and targeted retention and service expansion strategies in these areas could help maximize revenue retention and growth.

<br>
<br>

  <ins> **c. Distribution of Churned Customers by Availing Offers** </ins>

   **Description:** This Donut chart shows the distribution of churned customers based on the specific offers they were using at the time of churn, helping to identify which offers may be associated with higher churn rates and need improvement or reevaluation.

   ![image](https://github.com/user-attachments/assets/f53d68c3-320b-4e74-a3d5-1c753703b777)


   **Insights:** This chart highlights the distribution of churned customers across different offers. Offer E shows the highest churn rate, indicating it may not be meeting customer expectations or may lack competitive advantages. Offers with lower churn rates, like Offer A, could provide insights into features or benefits that appeal more strongly to customers.

<br>
<br>

5. What role does customer tenure play in churn? 

    <ins> **Customer Longevity and Monthly Charges** </ins>
    
    **Description:** This scatter plot aims to analyze the relationship between customer tenure and monthly charges in relation to churn behavior. By identifying tenure and pricing patterns linked to churn, this visualization helps in developing targeted retention strategies for high-risk customers and reinforcing loyalty among long-term users.

    ![image](https://github.com/user-attachments/assets/4464d2fc-14ec-4d43-ae89-962e27cf80ed)


   **Insights:** This scatter plot reveals that customers with shorter tenures (particularly under 20 months) and higher monthly charges are more prone to churn, highlighted by the higher density of red points in these areas. In contrast, customers with tenures exceeding 50 months are more likely to stay, regardless of their monthly charges, as indicated by the blue clusters. These insights suggest that implementing targeted retention strategies for new customers, especially those with high charges, and offering loyalty incentives for long-term customers could effectively reduce churn.

<br>
<br>

6. What customer profiles are associated with higher churn rates?

    <ins> **Age Distribution by Contract Length** </ins>
    
    **Description:** These heatmap shows the comparison between the age distribution for churned vs stayed customers’ preferences across different contract lengths, helping identify age groups with higher churn based on contract type. This information could assist in designing contract options that appeal to specific demographics.

    ![image](https://github.com/user-attachments/assets/4aa05681-1ab7-4fbc-88a1-6c485bef2927)


   **Insights:** The heatmaps reveal that churn is primarily associated with customers on month-to-month contracts, particularly in younger age groups (20-40). This suggests that younger customers may prefer flexibility but are more likely to leave when dissatisfied. In contrast, customers on longer-term contracts (one or two years) tend to have lower churn rates, especially among older age groups, indicating a preference for stability. These insights suggest an opportunity to tailor retention strategies by offering more flexible month-to-month benefits for younger customers while promoting the value of long-term contracts for older demographics.

<br>
<br>

7. Which cities have the highest number of churned customers?
   
    <ins>	**Top 10 Cities by Number of Churned Customers** </ins>
    
    **Description:** This column chart highlights the cities with the highest churn, helping to identify geographic areas where customer retention efforts may be most needed.

     ![image](https://github.com/user-attachments/assets/51815de7-ef15-43ea-a6a3-8739a888adc0)


     **Insights:** The chart shows that San Diego has the highest number of churned customers, followed by Los Angeles and San Francisco. This indicates that these cities might have specific factors, such as service issues or competitive alternatives, contributing to higher churn rates. Focusing retention efforts in these top cities by offering targeted promotions, improving service quality, or addressing local competitor challenges could help reduce churn and improve customer satisfaction in these areas.

<br>
<br>
<br>

### MANAGERIAL IMPLICATIONS

<br>

1. **Enhanced Value Proposition Against Competitors:**
  
   With competition identified as a major driver of churn, particularly due to better devices, download speeds, and pricing, the company should focus on differentiating its offerings. This can be achieved by:
    - Introducing competitive pricing models or bundled services.
    - Providing enhanced internet speeds and value-added services.
    - Offering device upgrade programs or exclusive perks.



2. **Targeted Retention Efforts for High-Risk Segments:**
  
   Analysis shows that customers with short tenures (under 20 months) and high monthly charges are at higher risk of churning. To address this:
    - Develop personalized retention campaigns, such as discounts or rewards for new customers nearing the 20-month mark.
    - Introduce flexible for month-to-month plans or service targeted at younger customers  with higher monthly charges.



3. **Improving Service Quality and Customer Support:**

   Dissatisfaction with service quality and support is a significant churn driver. Investments should be made in:
    - Strengthening network reliability in high-churn areas like San Diego and Los Angeles.
    - Expanding and training customer support teams to deliver quicker and more effective resolutions.



4. **Region-Focused Campaigns and Service Enhancements:**

   High churn cities like San Diego, Los Angeles, and San Francisco require dedicated strategies:
    - Conduct localized marketing campaigns promoting unique service offerings.
    - Address specific service issues in these areas, such as network upgrades or exclusive promotions.



5. **Optimizing Offers and Bundles:**

   With Offer E showing the highest churn rate, it’s essential to:
    - Reevaluate the features and pricing of Offer E to meet customer expectations better.
    - Identify the elements of successful offers, like Offer A, and replicate them across other plans.

6. **Loyalty Programs for Long-Term Customers:**

   Long-tenure customers (50+ months) show higher loyalty. To encourage retention:
    - Launch loyalty programs offering discounts, exclusive deals, or early access to new services for long-term customers.
    - Prioritize outreach to high-revenue customers showing early signs of churn (e.g., complaints or reduced usage).
    <br>
    <br>
#### CONCLUSION

The analysis highlights that customer churn in the telecom industry is driven by competition, dissatisfaction, pricing, and demographic-specific preferences. By implementing targeted retention strategies, such as improving service quality, offering personalized plans, focusing on high-churn regions, and enhancing customer support, the telecom company can reduce churn effectively. Retention efforts not only stabilize revenue but also enhance customer loyalty, paving the way for sustainable growth and a competitive edge in the market.
<br><br>

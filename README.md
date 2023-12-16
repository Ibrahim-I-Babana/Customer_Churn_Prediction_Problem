# Customer_Churn_Prediction_Problem
Every company wants to increase its profit or revenue margin and customer retention is one of the key area industry players focus their resources. In todays world of machine learning, most companies build classification models to perform churn analysis on their customers

A Classification project aimed at assisting a telecommunications company understand their data and find the life time value of each customer and know what factors affect the rate at which customers stop using their network. Predict whether a customer will churn or not

DATA FOR THE PROJECT
The data for this projects was divided into 3. The first 2 data sets are for training and evaluation the machine learning model  while the last data set is for testing the model. Please keep this in mind


First Data Set

The first 3000 records of the dataset can be found in a database you will have to access remotely


server name: dap-projects-database.database.windows.net
user: LP2_project
password: Stat$AndD@t@Rul3
database name: dapDB
table name: dbo.LP2_Telco_churn_first_3000


Please note that you only have read privileges which mean you will not be able to insert, delete or update the table in the database. The Database Management System for this project is MIRCORSOFT SQL SERVER. You should connect to the database using an Open Database Connectivity standard library like pyodbc, or an Object-Relational Mapping library SQLAlchemy. Note that you cannot use the read_csv() method in this case. You can find a notebook on how to do this in this GitHub Repository.


Second Data Set

The second part of the data is hosted on this GitHub Repository in a file called LP2_Telco-churn-second-2000.csv. 


Testing Data Set

The final 2000 records of the data set needed for this project can be found in this OneDrive. The filed is named Telco-churn-last-2000.xlsx. 

Please note that this is your test dataset. This Dataset will be used for testing the accuracy of your models. 


Project Rubrics

The Sprint's rubrics can be found on this GitHub Repository, and further explanations of the features can also be found in this repository. Please read them carefully.


Based on the findings that customers with dependents, senior citizens, and customers with partners are less likely to churn, here are some professional recommendations for the company:

Targeted Marketing Campaigns:

Recommendation: Develop targeted marketing campaigns to attract and retain customers without dependents.
Rationale: Since customers with dependents are less likely to churn, the company can focus on promoting family-oriented services or benefits that appeal to this demographic. Tailoring marketing messages to the needs and preferences of customers without dependents can help attract and retain this segment.
Enhanced Senior Citizen Programs:

Recommendation: Enhance loyalty programs or introduce special offers for senior citizens.
Rationale: Given that senior citizens are less likely to churn, the company can capitalize on this by offering exclusive promotions, discounts, or personalized services for this demographic. Creating a positive and rewarding experience for senior customers can contribute to their loyalty and satisfaction.
Promote Partner-Centric Services:

Recommendation: Design marketing strategies that emphasize benefits for customers with partners.
Rationale: Since customers with partners are less likely to churn, the company should highlight features or services that cater to couples. This could include special promotions for family plans, bundled services, or exclusive offers that incentivize customers to engage with the company as a household.
Customer Engagement Programs:

Recommendation: Implement customer engagement programs for all segments to strengthen relationships.
Rationale: While specific recommendations are made for customers without dependents, senior citizens, and those with partners, it's crucial to implement overarching customer engagement programs. Building strong relationships with all customers through personalized communication, feedback mechanisms, and responsive customer service can contribute to overall customer satisfaction and loyalty.
Regular Data Monitoring and Analysis:

Recommendation: Continuously monitor customer churn patterns and demographics.
Rationale: The business landscape is dynamic, and customer preferences may change over time. Regularly analyze customer data, conduct surveys, and stay attuned to market trends to adapt strategies accordingly. This ensures that the company remains responsive to evolving customer needs.
Feedback Mechanisms:

Recommendation: Implement robust feedback mechanisms to understand customer sentiments.
Rationale: Establishing channels for customer feedback helps the company gain insights into customer satisfaction and areas that may need improvement. Actively seek feedback from different customer segments to refine services and address specific concerns.
Employee Training:

Recommendation: Provide training to customer-facing employees for effective communication.
Rationale: Ensure that customer service representatives are trained to understand and address the needs of diverse customer segments. Effective communication plays a vital role in building trust and satisfaction, contributing to customer retention.
Remember, these recommendations should be implemented in a thoughtful and phased manner, and continuous evaluation of their impact should be conducted to refine strategies over time


**Business Implications:**

**DSL:**

**Observation:** *DSL has a higher number of customers who haven't churned compared to those who have.*
**Implication:** *DSL customers are relatively more loyal or less likely to churn. The company could explore the reasons for this loyalty and use it to develop strategies to retain customers.*


**Fiber Optic:**

**Observation:** *Fiber optic has a significant number of customers who have churned.*
**Implication:** *There might be issues or dissatisfaction among Fiber optic customers leading to higher churn. The company should investigate the reasons for dissatisfaction and work on improving service quality or addressing customer concerns to reduce churn.*

**No Internet Service:**

**Observation:** *The number of customers with no internet service who have churned is relatively low.*
**Implication:** *Customers without internet service are less likely to churn. This might suggest that the company could explore strategies to upsell or cross-sell internet services to this segment or focus on retaining them through other means.*

**Overall Business Strategy:**

**Segment-Specific Strategies:** *Tailor retention strategies based on the characteristics of each internet service type. For example, improving Fiber optic service quality or providing incentives for DSL customers to upgrade their plans.*

**Customer Experience Improvement:** *Investigate and address common issues or reasons for churn, especially in the Fiber optic category, to enhance overall customer satisfaction.*

**Promotions and Upselling:** *Consider targeted promotions or upselling efforts, especially for customers without internet service, to increase revenue and provide additional value.*

**Data-Driven Decision Making:** *Continue monitoring churn data over time and use it to make data-driven decisions to optimize customer retention strategies.*

**Understanding the reasons behind churn and proactively addressing them can significantly impact customer satisfaction and the company's bottom line**

Based on the findings that customers with certain contract types, paperless billing, and payment methods are more likely to churn, here are some professional recommendations for the company:

Promote Long-Term Contracts:

Recommendation: Incentivize customers to opt for long-term contracts of one year or more.
Rationale: Since customers with month-to-month contracts are more likely to churn, the company can introduce special discounts, promotions, or additional benefits for customers who commit to longer contract durations. This strategy provides stability and reduces the likelihood of churn.
Enhance PaperlessBilling Experience:

Recommendation: Improve the value proposition of paperless billing or introduce incentives for its use.
Rationale: Customers using paperless billing are more likely to churn, so the company should focus on enhancing the benefits of this feature. This could include exclusive discounts, rewards, or simplified processes for paperless billing users. Improving the overall user experience of this service may contribute to customer retention.
Diversify Payment Options:

Recommendation: Provide more payment options and promote alternatives to Electronic Check.
Rationale: Customers using Electronic Check are the most likely to churn, suggesting dissatisfaction with this payment method. Introduce a variety of payment options, educate customers about their choices, and incentivize the use of methods like Credit Cards (Automatic), which are associated with lower churn rates.
Customer Education Programs:

Recommendation: Implement educational programs to inform customers about contract types and billing options.
Rationale: Some customers may not fully understand the benefits of long-term contracts or the nuances of different billing options. Develop educational materials, FAQs, and customer support resources to help customers make informed decisions about contracts and billing preferences.
Personalized Retention Offers:

Recommendation: Design personalized retention offers for at-risk customer segments.
Rationale: Utilize the findings to identify customer segments that are more likely to churn. Develop targeted retention offers, such as discounts, exclusive features, or loyalty rewards, tailored to the specific needs and preferences of these segments.
Regular Customer Feedback:

Recommendation: Implement regular surveys and feedback mechanisms to understand customer sentiments.
Rationale: Customer preferences and expectations may evolve over time. Regularly seek feedback to gauge customer satisfaction, identify pain points, and uncover opportunities for improvement. Act on feedback to enhance the overall customer experience.
Improve Billing Transparency:

Recommendation: Enhance transparency in billing processes and communicate changes effectively.
Rationale: Customers may be more likely to churn if they encounter unexpected charges or if billing processes are unclear. Ensure that billing statements are transparent, and communicate any changes in billing practices proactively to build trust with customers.
These recommendations aim to address specific pain points identified in the findings and create a more customer-centric approach to reduce churn rates. Continuous monitoring and adjustment of strategies based on customer feedback and market dynamics are essential for long-term success.

Professional Recommendations:

Understanding the Matrix:

The matrix represents the correlation coefficients between different variables, indicating the strength and direction of their linear relationships.
A correlation coefficient ranges from -1 to 1, where:
1 indicates a perfect positive correlation.
-1 indicates a perfect negative correlation.
0 indicates no linear correlation.
In this context, the matrix shows correlations between SeniorCitizen, tenure, MonthlyCharges, and TotalCharges.
Interpretation of Matrix:

SeniorCitizen vs. Other Variables:

There is a weak positive correlation (0.22) between being a SeniorCitizen and MonthlyCharges.
A very weak positive correlation (0.0046) exists between SeniorCitizen and tenure.
SeniorCitizen has a very weak positive correlation (0.095) with TotalCharges.
Tenure vs. Other Variables:

A moderate positive correlation (0.24) exists between tenure and MonthlyCharges.
Strong positive correlation (0.83) is observed between tenure and TotalCharges.
MonthlyCharges vs. TotalCharges:

There is a moderate positive correlation (0.65) between MonthlyCharges and TotalCharges.
Recommendations Based on Findings:

1. Pricing Strategy for Seniors:

Consider tailoring pricing plans or promotions for SeniorCitizens, as there is a positive correlation between SeniorCitizen status and MonthlyCharges. Seniors may have specific preferences or budget considerations.
2. Loyalty Programs for Tenured Customers:

Implement loyalty programs or incentives for customers with longer tenure, as there is a strong positive correlation between tenure and TotalCharges. This encourages customer retention.
3. Pricing and Value Bundles:

Evaluate MonthlyCharges in conjunction with TotalCharges to develop pricing and value bundles. Understanding the moderate correlation between MonthlyCharges and TotalCharges can help optimize offerings.
4. Communication Strategies:

Develop targeted communication strategies for different customer segments. For instance, focus on explaining the value of services to customers with shorter tenures to potentially increase TotalCharges over time.
5. Customer Segmentation:

Use the correlation insights to create customer segments based on tenure, SeniorCitizen status, and pricing preferences. Tailor marketing and service strategies for each segment.
In Simple Terms:

The matrix shows how different factors relate to each other. Positive numbers mean things tend to go up together, negative numbers mean one thing goes up when the other goes down, and zero means there's no clear relationship.
For this business:
Being a senior slightly relates to higher monthly charges.
The longer someone stays (tenure), the more they tend to spend.
Monthly charges and total charges are related, but not too strongly.
Recommendations:
Offer special deals for seniors.
Reward customers who stay longer.
Create pricing plans that balance monthly and total charges.
Tailor messages to different customer groups based on these insights

**Considerations and Recommendation to the Team**
**Causation vs. Correlation:** *It's important to note that finding a relationship does not necessarily imply causation.* *Even if there is a correlation between gender and churn rate, other factors might be influencing both, and further analysis is needed to establish causation.*
**Ethical Considerations:** *When dealing with gender-related data, it's crucial to handle the information ethically, respecting privacy and avoiding any discriminatory practices*

**Considerations and Recommendation for the Team**:

**Causation vs. Correlation:** *Establishing a relationship doesn't necessarily imply causation.* *Other factors, such as customer support, pricing, or regional considerations, could also contribute to churn.*
*Customer Feedback: Combining quantitative analysis with qualitative data, such as customer feedback, can provide a more comprehensive understanding of the reasons behind churn.*

**Business Insights on Gender:** 
*Understanding such a relationship could provide valuable insights for businesses. For example, it might lead to targeted strategies to retain customers of a specific gender, or it could inform marketing approaches tailored to different gender segments.*

**Decision-Making:** 
*Businesses might use this information to make informed decisions about resource allocation, customer engagement, or service improvements.*

Business Implications:

DSL Service: The business may want to analyze why DSL customers are less likely to churn and identify factors that contribute to customer retention. This information can be used to implement strategies to retain more customers, potentially by offering targeted promotions or improving service quality.

Fiber Optic Service: Given the higher churn rate among fiber optic customers, the business should investigate the reasons behind this. It could be related to service issues, pricing, or customer satisfaction. Addressing these issues could help reduce churn and improve customer loyalty.

No Internet Service: Understanding why some customers without internet service are churning may also provide insights. It's possible that there are specific needs or expectations that are not being met. Identifying and addressing these concerns can help retain more customers in this segment.

In summary, this table provides a snapshot of churn rates based on different types of internet services. Analyzing and addressing the factors influencing churn in each category can help the business develop targeted strategies to improve customer retention.

**Correlation between monthly charges (MonthlyCharges), total charges (TotalCharges), and customer churn?**

**MonthlyCharges and TotalCharges**
*Business Implications: This correlation suggests that the company's revenue is positively influenced by higher monthly charges. The business may consider offering premium services or encouraging customers to upgrade their plans to increase overall revenue.*

**Tenure and other variables:**
*Business Implications: Customers who have been with the company for a longer time tend to have higher TotalCharges. This suggests that customer loyalty and retention over time contribute significantly to the total amount charged. The company may want to implement strategies to retain customers for longer periods.*

**SeniorCitizen and other variables:**
**Business Implications:** 
*Being a senior citizen doesn't strongly influence MonthlyCharges or TotalCharges. The company may not need to focus specific strategies on senior citizens regarding these two financial metrics.*

**In summary, understanding these correlations helps the business identify relationships between different variables. For example, the company may focus on customer retention strategies to increase tenure and, consequently, TotalCharges. Additionally, exploring ways to increase MonthlyCharges could positively impact overall revenue**


Business Implications:

Gender Differences in Churn:
The business may want to investigate why there is a difference in churn rates between genders. This could involve understanding if there are specific factors or services that appeal differently to male and female customers.
Targeted Strategies:
If there are identifiable preferences or needs based on gender, the company can tailor its marketing and service strategies to better meet the expectations of both male and female customers. This might involve personalized promotions or communication strategies.
Overall Churn Management:

Identifying Risk Groups:
Understanding the distribution of churn among male and female customers helps the business identify potential risk groups. This insight can be used to implement targeted retention strategies for those at a higher risk of churning.
Improving Retention:
The company can use the information to focus on improving customer satisfaction and loyalty, addressing any issues that may be more prevalent in one gender group over the other.
In summary, analyzing churn based on gender can provide valuable insights for developing targeted strategies to reduce churn rates. The business can use this information to enhance customer satisfaction and implement gender-specific retention initiatives, ultimately improving overall customer loyalty and profitability

**Conclusion on Hypothesis Testing:**

Interpretation: The statement "There is a significant relationship between Total Charges and customer churn" suggests that the p-value is below the significance level (commonly set at 0.05).
Meaning: The small p-value provides evidence to reject the null hypothesis that there is no relationship between Total Charges and customer churn. Therefore, there is statistical support for the existence of a significant relationship.
Business Implications:

Understanding the Relationship:
The significant relationship between Total Charges and customer churn indicates that these two variables are associated. This could mean that customers with certain Total Charges are more likely to churn.
Strategic Decision-Making:
The business can use this information to make strategic decisions. For example, it might identify customer segments with high Total Charges that are more prone to churn and implement targeted retention strategies for those segments.
Improving Customer Retention:
By understanding the factors associated with customer churn (in this case, Total Charges), the company can take proactive measures to address issues, improve service, or offer incentives to reduce churn rates and retain valuable customers.
In summary, the Kruskal-Wallis test results suggest a significant relationship between Total Charges and customer churn. This information can guide the business in making informed decisions to improve customer retention and overall customer satisfaction






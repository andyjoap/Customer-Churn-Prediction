# Customer-Churn-Prediction

📌 Project Overview 

A telecommunications company which is concerned about the number of customers leaving their land-line business for cable competitors. They need to understand who is more likely to leave the company. These insights empower the company to take preventive decisions.

🛠️ Methodology

Data Preprocessing

Modeling: Implemented a Random Forest Classifier, optimized specifically for Recall (75%) to capture the highest possible number of at-risk customers.

Feature Importance Analysis: Performed a detailed extraction of key features to understand the "why" behind customer departures, focusing on behavioral and demographic patterns.

Business Intelligence: Translated technical metrics into actionable business interventions

📊 Key Results

* Recall Rate: 0.75 — The ML model successfully identifies 75% of customers who are actually planning to leave, providing a wide window for intervention.

* Customers in their first 12 months exhibit the highest risk of attrition. Beyond the first year, churn probability drops significantly

* A significant 41% of customers paying over $70/month (primarily Fiber Optic users) eventually churn. This high-tier group is so critical that it accounts for 67% of all churn cases across the entire dataset.

* Among Fiber Optic customers who churned, 50% did not have technical support included in their plans. This confirms that the lack of value-added services is a stronger driver of abandonment than price alone.

* Senior citizens enrolled in Paperless Billing show a disproportionate 45% churn rate. This data point reveals that digital-only communication is a high-risk factor for this specific demographic

* Customers on Month-to-month contracts using Fiber Optic and paying over $70 exhibit a staggering 54.14% churn rate

📈 Strategic Insights

1) We have developed a predictive machine learning model to identify at-risk customers. The model successfully detects 75% of customers who are actually planning to leave, allowing the company to take proactive retention measures before the loss occurs.

2) Early-stage customers show the highest churn risk. We propose implementing NPS surveys at months 3 and 6 to identify friction points. Additionally, a 6-month introductory discount will bridge the gap until the 'loyalty peak' at year 5.

3) With 67% of churned customers coming from the Fiber Optic segment, service stability is paramount. We must prioritize infrastructure audits and technical maintenance to ensure that the premium price is justified by premium performance.

4) Since 50% of Fiber Optic customers that churn lack technical support, we recommend bundling complimentary Tech Support instead of reducing prices. This adds value to the high-tier segment and directly addresses a known churn driver.

5) To stabilize the most volatile segment (Fiber + Month-to-month), we propose a targeted conversion campaign. Offering incentives to switch to 1 or 2-year plans will create a structural barrier against attrition.

6) Offer complimentary physical billing to Senior Citizens currently on Paperless plans to mitigate the 45% churn rate. Eliminating digital friction for this segment is a low-cost intervention that protects high-lifetime-value customers. 

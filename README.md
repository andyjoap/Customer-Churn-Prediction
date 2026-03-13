# Customer-Churn-Prediction

A telecommunications company which is concerned about the number of customers leaving their land-line business for cable competitors. They need to understand who is more likely to leave the company.

📌 Project Overview 

A telecommunications company which is concerned about the number of customers leaving their land-line business for cable competitors. They need to understand who is more likely to leave the company.

🛠️ Methodology

Data Preprocessing: Handled class imbalance to ensure the model could effectively identify the minority class (churners).

Modeling: Implemented a Random Forest Classifier, optimized specifically for Recall (75%) to capture the highest possible number of at-risk customers.

Feature Importance Analysis: Performed a detailed extraction of key features to understand the "why" behind customer departures, focusing on behavioral and demographic patterns.

Business Intelligence: Translated technical metrics into actionable business interventions, such as lifecycle management and infrastructure audits.

📊 Key Results

Recall Rate: 0.75 — The model successfully identifies 75% of customers who are actually planning to leave, providing a wide window for intervention.

Precision (Churn): 0.50 — Balanced to ensure that while we capture most churners, the retention campaigns remain cost-effective.

Model Reliability: High performance in distinguishing stable customers from volatile ones using tenure and contract data.

📈 Strategic Insights

1) We have developed a predictive machine learning model to identify at-risk customers. The confusion matrix confirms high precision in detecting potential churners, allowing for proactive retention actions. The model successfully detects 75% of customers who are actually planning to leave, allowing the company to take proactive retention measures before the loss occurs.

2) Early-stage customers show the highest churn risk. We propose implementing NPS surveys at months 3 and 6 to identify friction points. Additionally, a 6-month introductory discount will bridge the gap until the 'loyalty peak' at year 5.

3) Offer complimentary physical billing to Senior Citizens currently on Paperless plans to mitigate the 45% churn rate. Eliminating digital friction for this segment is a low-cost intervention that protects high-lifetime-value customers.

4) With 67% of churned customers coming from the Fiber Optic segment, service stability is paramount. We must prioritize infrastructure audits and technical maintenance to ensure that the premium price is justified by premium performance.

5) Since 50% of Fiber Optic customers lack technical support, we recommend bundling complimentary Tech Support instead of reducing prices. This adds value to the high-tier segment and directly addresses a known churn driver.

6) To stabilize the most volatile segment (Fiber + Month-to-month), we propose a targeted conversion campaign. Offering incentives to switch to 1 or 2-year plans will create a structural barrier against attrition.

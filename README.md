**🧮 Customer Segmentation using Clustering – AllLife Bank**

📌 **Context**
AllLife Bank aims to strengthen its credit card business in the upcoming financial year. Market research indicates two key issues:
1.	Low market penetration → Marketing wants to launch personalized campaigns to acquire new customers and upsell existing ones.
2.	Poor perception of customer support → Operations wants to upgrade service delivery to reduce query resolution time.
To support these goals, the Heads of Marketing and Operations have approached the Data Science team to segment customers and understand behavioral patterns.
________________________________________

**🎯 Objective**
The goal of this project is to:
•	Identify distinct customer segments based on spending patterns and past interactions
•	Apply clustering algorithms to uncover hidden behavioral groups
•	Provide actionable recommendations for:
o	Targeted marketing campaigns
o	Improved service delivery models
This segmentation will enable the bank to optimize acquisition, retention, engagement, and customer satisfaction.
________________________________________

**📂 Dataset Description**
The dataset includes customer demographic and behavioral features:
Data Dictionary
•	Sl_No: Record index
•	Customer Key: Unique customer ID
•	Average Credit Limit: Average credit limit across all credit cards
•	Total Credit Cards: Number of credit cards owned
•	Total Visits (Bank): Yearly in-person visits
•	Total Visits (Online): Yearly online logins
•	Total Calls Made: Yearly calls to the bank or customer support
These variables collectively capture customers’ financial capacity, engagement level, and support dependency.
________________________________________

**🔄 Project Workflow**
1.	Data Understanding & Cleaning
2.	Exploratory Data Analysis (EDA)
3.	Feature Scaling & Normalization
4.	Clustering (K-Means, Hierarchical Clustering)
5.	Cluster Profiling
6.	Insights & Recommendations
________________________________________

**📊 Customer Segmentation Results**
**🟣 Segment 0 – Mass Market Users**
•	Largest cluster
•	Moderate credit limit (~₹33.7k)
•	Moderate card ownership (~5.5)
•	Moderate bank visits, low online usage, few calls
•	Interpretation: Stable, loyal customers with consistent behavior
Opportunities: Upsell credit cards/products, promote digital usage
________________________________________

**🟢 Segment 1 – Premium / Digital Users**
•	Smallest but distinct cluster
•	Highest credit limit (~₹141k)
•	Most credit cards (~8.7)
•	Very high online activity, low calls/visits
•	Interpretation: High-value, digital-first customers
Strategy: Retain with exclusive perks, not aggressive upselling
________________________________________

**🔴 Segment 2 – Support-Seeking / Low Value Users**
•	Medium-sized cluster
•	Lowest credit limit (~₹12.2k), fewest cards (~2.4)
•	High call volume (~6.8), minimal digital usage
•	Interpretation: Dependent on support, frustrated or low-engaged users
Strategy: Improve support, encourage digital onboarding
________________________________________

**💡 Actionable Insights & Recommendations**
**⭐ Best Target for Marketing: Segment 0 (Mass Market Users)**
•	Represents the majority (387 customers)
•	Good potential for upselling additional cards/services
•	Low digital usage → opportunity to promote mobile/online banking

**Recommended Actions:**
•	Personalized upsell campaigns
•	Incentives for digital adoption (cashback, fee waivers)
________________________________________

**🛠️ Best Target for Service Improvement: Segment 2 (Support-Seeking Users)**
•	High call frequency indicates pain points
•	Less digitally engaged → may require guided support

**Recommended Actions:**
•	Improve call center efficiency
•	Offer multi-channel support (chatbots, WhatsApp, IVR)
•	Educate customers on self-service tools
________________________________________

**💎 Retention Focus: Segment 1 (Premium Digital Users)**
•	High credit usage and strong digital engagement
•	Least support-dependent

**Recommended Actions:**
•	Loyalty programs, exclusive offers
•	Premium support channels
•	Avoid over-targeting to prevent fatigue
________________________________________

**🧰 Technologies Used**
•	Python, Pandas, NumPy
•	Scikit-learn
•	Matplotlib, Seaborn
•	Jupyter Notebook


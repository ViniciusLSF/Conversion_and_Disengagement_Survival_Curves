📊 Customer Conversion & Disengagement Survival Analysis

Understanding when customers convert — and when they silently disengage — is often more valuable than simply predicting if they will convert.

This project applies Survival Analysis to model customer behavior over time, identifying risk patterns and generating actionable insights for retention and growth strategies.

🚀 Business Problem

Many companies focus only on conversion rates, ignoring a critical dimension:

👉 time-to-conversion

Customers who take too long often disengage before converting — creating hidden revenue loss.

This project answers key strategic questions:

How long does a typical customer take to convert?

When does disengagement risk spike?

What behavioral patterns indicate early abandonment?

When should the business intervene?

🎯 Objectives

Model customer conversion as a time-to-event problem

Estimate disengagement risk across the customer lifecycle

Identify high-risk windows for churn

Support data-driven retention strategies

🧠 Methodology

The project follows a structured Data Science workflow:

✔ Data Preparation

Handling censored data

Feature engineering

Behavioral timeline construction

✔ Exploratory Analysis

Distribution of conversion times

Cohort behavior

Early disengagement signals

✔ Survival Modeling

Kaplan-Meier estimator to measure survival probability

Conversion vs disengagement curve analysis

Risk interpretation over time

📈 Key Insights

✅ Conversion probability drops significantly after the early lifecycle stage

✅ Customers inactive beyond a critical time window show sharply higher disengagement risk

✅ Survival curves reveal clear opportunities for proactive engagement

👉 Business implication:
Targeting customers before the risk inflection point can materially improve conversion rates.

💡 Strategic Applications

This framework enables companies to:

Trigger lifecycle marketing at optimal moments

Prioritize high-risk users

Reduce wasted acquisition spend

Improve LTV through earlier intervention

🛠 Tech Stack

Languages: Python
Libraries:

Pandas

NumPy

Lifelines

Matplotlib / Seaborn

Techniques:

Survival Analysis

Kaplan-Meier

Time-to-event modeling

Behavioral analytics

⭐ Why This Project Matters

Most churn projects rely on classification models.

This project goes deeper by answering:

👉 "When will we lose the customer?"

Understanding timing unlocks far more effective business decisions.

🔮 Next Steps (Planned Improvements)

Cox Proportional Hazards model

Feature-driven risk estimation

Survival model comparison

Business simulation scenarios

Deployment-ready scoring pipeline

👨‍💻 Author

Vinícius Silva
Senior Data Analyst | Data Science | Machine Learning

📫 vniluizdasilva@gmail.com

💼 https://www.linkedin.com/in/vin%C3%ADciusluiz/

# The Analysis

## 1. What are the most demanded Skills for the Top 3 most popular Data roles?

To find the most demanded skills for the top 3 most popular data roles. I filtered out those positions by which ones where the most popular, and got the top 5 skills for these top 3 roles. This query highlights the most popular job titles and their job top skills, showing which skills I should pay attention to depending on the role I'm targeting.

View my notebook with detailed steps here: [2_Skills_Demand.ipynb](2_Skills_Demand.ipynb)

### Results
![Visulization of Top Skills for Data roles](Images\skill_demand.png)

### Insights
🔑 Overall Trends
SQL and Python dominate across all roles — they’re the core skills in data careers.
Each role has a distinct “second layer” of tools depending on responsibilities.

📊 Data Analyst
SQL (51%) and Excel (41%) are the top skills → strong focus on querying + reporting.
Tableau (28%) and Python (27%) are useful but secondary.
Insight: Analysts are more business-facing, relying heavily on tools for reporting and dashboards rather than heavy programming.

⚙️ Data Engineer
SQL (68%) and Python (65%) are almost equally critical → strong backend/data pipeline work.
Cloud skills (AWS 43%, Azure 32%) + Spark (32%) are key differentiators.
Insight: This role is highly technical and infrastructure-focused, requiring distributed systems and cloud knowledge.

🤖 Data Scientist
Python (72%) is #1 by far → the most programming-heavy role.
SQL (51%) and R (44%) show a mix of data manipulation + statistical work.
Lower emphasis on tools like Tableau → less focus on dashboards.
Insight: Data scientists focus more on modeling, statistics, and machine learning.

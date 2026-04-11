# The Analysis

## 1. What are the most demanded Skills for the Top 3 most popular Data roles?

To find the most demanded skills for the top 3 most popular data roles. I filtered out those positions by which ones where the most popular, and got the top 5 skills for these top 3 roles. This query highlights the most popular job titles and their job top skills, showing which skills I should pay attention to depending on the role I'm targeting.

View my notebook with detailed steps here: [2_Skills_Demand.ipynb](2_Skills_Demand.ipynb)

### Results
![Visulization of Top Skills for Data roles](Images/skill_demand.png)

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

---

## 2. How are in-demand skills trending for Data Analysts?

View my notebook with detailed steps here: [3_Skills_Trend.ipynb](3_Skills_Trend.ipynb)

### Results
![Trending Top skills for Data Analysts in the US](Images/skill_trend.png)

*This graph visulizing the trending top skills in Data Analysis in 2023.*

### Insights:
1. SQL dominates consistently
SQL has the highest demand throughout the entire year.
Even though it slightly declines toward the end (from ~63% to ~53%), it still remains #1 by a clear margin.
👉 Insight: SQL is non-negotiable for data analysts.

2. Excel is strong but volatile
Starts high (~43%), peaks around July–August (~45%), then drops sharply (~34%) before recovering in December.
👉 Insight: Excel is still important, but demand fluctuates more compared to SQL—possibly due to seasonal or role-specific needs.

3. Python is growing (long-term upward trend)
Starts around ~29% and ends higher (~33%).
Shows some dips but overall clear upward momentum, especially in the second half of the year.
👉 Insight: Python is becoming more important → shift toward automation + advanced analytics.

4. Tableau is stable but slightly declining
Starts ~35% and trends downward to ~30%.
Minor peaks mid-year but overall gradual decrease.
👉 Insight: Visualization tools are still needed, but maybe:
Being replaced by alternatives (Power BI, Python viz)
Or becoming a baseline skill rather than a differentiator.

5. Power BI is steady but lowest demand
Ranges between ~18%–23% all year.
Very stable, no big spikes.
👉 Insight: Power BI demand is consistent but less dominant than Tableau in this dataset.

---
## 3. How well do jobs and skills pay for Data Analysts?

View my notebook with detailed steps here: [4_Salary_Analysis.ipynb](4_Salary_Analysis.ipynb)

### Salary Analysis

### Result

![Salary Distributions of Data jobs in the US](Images/salary_distribution.png)

*Box Plot visulizing the salary ditributions for the top 6 data jobs titles.*

### Insights:
- There's a significant variation in salary ranges across different job titles. Senior Data Scientist positions tend to have the highest salary potential, with up to $600K, indicating the high value placed on advanced data skills and experience in the industry.

- Senior Data Engineer and Senior Data Scientist roles show a considerable number of outliers on the higher end of the salary spectrum, suggesting that exceptional skills or circumstances can lead to high pay in these roles. In contrast, Data Analyst roles demonstrate more consistency in salary, with fewer outliers.

- The median salaries increase with the seniority and specialization of the roles. Senior roles (Senior Data Scientist, Senior Data Engineer) not only have higher median salaries but also larger differences in typical salaries, reflecting greater variance in compensation as responsibilities increase.

#### Investigate Median Salary Vs Skills for Data Analysts

![Highest Paid and most demanded skills](Images/top_paid_skills.png)

---
## 4. What is the most optimal skill to learn for Data Analysts?

To identify the most optimal skills to learn ( the ones that are the highest paid and highest in demand) I calculated the percent of skill demand and the median salary of these skills. To easily identify which are the most optimal skills to learn.

View my notebook with detailed steps here: [5_Optimal_Skills.ipynb](5_Optimal_Skills.ipynb)

### Visualizing Different Techonologies

Let's visualize the different technologies as well in the graph. We'll add color labels based on the technology (e.g., {Programming: Python})

### Results

![Most Optimal Skills for Data Analyst](Images/optimal_skills.png)

A scatter plot visualizing the most optimal skills (high paying & high demand) for data analysts in the US with color labels for technology.

### Insights

- The scatter plot shows that most of the programming skills (colored blue) tend to cluster at higher salary levels compared to other categories, indicating that programming expertise might offer greater salary benefits within the data analytics field.

- The database skills (colored orange), such as Oracle and SQL Server, are associated with some of the highest salaries among data analyst tools. This indicates a significant demand and valuation for data management and manipulation expertise in the industry.

- Analyst tools (colored green), including Tableau and Power BI, are prevalent in job postings and offer competitive salaries, showing that visualization and data analysis software are crucial for current data roles. This category not only has good salaries but is also versatile across different types of data tasks.


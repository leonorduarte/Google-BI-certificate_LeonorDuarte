# Google-BI-certificate_LeonorDuarte
# Leonor Duarte - Portfolio
## About
Hi, I’m Leonor! I have a strong academic foundation in Management and Marketing Intelligence and am currently pursuing a Master’s in Data-Driven Marketing. My passion lies in combining data analytics and strategic insights to solve real-world problems. I am excited to bring my technical and analytical skills to the fields of data science and project management as an entry-level data specialist and project leader.

During my studies, I honed my ability to work with complex datasets and developed a knack for identifying patterns and actionable insights. I’ve also gained hands-on experience in data visualization, statistical analysis, and workflow optimization, which I believe are key assets in supporting impactful decision-making. Certifications like the IBM Data Science Specialization and Scrum Master further complement my skills.
This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

# Summary of This Repository
## Completed Courses 
- **Course 1:** Foundations of Business Intelligence
- **Course 2:** The Path to Insights: Data Models and Pipelines
- **Course 3:** Decisions, Decisions: Dashboards and Reports

### Google Fiber- Case study

**Background** Google Fiber provides people and businesses with fiber optic internet. Currently, the customer service team working in their call centers answers calls from customers in their established service areas. In this fictional scenario, the team is interested in exploring trends in repeat calls to reduce the number of times customers have to call in order for an issue to be resolved.

**Scenario** You are currently interviewing for a BI position on the Google Fiber call center team. As part of the interview process, they ask you to develop a dashboard tool that allows them to explore trends in repeat calls. The team needs to understand how often customers call customer support after their first inquiry. This will help leadership understand how effectively the team can answer customer questions the first time.

First, I started with completing 3 Key business intelligence documents under course guidence. The documents are:

[Stakeholder Requirements Document](https://github.com/leonorduarte/Google-BI-certificate_LeonorDuarte/blob/main/Google_Fiber_Stakeholder-Requirements-Document_LD.pdf) This is to capture stakeholder requests and requirements so you understand their needs before planning the rest of the project details or strategy.

[Project Requirements Document](https://github.com/leonorduarte/Google-BI-certificate_LeonorDuarte/blob/main/Google_Fiber_Project-Requirements-Document_LD.pdf) This document cover project requirements that need to be met to achieve the stakeholder requirements.

[Strategy Document](https://github.com/leonorduarte/Google-BI-certificate_LeonorDuarte/blob/main/Google_FiberStrategy-Document_LD.pdf) This is a collaborative place to align with stakeholders about project deliverables. 

> In this project, I started by working with three Excel files containing customer call data across various markets and issue types. Using Power Query in Power BI, I imported the data for processing and applied several cleaning and transformation steps. These included changing data types, particularly for the date column, and extracting time-based components such as month, week, quarter, and day to enable detailed temporal analysis. Rows with missing values in critical columns like market and type were removed, and null values in the contact_n_# column were replaced with zeros to ensure data integrity. Consistent cleaning steps were applied across all files to maintain uniformity, and column names were standardized for clarity. The cleaned data was organized into sheets renamed as Market_1, Market_2, and Market_3 for better identification and saved for further analysis. In Power BI, I loaded the cleaned data and used the Append Queries feature to merge multiple sheets into a single unified dataset. Calculated fields were created, such as "Total repeated calls," by aggregating the contact_n_# values across different markets and issue types. For visualization, I designed a dual-axis chart to display day 0 calls and repeat calls by market type, as well as pie charts and column charts to show the distribution of repeated calls by issue type. Filters for month and day were added to facilitate dynamic analysis, and tooltips were customized to enhance clarity and provide additional context within the visualizations.

# Conclusions
The analysis revealed key insights. Market 1 accounted for the majority of repeated calls, approximately 63%, followed by Market 3 with 34%, while Market 2 contributed only 4%. Among issue types, Type 5 (Internet and WiFi) had the highest proportion of repeated calls at 51%, followed by Type 2 (Technician Troubleshooting) at 30%. Type 4 (Construction) had the lowest percentage, just 1%. Timing analysis showed that repeated calls most commonly occurred on day 1 following the initial contact, highlighting the need for prompt issue resolution. Weekly patterns indicated that Markets 1 and 2 saw the highest volume of repeated calls on Mondays, whereas Market 3 experienced a peak on Wednesdays.

Then, I create the [dashboard](https://github.com/leonorduarte/Google-BI-certificate_LeonorDuarte/blob/main/Google%20Fiber%20Call%20Resolution%20Optimization%20Dashboard%20(1).pdf) using Power BI!





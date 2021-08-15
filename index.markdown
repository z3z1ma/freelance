---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

\
👇
# Alex Butler ⚡

\
\
\
\
Hello! My name is Alex Butler 👋. I am a freelance data/analytics engineer specializing in the _Modern Data Stack_ including proficiency with Python, Data Pipelines, SQL, Data Warehouse Design, Data Governance, and dbt (data build tool). I am a tech enthusiast interested in the cutting edge of modern analytics. 🚀

Looking to Modernize your data stack? Managing expenses and churn in Excel? Struggling to democratize and share data amongst a growing team as a single source of truth? Difficulty creating KPIs to measure the performance of your business and make informed decisions? Or maybe just looking to hit the ground running early so you have no regrets later (inactionable data, compromised data, or data loss) due to lack of Data Governance.

I specialize in open source technologies. 🙌
Together, we can solve your problems with either workshops/consulting sessions whereby I can speak with you and your team of analysts or engineers on what exactly constitutes the Modern Data Stack, why it exists, what dbt is, how to effectively deploy dbt on top of a data warehouse, and general design principles in an interactive session, or alternatively, I can be contracted directly to work with you and your team in a short sprint to stand up the infrastructure and operationalize your data. 

\
\
\
💡 Stack 1

___

A common stack that can be deployed with minimum **monetary** overhead might look something like:

**EXTRACT LOAD**
- AWS EC2 / Google Kubernetes Engine with Jenkins for continuous deployment/job orchestration and Data Loaders authored in Python; good in the short term if sources are unlikely to change and/or the business has a Python developer who can maintain with minimal time investment. If the business is small and data ingestion speed is not an issue, these loaders can be ran locally.

**DATA WAREHOUSE**
- Google BigQuery or Amazon RDS 

**TRANSFORM**
- dbt (Data Build Tool) Cloud suitable for single developer or deployment via EC2 / Kubernetes Engine (recommended)

**BUSINESS INTELLIGENCE**
- Metabase or Apache Superset with a lean towards Metabase (I contribute heavily to an open source project which supercharges dbt + Metabase 🚀)


\
\
\
💡 Stack 2

___

A common stack that can be deployed with minimum **technical** overhead might look something like:

**EXTRACT LOAD**
- Fivetran which will average 100$ per month for companies with less than a certain number of active rows (which is fine when compared to the expensive data engineer time it would take otherwise). Fivetran includes dbt packages for many sources which saves additional time/resources for your team.

**DATA WAREHOUSE**
- Google BigQuery / Snowflake depending on volume of data

**TRANSFORM**
- dbt (Data Build Tool) Cloud or deployment via AWS EC2 + Airflow for orchestration depending on analyst/engineer skillsets

**BUSINESS INTELLIGENCE**
- Metabase or Apache Superset with a lean towards Metabase (I contribute heavily to an open source project which supercharges dbt + Metabase 🚀)

___


\
👇
## Contact Me 📥

Lets assess your business case, needs, and decide if a consultation/workshop or a hands on, expedient, standing up of infrastructure is what is needed to propel your decision making to the next level. I will work to build / present the best solution for your particular team.

butler.alex2010@gmail.com

## Services 👨‍🏫

Please add one of the below to the subject of your email.

- Data Infrastructure Assessment
- Modern Data Stack Consultation / Workshop
- dbt Deployment and Operationalization
- Modern Data Stack Deployment and Operationalization
- Automation Problem Solving

\
\
\
`# Blog Posts Below`
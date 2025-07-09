![image](https://github.com/user-attachments/assets/5eb2a1e5-de4f-422b-b63e-0c88fd673763)

# Introduction
In the dynamic hospitality industry, data-driven decision-making has become an indispensable tool for optimizing operations and enhancing customer satisfaction. This case study explores how leveraging Power BI to analyze hotel booking data can significantly improve operational efficiency and guest experiences.

# Problem Statement
Our client, a prominent hotel chain, is facing challenges in managing bookings and maximizing revenue. They have reached out to Datafied Technologies to utilize data analytics for insights into booking patterns, guest demographics, and operational efficiencies. The goal is to develop a comprehensive strategy to enhance customer satisfaction and optimize revenue.
You are a junior data analyst at Datafied Technologies. You are required to harness the power of data analytics to:
- Identify and understand booking patterns and trends.
- Analyze guest demographics and preferences.
- Develop actionable insights to optimize revenue and enhance customer satisfaction.

# Data Sourcing
You will be working with a dataset encompassing various aspects of hotel bookings, ranging from booking details to guest demographics. Each entry contains essential information like the Average Daily Rate (ADR), number of guests, booking agency, arrival details, room assignments, and more. Understanding and harnessing this data will allow us to uncover patterns, identify opportunities, and make informed decisions.

For further details on the data table specification, consult the data dictionary document.

The successful execution of this project will empower the hotel management to make informed decisions, leading to substantial improvements in revenue optimization and guest satisfaction. This not only transforms traditional hotel management methods but also underscores the significance of a proactive, data-driven approach in addressing the evolving challenges of the hospitality industry.

Data Source: [Hotel Dataset](https://docs.google.com/spreadsheets/d/e/2PACX-1vQJgQDtdAm0IHL4VoVJoZZap2aHZU5oXABM9ox5R_AWOCIy_TLqUzk8MePGZK2p7QIPPTQhTs6KC5YA/pub?output=xlsx)

# Data transformation and cleaning
The dataset was cleaned by removing duplicates, correcting any inconsistent dataypes, and ensuring the data is in a suitable format for analysis and visualization.

### Dataset before cleaning
![image](https://github.com/user-attachments/assets/2f9c6e4a-e454-4cee-bd40-fdfb9f03e583)

### Dataset after cleaning
![image](https://github.com/user-attachments/assets/390bc7ff-7d35-4242-8f9e-dfeb500ae593)

## Data modelling
Dimensions with which to break down the analysis were identified. Hence, new tables for identified dimensions were created. These included:

- Date Table
- Location Table
- Distribution Channel Table
- Hotel Table
- Market Segment Table
- Market Cost Table

The data model was designed using the Star Schema where the different dimensions were connected to the Facts table in a one-to-many relationship.

![image](https://github.com/user-attachments/assets/83ec5d91-06d4-4951-b32a-9f60311fb96b)

## Data analysis and Visualization
Appropriate chart types (e.g., bar charts, line charts, pie charts) were used to represent the metrics and insights. Interactive features such as filters, drill-down options, and tooltips were used for detailed information.

![image](https://github.com/user-attachments/assets/a900b462-3c61-4862-aa45-c501beec3995)


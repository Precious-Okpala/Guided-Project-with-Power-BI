![image](https://github.com/user-attachments/assets/5dfd010c-43ae-4646-ace6-b7cbb50b0bb6)

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

# Data modelling
Dimensions with which to break down the analysis were identified. Hence, new tables for identified dimensions were created. These included:

- Date Table
- Location Table
- Distribution Channel Table
- Hotel Table
- Market Segment Table
- Market Cost Table

The data model was designed using the Star Schema where the different dimensions were connected to the Facts table in a one-to-many relationship.

![image](https://github.com/user-attachments/assets/83ec5d91-06d4-4951-b32a-9f60311fb96b)

# Data analysis and Visualization
Appropriate chart types (e.g., bar charts, line charts, pie charts) were used to represent the metrics and insights. Interactive features such as filters, drill-down options, and tooltips were used for detailed information.

![image](https://github.com/user-attachments/assets/a900b462-3c61-4862-aa45-c501beec3995)

# Insights
- The hotel has a strong overall booking volume, indicating high customer interest and consistent business flow.
- The average daily rate suggests the pricing is moderately set, making it accessible to a wide range of guests.
- Guest retention is very low, which may indicate issues with guest satisfaction, experience, or lack of loyalty programs.
- The cancellation rate is quite high, showing that a significant portion of guests cancel their bookings.
- The majority of bookings come through third-party travel agents, while direct and corporate channels are used far less frequently.
- Most guests prefer the bed and breakfast meal plan, while other meal options like half board or full board are rarely selected.
- One particular room type is overwhelmingly booked, while many other room types have minimal or no bookings.
- Non-repeat guests cancel their bookings much more frequently than repeat guests, who are more consistent and reliable.
- Booking activity peaked in mid-2019, followed by a notable decline, likely influenced by external events such as the pandemic.
- City hotels are slightly more popular than resort hotels, showing a preference among guests for urban accommodations.

# Recommendation
- Introduce loyalty programs and exclusive offers to encourage more guests to return and improve retention.
- Review and tighten cancellation policies or offer non-refundable booking incentives to reduce the high cancellation rate.
- Increase investment in digital marketing and website optimization to drive more direct bookings and reduce dependency on third-party agents.
- Assess and reposition underperforming room types through better promotion, redesign, or by phasing out those with consistently low demand.
- Create attractive meal package deals to encourage guests to explore underused options like half board and full board.
- Focus marketing efforts on retaining repeat guests, as they tend to be more committed and less likely to cancel.
- Activate and leverage global distribution systems (GDS) to attract business and international travelers, especially from the corporate segment.
- Analyze the post-peak booking decline in depth to understand whether it was driven by internal service issues or broader market trends.
- Expand and enhance offerings in city hotels, as they currently attract more guests than resort locations.
- Design seasonal promotions and discounts during historically low booking periods to balance demand throughout the year.

<img width="1294" height="865" alt="image" src="https://github.com/user-attachments/assets/0630d050-fc30-4811-882a-69e11a9d83c4" />

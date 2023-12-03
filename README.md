# Hotel-Booking-Analysis 
A in-depth analysis of booking data from Splendor Hotel Groups to extract useful insights.


# Case Study
## Project Brief: Analyzing Booking Data for Splendor Hotel Groups (SHG)  
Greetings from Splendor Hotel Groups (SHG). As a recently recruited Business Intelligence Analyst and Data Analyst, you will be essential to our efforts to solve the puzzles buried in our booking data. Renowned hospitality company SHG aims to improve visitor experiences and streamline corporate processes by utilizing data-driven insights. Your task is to thoroughly examine one of our best resorts' past booking data in order to identify trends, comprehend consumer behavior, and offer useful suggestions for tactical decision-making.

## Project Overview:
Your task involves a thorough analysis of a comprehensive dataset, featuring intricate details of bookings, guest demographics, distribution channels, and financial metrics. By applying your analytical prowess, we aim to extract meaningful insights that will not only inform operational improvements but also contribute to the overall success of SHG in delivering unparalleled hospitality.

## Objectives of the Analysis:
### Booking Patterns:
  - What is the trend in booking patterns over time, and are there specific seasons or months with increased booking activity?
  - How does lead time vary across different booking channels, and is there a correlation between lead time and customer type?

### Customer Behavior Analysis:
- Which distribution channels contribute the most to bookings, and how does the average daily rate (ADR) differ across these channels?
- Can we identify any patterns in the distribution of guests based on their country of origin, and how does this impact revenue?

### Cancellation Analysis:
- What factors are most strongly correlated with cancellations, and can we predict potential cancellations based on certain variables?
- How does the revenue loss from cancellations compare across different customer segments and distribution channels?

### Revenue Optimization:
- What is the overall revenue trend, and are there specific customer segments or countries contributing significantly to revenue?
- Can we identify optimal pricing strategies based on the Average Daily Rate (ADR) for different customer types and distribution channels?

### Geographical Analysis:
- How does the distribution of guests vary across different countries, and are there specific countries that should be targeted for marketing efforts?
- Is there a correlation between the country of origin and the likelihood of cancellations or extended stays?

### Operational Efficiency:
- What is the average length of stay for guests, and how does it differ based on booking channels or customer types?
- Are there patterns in check-out dates that can inform staffing and resource allocation strategies?

### Impact of Deposit Types:
- How does the presence or absence of a deposit impact the likelihood of cancellations and revenue generation?
- Can we identify any patterns in the use of deposit types across different customer segments?

### Analysis of Corporate Bookings:
- What is the proportion of corporate bookings, and how does their Average Daily Rate (ADR) compare to other customer types?
- Are there specific trends or patterns related to corporate bookings that can inform business strategies?

# Deliverables
- A report of findings

# Methodology
## Data Source
- The data can be found from the link (https://docs.google.com/document/d/1IrTM4L0hCdna1GJopUNYnSPmm9wiTtwYwqkIF1UP_aM/edit?pli=1)

## Data Exploration
- After importing the data, I explored the data to get a feel of the shape, summary and descriptive stats of the data.
  
<img width="326" alt="image" src="https://github.com/isaacmunyao/Hotel-Booking-Analysis/assets/63389925/dcb071d5-16fe-4df6-ba11-8ebc96ff1a89">

## Data Cleaning
- The data was fairly clean and the cleaning process was quite simple. The process included dropping missing values in the Country and renaming the column Cancelled(0/1) to Cancellation Status
  <img width="803" alt="image" src="https://github.com/isaacmunyao/Hotel-Booking-Analysis/assets/63389925/ece14878-7690-45f8-8877-d34d48fcfbfc">

  <img width="479" alt="image" src="https://github.com/isaacmunyao/Hotel-Booking-Analysis/assets/63389925/91fd1a5e-80f4-4b79-9c16-2d961ab89d7f">

## Data Analysis and Visualization
###  Booking Patterns:
  - What is the trend in booking patterns over time, and are there specific seasons or months with increased booking activity?
  - How does lead time vary across different booking channels, and is there a correlation between lead time and customer type?


<img width="824" alt="image" src="https://github.com/isaacmunyao/Hotel-Booking-Analysis/assets/63389925/d375e211-57a7-4fe3-8b29-4afd8508ccb7">


<img width="801" alt="image" src="https://github.com/isaacmunyao/Hotel-Booking-Analysis/assets/63389925/16bb18fc-f632-4de3-b77e-5be48bcf07bd">

We can see how the number of bookings per year, month and day. The bookings steadily increased from 2013 - 2016 and then dipped in 2017. They also decrease from January to June then the number of bookings increase slowly from July.

<img width="859" alt="image" src="https://github.com/isaacmunyao/Hotel-Booking-Analysis/assets/63389925/da4b5b7e-6d8f-4220-aa3f-6fc5524f25fc">

The lead time across various distribution channel differs, however, we it ranges from between 0 to 100 days except from corporate and undefined distribution channels where the lead time is much shorter.

## Customer Behavior Analysis:
- Which distribution channels contribute the most to bookings, and how does the average daily rate (ADR) differ across these channels

<img width="455" alt="image" src="https://github.com/isaacmunyao/Hotel-Booking-Analysis/assets/63389925/664ff5ab-4573-4447-8275-efdb9277b920">

- Online travel bookings generate 62% of bookings, Offline travel bookings comes second with 20%, Undefined doesn't contiribute to any significant number of bookings.

- Can we identify any patterns in the distribution of guests based on their country of origin, and how does this impact revenue?
-  We have 174 different countries in the dataset. We analysed the top 10 counties contributing majority of bookings.

<img width="828" alt="image" src="https://github.com/isaacmunyao/Hotel-Booking-Analysis/assets/63389925/7c6dd9d7-c3a9-4ef3-877f-a2852b9ac2ff">

- Portugal Contributes significantly to the number of bookings as shown in the bubble plot.

# Summary

- More of the analysis process can be found in the notebook.

## Other Findings
- Transient customers from online travel agents contribute most to revenue loss.
- Revenue increased when the number of booking increased from 2013 - 2016 then decreased in 2017.
- Transient customers bring the most revenue.
- On average guests spend 3 nights at the hotel.
- Sunday is the most checked-out day in both the hotel and resort.
- Presence of deposit type is correlated with revenue loss. Apart from non-refundable deposit type,other deposit types lead to revenue loss.

# Recommendations
- The hotel should focus more marketing efforts between Monday and Thursday, this is because guests majorly arrive on Friday.
- To reduce the risk of revenue, the hotel should insist on Non-refundable deposits.
- In terms of resource allocation, the hotel should ensure that they stock up on food, toiletries etc from Friday.
- The hotel receives most of their guests from Europe (Portugal, UK, France etc) and therefore they should focus their marketing efforts targeting Europeans.




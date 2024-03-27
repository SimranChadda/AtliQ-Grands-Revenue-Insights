# AtliQ-Grands-Revenue-Insights
To provide insights to the Revenue Team in the Hospitality Domain

**Domain:** Hospitality
**Function:** Revenue

**Introduction:** 
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. 

**Company Background:** 
AtliQ Grands own multiple five-star hotels across the following cities.

| City          | Category      | Property Name |
| ------------- | ------------- | ------------- |
| Delhi         | Luxury        |  AtliQ Grands |
|               |               |  AtliQ Blu    |
|               |               |  AtliQ Bay    |
| Content Cell  | Content Cell  |               |
| Content Cell  | Content Cell  |               |
| Content Cell  | Content Cell  |               |
| Content Cell  | Content Cell  |               |
| Content Cell  | Content Cell  |               |
| Content Cell  | Content Cell  |               |
| Content Cell  | Content Cell  |               |
| Content Cell  | Content Cell  |               |
| Content Cell  | Content Cell  |               |

**Problem Statement**
Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights. 

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

**Task**
* Create the metrics according to the metric list.
* Create a dashboard according to the mock-up provided by stakeholders.
* Create relevant insights that are not provided in the metric list/mock-up dashboard.

**Mockup Dashboard**


**Tools used**
* MS Power BI
* MS Excel
* Power BI Service

**Operations Performed**
* Data Gathering: For getting the data sources
* Power Query: For data cleaning and data transformation
* Data Modelling: For creating the relationship b/w dimension and fact tables
* Creating DAX Meausres: For creating measures/ calculated columns. Also, DAX are helpful to get most out of the data.
* Creating Visuals and Dashboarding
* Publishing Dashboard to Power BI Service

**Step-1 Data Gathering and inputting into power BI app**
Below is an overview of the dataset. It consists of three dimensions (dim) files and two fact files and the format for all the files is in .csv:


**Step-2 Power Query**
Transformed and Prepared the data to Check for the below following:

* Removing any extraneous columns, rows, or blanks
* Conversions of data types – text, numbers, and dates
* Columns can be split or merged.
* New computed columns or additional columns are being added.
* Data aggregation or summarization, among other things.

**Step-3 Data Modelling**
Data modeling plays a pivotal role and serves as the foundation for generating meaningful reports. 
The entire framework of visualizations is constructed upon a well-designed data model. Neglecting proper data modeling can have adverse effects on the overall performance of the generated reports.

In the context of this project, we have meticulously followed the Snowflake data modeling method. This approach involves structuring data into normalized forms, resulting in reduced redundancy and improved query performance. This methodology enhances the way we organize and process data, ensuring optimal results for our analysis.

Remember, a robust data model is the cornerstone of effective data analysis and reporting. By employing sound data modeling practices, we can confidently generate insightful visualizations that empower data-driven decision-making.

**Step-4 Business Terminology**
In the hotel industry, several key metrics are crucial for assessing performance and making informed decisions. Here's a brief explanation of some of these metrics:

* **ADR (Average Daily Rate):** ADR represents the average price charged for each room per day. It's calculated by dividing total room revenue by the number of rooms sold.
* **Average Rating:** This is an average score or rating given by guests based on their stay experience, often derived from guest reviews and surveys.
* **DBRN (Daily Booked Room Night):** This metric tells on average how many rooms are booked for a day considering a time period.
* **DSRN (Daily Sellable Room Night):** This metric tells on average how many rooms are ready to sell for a day considering a time period.
* **DURN (Daily Utilized Room Night):** This metric tells on average how many rooms are successfully utilized by customers for a day considering a time period.
* **Occupancy (%):** Occupancy percentage calculates the ratio of successful occupied rooms to total available rooms, a key performance indicator.
* **No Show Rate (%):** This metric reveals the percentage of guests who make reservations but fail to arrive at the hotel as scheduled.
* **Realisation (%) or % checked out bookings:** It is nothing but the successful "checked out" percentage of all bookings that happened.
* **Revenue:** Total revenue generated by the hotel, encompassing income from various sources like room bookings, dining services, and events.
* **RevPAR (Revenue per Available Room):** RevPAR represents the revenue generated per available room, whether or not they are occupied. RevPAR helps hotel measure their revenue-generating performance to accurately price rooms. RevPAR can help hotels measure themselves against other properties or brands.

These metrics play a vital role in hotel management, aiding in pricing optimization, resource allocation, and enhancing overall guest satisfaction. Understanding and monitoring these metrics are essential for a hotel's success.

**Dashboard**

**Insights**

**ADR Remains Stable**
Upon analyzing the dashboard, it's evident that the Average Daily Rate (ADR) for AtliQ Hotels has remained relatively stable over the given time frame. This stability in pricing indicates a consistent pricing strategy.

Notably, AtliQ Hotels currently do not employ dynamic pricing based on weekdays and weekends. This presents an opportunity to consider adjusting the pricing strategy. Dynamic pricing can help optimize revenue by offering different rates for weekdays and weekends, aligning pricing more closely with demand fluctuations.

This insight suggests that exploring dynamic pricing strategies could be a valuable initiative to consider, potentially leading to increased revenue and better revenue management.

**Overall Occupancy Rate**
The overall occupancy rate for AtliQ Grands' properties currently stands at a solid 57%. This figure reflects the percentage of available rooms that are being utilized by guests. A 57% occupancy rate indicates a substantial portion of rooms are booked, contributing positively to revenue.

Maintaining a healthy occupancy rate is crucial for optimizing revenue and resource management. This insight suggests that AtliQ Grands has been successful in attracting guests and efficiently filling available rooms.

As part of ongoing strategies, it may be worthwhile to explore avenues to further increase occupancy, especially during off-peak periods, to maximize revenue potential.

Overall, the 57% occupancy rate provides a foundational understanding of AtliQ Grands' performance and can serve as a basis for further revenue optimization efforts.

**Average Rating**
The average guest rating for AtliQ Grands' properties is a commendable 3.62. This rating, derived from guest reviews and surveys, reflects the overall satisfaction of guests who have experienced our hospitality.

A rating of 3.62 signifies a positive guest experience, with the majority of guests expressing satisfaction with their stays. Guest ratings are a vital indicator of our service quality and the guest experience we provide.

As we continue to prioritize guest satisfaction, it's important to maintain and improve upon this rating. By consistently delivering exceptional service, addressing guest feedback, and enhancing guest experiences, we can aim for even higher ratings in the future.

The 3.62 average rating underscores our commitment to offering outstanding hospitality and ensuring our guests have memorable stays.

**Top 5 and Botom 5 Performers- why**


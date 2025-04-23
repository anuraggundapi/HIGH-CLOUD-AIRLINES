# HIGH-CLOUD-AIRLINES

Business Overview:
➢ In the modern airline industry, data analytics serves as a vital tool for enhancing operational efficiency and driving profitability. High Cloud Airlines can utilize data-driven insights to better understand business performance across key areas. This empowers leadership to make informed decisions that result in:

• Higher Load Factor Efficiency
• Improved Passenger Satisfaction
• Strategic Resource Optimization
• Evidence-Based Decision Making

➢ Project Scope:
The objective of this project was to utilize data analytics to generate meaningful insights aimed at enhancing the efficiency and performance of High Cloud Airlines. The analysis focused on key performance indicators (KPIs) to gain in-depth knowledge in the following areas:

• How full the planes are (Load Factor)
• What passengers really want
• Which routes work best
• How smooth and efficient the operations are

➢ TOOLS USED:
✅ MICROSOFT EXCEL
✅ MICROSOFT POWER BI
✅ MySQL
✅ TABLEAU

➢HIGH-CLOUD-AIRLINES ANALYSIS KEY-INSIGHTS:

Load Factor in Airlines:
Load Factor is a key performance metric in the airline industry that measures how efficiently available seating capacity is being utilized. It represents the percentage of available seats that are filled with paying passengers.
Formula for Load Factor:
Load Factor(%)=(Revenue Passenger Kilometers (RPK)Available Seat Kilometers (ASK))×100\text{Load Factor} (\%) = \left( \frac{\text{Revenue Passenger Kilometers (RPK)}}{\text{Available Seat Kilometers (ASK)}} \right) \times 100Load Factor(%)=(Available Seat Kilometers (ASK)Revenue Passenger Kilometers (RPK))×100 
Where:
•	Revenue Passenger Kilometers (RPK) = Total revenue-generating passengers × Distance flown
•	Available Seat Kilometers (ASK) = Total available seats × Distance flown
Simplified Formula (if distance is not considered):
Load Factor(%)=(Revenue Passengers CarriedAvailable Seats)×100\text{Load Factor} (\%) = \left( \frac{\text{Revenue Passengers Carried}}{\text{Available Seats}} \right) \times 100Load Factor(%)=(Available SeatsRevenue Passengers Carried)×100 
Interpretation:
•	A higher load factor (e.g., 80% or more) indicates efficient capacity utilization and profitability.
•	A lower load factor (e.g., below 60%) suggests that many seats are flying empty, which could lead to revenue losses.
Example Calculation:
•	A flight has 180 available seats and carries 150 passengers.
•	Load Factor = 150180×100=83.3%\frac{150}{180} \times 100 = 83.3\%180150×100=83.3%
Why is Load Factor Important?
✅ Revenue Optimization – Higher load factors generally mean better financial performance.
✅ Operational Efficiency – Helps airlines adjust capacity and pricing strategies.
✅ Profitability Indicator – Low load factors might require route optimization or marketing efforts.

The High Cloud Airlines Analysis Dashboard presents key insights into airline operations, passenger trends, and aircraft performance. Here's a data storytelling analysis based on the visualized information:
________________________________________
1. Overall Airline Performance Overview
•	Total Flights: 1,549
•	Total Passengers: 187.03 million
•	Total Seats Available: 243.54 million
•	Total Aircraft Types in Operation: 380
•	Total Airtime: 279,715 K hours
This indicates that the airline has a large operational scale, handling millions of passengers while maintaining a diverse fleet.
________________________________________
2. Load Factor Analysis
•	By Date Type:
o	Weekdays Load Factor: 71.26%
o	Weekends Load Factor: 28.74%
📌 Insight: Flights are significantly busier on weekdays, likely due to business travel. The airline may consider offering weekend promotions to increase occupancy.
•	By Year (Calendar-Wise):
o	Highest load factor observed in 2013 (56.41%)
o	Previous years (2008-2012) fluctuated between 51.56% - 54.67%
📌 Insight: There is a slight growth trend, but optimizing seat utilization further could boost revenue.
•	By Carrier:
o	The highest load factor carriers include Sichuan Airlines (88.12%), Skyservice Airlines (88.12%), and Corsair (88.56%).
o	Some airlines have lower utilization (~82-85%), indicating an opportunity to improve scheduling efficiency.
📌 Insight: The most utilized carriers could be prioritized for expanding routes.
________________________________________
3. Route and Distance-Based Flight Distribution
•	Top Routes:
o	The busiest routes have 78-80 flights, indicating strong demand for specific city pairs.
o	Potential expansion could focus on increasing flights on high-demand routes.
•	Distance-Based Flights:
o	The highest number of flights are in the short-haul category (0-500 miles).
o	Ultra-long-haul flights (above 5,000 miles) are few in number, but may contribute significantly to revenue per flight.
📌 Insight: The airline might analyze pricing strategies for different flight distances to improve profitability.
________________________________________
4. Passenger Preferences & Carrier Performance
•	Top Airlines by Passenger Volume:
o	Southwest Airlines leads with over 3.4 million passengers, followed by Delta Airlines (2.88M) and US Airways (1.56M).
📌 Insight: Southwest’s dominance suggests that low-cost carriers are preferred. Introducing more budget-friendly options on high-traffic routes could improve market share.
________________________________________
Final Recommendations
✅ Increase weekend promotions to improve load factors.
✅ Optimize seat utilization through pricing strategies and dynamic scheduling.
✅ Focus on high-demand routes while evaluating underutilized ones.
✅ Strengthen partnerships with top-performing carriers to maintain service quality.
✅ Enhance marketing efforts for long-haul flights to maximize profitability.
________________________________________
Profitability Indicator – Low load factors might require route optimization or marketing efforts. means what?
Profitability Indicator – Impact of Low Load Factor on Airlines
A low load factor means that a significant number of seats on flights are empty, which reduces revenue while the airline still incurs fixed costs like fuel, crew salaries, and maintenance. To improve profitability, airlines need to optimize routes and enhance marketing efforts. Here's how:
________________________________________
1️⃣ Route Optimization ✈️
If certain routes consistently have a low load factor, airlines can:
✅ Reduce flight frequency – Fewer flights on low-demand routes to minimize losses.
✅ Change aircraft type – Use smaller aircraft to match demand and reduce operational costs.
✅ Adjust schedules – Reschedule flights to more convenient times when demand is higher.
✅ Discontinue unprofitable routes – Shift focus to more profitable destinations.
Example:
•	If flights between City A and City B have only a 50% load factor, the airline might cut down daily flights or use a smaller aircraft.
________________________________________
2️⃣ Marketing & Pricing Strategies 🎯
To increase demand on routes with low load factors, airlines can:
✅ Offer promotions & discounts – Attract more passengers by lowering ticket prices.
✅ Loyalty programs & rewards – Encourage frequent travel with incentives.
✅ Dynamic pricing – Adjust ticket prices based on demand trends.
✅ Targeted advertising – Promote routes with low bookings through digital marketing.
Example:
•	A flight with only 60% seat occupancy on weekends could introduce "Weekend Saver Deals" to boost passenger numbers.
________________________________________
Bottom Line 💡
A low load factor means an airline is not fully utilizing its resources, leading to higher costs per passenger. By optimizing routes and implementing marketing strategies, airlines can increase profitability while improving efficiency.

➢ KPIs:
1) calcuate the following fields from the Year Month (#) Day fields ( First Create a Date Field from Year , Month , Day fields) 
A) Year
B) Monthno
C) Monthfullname
D) Quarter(Q1,Q2,Q3,Q4) 
E) YearMonth ( YYYY-MMM) 
F) Weekdayno 
G) Weekdayname
H) FinancialMOnth
I) Financial Quarter
3) Find the load Factor percentage on a yearly , Quarterly , Monthly basis ( Transported passengers / Available seats) 
4) Find the load Factor percentage on a Carrier Name basis ( Transported passengers / Available seats)
5) Identify Top 10 Carrier Names based passengers preference 
6) Display top Routes ( from-to City) based on Number of Flights
7) Identify the how much load factor is occupied on Weekend vs Weekdays. 
8) Identify number of flights based on Distance group

➤ Created a Dashboard for all above KPI to support our Analysis and also Used the filter to provide a search capability to find the flights between Source Country, Source State, Source City to Destination Country , Destination State, Destination City.









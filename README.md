**Project Overview**:
The Airline Passenger Satisfaction Analytics Dashboard is a two-page interactive Looker Studio dashboard designed to analyze passenger satisfaction, service quality, travel characteristics, flight distance, and operational delays.

The first page provides an overall passenger satisfaction overview using KPI cards and segmentation charts. The second page performs deeper analysis using calculated fields for satisfaction rate, age groups, delay categories, and service quality scoring.

The dashboard contains **103,904 passenger records**, with an overall satisfaction rate of **43.33%**, an average flight distance of **1,189.45**, and an average departure delay of **14.82 minutes**. :contentReference[oaicite:22]{index=22}

Objectives:
- Measure overall passenger satisfaction.
- Compare satisfaction across travel classes.
- Analyze satisfaction by travel type and customer type.
- Evaluate service-quality ratings for satisfied and dissatisfied passengers.
- Examine the relationship between departure delays and satisfaction.
- Analyze satisfaction across different age groups.
- Create delay categories for deeper operational analysis.
- Calculate an overall service quality score.
- Build interactive filters for passenger segmentation.

Tools Used:
- Looker Studio
- Google Sheets
- Airline Passenger Satisfaction Dataset
- Calculated Fields
- Interactive Filters
- Data Visualization

Process:
1. Imported the airline passenger satisfaction dataset into Google Sheets.
2. Connected the dataset to Looker Studio.
3. Created KPI cards for total passengers, satisfaction rate, average flight distance, and average departure delay.
4. Built satisfaction analysis by class, travel type, and customer type.
5. Compared service-quality ratings between satisfied and neutral/dissatisfied passengers.
6. Analyzed average departure delay by satisfaction status.
7. Created calculated fields:
   - Satisfaction Flag
   - Satisfaction Rate
   - Age Group
   - Delay Category
   - Service Quality Score
8. Built advanced satisfaction analysis by age group and delay category.
9. Created a service quality comparison by travel class.
10. Created a class-performance summary table containing satisfaction rate, service quality score, average flight distance, and average departure delay.
11. Added interactive filters for Class, Customer Type, Type of Travel, Gender, and Delay Category.
12. Added navigation between the two dashboard pages.

Key Insights:
- The dataset contains **103,904 passengers**, with an overall satisfaction rate of **43.33%**. :contentReference[oaicite:23]{index=23}
- **Business Class** has a substantially higher satisfaction rate than both Eco Plus and Eco. The class performance table shows approximately **69.43%** satisfaction for Business, compared with **24.61%** for Eco Plus and **18.61%** for Eco. :contentReference[oaicite:24]{index=24}
- Business travel passengers show a much higher satisfaction level than Personal Travel passengers. The dashboard illustrates a strong difference between the two travel types. :contentReference[oaicite:25]{index=25}
- Loyal Customers show a substantially higher satisfied share than disloyal customers. :contentReference[oaicite:26]{index=26}
- Service-quality ratings are consistently higher among satisfied passengers. Seat comfort is approximately **3.97 vs 3.04**, Online Boarding **4.03 vs 2.66**, and Cleanliness **3.74 vs 2.94** for satisfied versus neutral/dissatisfied passengers. :contentReference[oaicite:27]{index=27}
- Average departure delay is higher for neutral/dissatisfied passengers (**16.5 minutes**) than for satisfied passengers (**12.61 minutes**). :contentReference[oaicite:28]{index=28}
- Satisfaction varies considerably across age groups. The advanced analysis shows the highest satisfaction rate among passengers aged **46–60 at 57.41%**, followed by **36–45 at 51.98%**, while passengers under 18 have the lowest rate at **16.39%**. :contentReference[oaicite:29]{index=29}
- Satisfaction declines as departure delays move into more severe categories in the dashboard. The satisfaction rate is **45.75% for passengers with no delay** and falls to **35.74% for the severe-delay category**. :contentReference[oaicite:30]{index=30}
- The class-performance summary shows Business Class combining the highest satisfaction rate with the highest service-quality score and longest average flight distance among the three classes. :contentReference[oaicite:31]{index=31}

Dashboard Pages:
Page 1 — Passenger Satisfaction Overview
Provides a high-level view of passenger volume, satisfaction rate, average flight distance, departure delays, class-level satisfaction, customer type, travel type, and service-quality ratings.

Page 2 — Advanced Satisfaction Analysis
Uses calculated fields and segmentation to analyze satisfaction by age group and delay severity, along with class-level service quality and operational performance.

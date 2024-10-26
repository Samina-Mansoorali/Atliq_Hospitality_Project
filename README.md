# Project Background

Atliq Grands, a luxury hotel chain with a 20-year legacy in India, is facing increasing competition and a decline in business. Poor decision-making and a lack of strategic planning have contributed to a loss in market share and revenue. To address these challenges, the managing director has initiated a data-driven analysis to uncover insights and guide the chain back to success.

This project thoroughly analyzes key performance metrics to uncover critical insights that will improve Atliq Grands' success. 

Insights and recommendations are provided on the following key areas:

**Revenue Analysis:** An evaluation of revenue trends to identify opportunities for growth and optimize pricing strategies.

**Booking Analysis:** A study of booking patterns to understand peak seasons, customer preferences, and ways to increase occupancy rates.

**Cancellation Analysis:** Identifying causes of cancellations and reducing their impact.

An interactive Power BI dashboard can be downloaded [here](/Atliq%20hospitality%20analysis.pbix) 

# Data structures

Atliq grands dataset consist of five tables: fact bookings, dimension hotel, dimension room, fact aggregated bookings, dimension date.

![atliq data model](/Atliq%20data%20model.png)

## Executive Summary: (May - July 2022 Performance)

**Overview of Findings**

By May 2022, the numbers weren’t looking good. Revenue had dropped, occupancy rates were lower than expected, and the hotel chain was losing money instead of making a profit. Each week’s revenue showed wild ups and downs, leaving Atliq Grands in an unstable position.

By reviewing the performance metrics from May to July 2022, we found the following insights:

Total Revenue was ₹1.71 billion, but the hotel still faced a -28.85% profit margin, meaning they were spending more than they were earning.
The occupancy rate was 57.87%, much lower than what’s typical for a five-star hotel.
Even though the Average Daily Rate (ADR)—the amount guests were paying per room—was ₹12.70k, the Revenue Per Available Room (RevPAR) was just ₹7.35k, which showed that too many rooms were sitting empty.

These figures reveal several areas of concern. The occupancy rate is below the industry standard for five-star hotels, and the negative profit margin indicates inefficiencies in operations or pricing. Revenue instability across weeks further highlights the hotel's struggles.


### Revenue Insights

- Atliq Grands earns most of its money from luxury hotels. They made ₹1.05 billion from luxury hotels, which is 61.61% of all their revenue. Business hotels brought in ₹0.66 billion which is 38.39%.

- Most money comes in during the weekdays, with ₹1.18 billion (69.34%) earned then, compared to ₹0.52 billion (30.66%) on weekends. This means weekends, which are usually busy for hotels, are not performing as well as expected.

- By city, Mumbai is the top earner, bringing in ₹669 million. Other cities like Bangalore (₹420 million), Hyderabad (₹325 million), and Delhi (₹295 million) follow. This shows that Mumbai is very important for Atliq Grands' business.

- Looking at booking platforms, "Others" (lesser-known services) brought in the most revenue at ₹0.70 billion. This is more than well-known platforms like MakeMyTrip (₹0.34 billion) and LogTrip (₹0.19 billion). Direct online bookings made ₹0.17 billion, and offline bookings made ₹0.09 billion. Relying heavily on lesser-known platforms could be risky.

- In terms of hotel properties, Atliq Exotica made the most money, earning ₹0.32 billion. In contrast, Atliq Seasons earned only ₹0.07 billion, indicating a need for improvement there.

- When looking at room types, elite rooms made the most money at ₹0.56 billion, followed by premium rooms (₹0.46 billion) and presidential rooms (₹0.38 billion). Standard rooms earned ₹0.31 billion, showing there are opportunities to market higher-end rooms more effectively.

![Revenue analysis dashboard](/Revenue_analysis.png)

### Booking Insights

- Looking at bookings by week, there were big drops in later weeks. For example, in week 32, there were only 1.6k bookings, down from over 10k in earlier weeks like week 19. This inconsistency shows a struggle to keep demand steady.

- By property, Atliq Palace had the most bookings with 23.6k, closely followed by Atliq Exotica (23.4k). Atliq Seasons, however, only had 3.9k bookings, indicating it needs more attention.

- In total, there were 84k luxury bookings compared to 51k business bookings, showing that luxury options are more popular.

- Looking at booking platforms, "Others" accounted for 40.91% of all bookings, while MakeMyTrip had 19.99%, and LogTrip had 10.96%. These percentages suggest Atliq Grands needs to strengthen partnerships with more popular platforms to increase bookings.

- There were also inconsistencies in bookings for luxury and business categories. For instance, in week 19, luxury bookings were 6.8k, but by week 32, they dropped to 1k. Business bookings fell from 4.1k to 0.6k in the same period, highlighting a need for better promotional efforts.

![Booking analysis dashboard](/Booking_analysis.png)

### Cancellations and Occupancy Insights

- Cancellations are a big problem for Atliq Grands, with about 25% of all bookings being canceled. Mumbai has the highest cancellation rate at 24.75%, followed by Bangalore (24.99%), Hyderabad (24.63%), and Delhi (25.06%). High cancellation rates hurt both revenue and occupancy.

- Looking at cancellations by platform, "Others" led with 40.99%, followed by MakeYourTrip (20.11%) and LogTrip (10.73%). Cancellations are also common in luxury bookings, with 20.7k cancellations, compared to 12.7k in business bookings.

- Occupancy rates vary by property. Atliq Blu has the highest occupancy at 62.02%, while Atliq Seasons struggles with just 44.62%. Low occupancy, especially at Atliq Seasons and Atliq Grands, suggests that targeted strategies are needed to fill more rooms.

- A significant issue is the high no-show rates, particularly at Atliq Blu (5.30%) and Atliq Bay (5.19%). This indicates a need for stricter no-show policies or reminders to guests before check-in.

![Cancellation analysis dashboard](/Cancellation_analysis.png)

## Recommendations

- Strengthen partnerships with booking platforms by increasing visibility on sites like MakeMyTrip and LogTrip, using exclusive deals and promotions to boost bookings and revenue.

- Boost weekend bookings with targeted promotions, themed events, and marketing through social media and influencers to attract more weekend guests.

- Lower cancellation rates by offering non-refundable booking options and loyalty rewards to encourage booking commitment.

- Improve profit margins by reviewing costs and pricing, particularly for properties like Atliq Seasons, while optimizing staffing and operational efficiency to address negative margins.

- Draw more business travelers by offering corporate packages, extended-stay discounts, and business amenities like conference spaces.

- Minimize no-show issues with reminders, stricter policies, and slight overbooking to reduce the impact of missed bookings.
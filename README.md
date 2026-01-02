# Airbnb Market and Listings Evaluation for a Real Estate Company in France

This project analyzes Airbnb listing and booking data across major French cities to evaluate real estate investment performance.
By combining city-level demand patterns with listing-level revenue and occupancy metrics, the project identifies key drivers of profitability and risk.
The analysis delivers data-driven insights to support strategic Airbnb investment, pricing, and operational decisions..

## Business Problem ❓

 A real estate company that  owns residential properties across multiple major French cities is planning to enter the Airbnb short-term rental market. While the company possesses the properties, it still needs to invest to make the properties liveable, it also lacks visibility into which cities, property types, and operational strategies will generate the most profitable and sustainable returns when listed on Airbnb.

Entering the Airbnb market involves more than listing properties—it requires understanding city-specific demand dynamics, seasonality, occupancy behavior, pricing potential, and operational constraints such as blocked days and booking lead times. A city with high annual revenue may expose the company to seasonal risk, while another city with lower headline revenue may offer stable, predictable cash flows.

Without a data-driven evaluation, the company risks:
* Deploying properties in high-risk, highly seasonal markets
* 	Mispricing listings during peak and off-peak periods
* 	Underutilizing inventory due to inefficient blocked-day management
* Overestimating the impact of host scale instead of focusing on listing quality

This project addresses these challenges by providing an analytics-based framework to assess Airbnb market readiness, identify revenue drivers, and guide the optimal deployment of the company’s existing property portfolio.


## Project Objectives 🎯

* Evaluate Airbnb market performance across major French cities to determine where existing properties should be prioritized for Airbnb conversion.
* Analyze city-level demand, revenue potential, and seasonality to distinguish between high growth markets and stable, low risk markets.
* Identify listing-level revenue drivers, including room type, booking lead time, average length of stay, review volume, and occupancy behavior.
* Assess the relationship between revenue, occupancy, and demand concentration to understand risk exposure across cities.
* Quantify the impact of blocked days on unrealized revenue and estimate potential revenue gains through operational optimization.
* Evaluate whether host scale (number of listings) materially impacts revenue or whether performance is driven by listing-specific characteristics.
* Classify cities into high-seasonality, high-stability, and opportunity markets to support differentiated market entry and pricing strategies.
* Deliver actionable business insights using an end-to-end analytics workflow with Python, SQL, and Tableau, demonstrating data-driven decision-making for Airbnb market entry.


## Tools Used 🛠️

* Python: Data cleaning (Pandas), handling missing values and outliners, and Exploratory Data Analysis (EDA).

* SQL: Data extraction, joining 5+ tables, and calculating the business insights.

* Tableau: Interactive dashboarding to visualize regional performance and customer behaviour.

<img width="1470" height="956" alt="Python" src="https://github.com/user-attachments/assets/f81dca1a-05d9-4717-8d7e-8eb62f843694" />
<img width="1470" height="956" alt="SQL" src="https://github.com/user-attachments/assets/0f6f6ce3-5902-417b-a00c-5bbf32707113" />

## Key Insights 📊

*  Entire Home Listings Are the Primary Revenue Driver

    Entire home/apartment listings consistently outperform private rooms in terms of revenue contribution, as guests tend to book longer stays and show a stronger willingness to pay for privacy and space. Private rooms generate lower nights stayed and contribute marginally to overall revenue.



*  Revenue Leadership Is City-Driven, Not Occupancy-Driven

    Paris generates the highest revenue per listing, followed by Nice, Antibes, and Lyon. However, higher city revenue does not necessarily translate into higher occupancy—highlighting the importance of pricing power and demand intensity, not just booking frequency.


* Occupancy Patterns Vary Significantly by City
    * Nice records the highest average occupancy rate, followed by Lyon and Paris.
	* Lyon demonstrates stable, high occupancy throughout the year, making it the most reliable city for predictable and healthy cash flows.
	* Paris shows strong seasonality, with April–July contributing a majority of annual revenue.
	* 	Nice peaks from May–September, while Antibes sees massive revenue spikes in July and August, exceeding €1.2–1.3 million per month.



* Luxury Does Not Guarantee Maximum Revenue

    While the top 10 revenue-generating listings are ultra-luxury, high revenue is not exclusive to premium properties. Several listings outside the top 10 generate €50,000–€60,000+ annually, indicating that optimal pricing, demand, and reviews can outperform luxury alone.



* Booking Lead Time and Reviews Are Strong Predictors of Performance

    Listings with longer booking lead times tend to have:
    * 	Higher occupancy rates
    * 	More reviews
    * 	Stronger brand recall and guest trust

These listings are typically well-established, frequently booked, and consistently high-revenue performers.



* Host Scale Has Limited Impact on Revenue

Analysis shows no strong correlation between the number of listings owned by a host and total revenue. Revenue performance is listing-specific, driven more by location, demand timing, and operational efficiency than by portfolio size.



7. Blocked Days Represent a Major Revenue Leakage

If blocked days were optimized using average occupancy and booking rates, potential revenue could increase by €2,600 per listing annually. This represents a significant missed opportunity. However, blocked days can be strategically repurposed for maintenance, deep cleaning, or renovations to protect long-term asset quality.



8. Demand Is Seasonal but Operationally Healthy

Month-on-month growth appears inconsistent at an aggregate level due to mid-year demand concentration, which is a structural market characteristic, not a performance issue. Demand peaks are predictable and city-specific, allowing for planned pricing and capacity strategies.


## Recommendations 📌

* Market Entry Recommendation

    The company should prioritize Airbnb market entry in Lyon and Paris to balance stable cash flows with high revenue potential, followed by Nice for seasonal demand, while adopting a selective summer-only strategy for Antibes and deferring entry into Cannes, Bordeaux, Marseille.


* Prioritize Entire-Home Inventory Expansion

    Platforms and hosts should focus on acquiring and optimizing entire-home listings, especially in high-demand cities, as they offer higher revenue stability and longer stays compared to private rooms.



* Adopt City-Specific Pricing and Demand Strategies
    * Use dynamic pricing in Paris, Nice, and Antibes during peak months.
    *   Maintain steady pricing and promotional consistency in Lyon to preserve cash flow stability.
    A one-size-fits-all pricing model results in lost revenue potential.



*  Reduce Blocked Days Through Smarter Scheduling

    Optimize blocked days by:
    * Shortening unnecessary closures
    * Scheduling maintenance during low-demand periods
        
    This alone can unlock €2,000–€3,000 incremental revenue per listing annually.



* Invest in Review Growth and Early Booking Incentives

    Encourage early bookings via discounts or flexible cancellation policies. More  reviews and longer lead times directly correlate with higher occupancy and revenue predictability.



* Standardize Essential Amenities Across Listings

    Listings offering complete basic amenities (Wi-Fi, heating, kitchen, hot water, essentials, appliances, and cooking basics) perform significantly better. Standardizing amenities improves guest satisfaction, ratings, and repeat bookings.



* Target High-Season Marketing by City

    Align marketing spend with city-level demand peaks:
    * Paris: Apr–Jul
    * Nice: May–Sep
    * Antibes: Jul–Aug
    This ensures maximum ROI on promotional efforts.

<img width="1470" height="956" alt="Tableau" src="https://github.com/user-attachments/assets/05fc543d-dde4-45b1-a7a5-b2f13c84efc9" />



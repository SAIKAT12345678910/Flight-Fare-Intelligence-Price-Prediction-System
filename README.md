# Flight-Fare-Intelligence-Price-Prediction-System

🎯 Project Objective

To analyze airline ticket pricing patterns, identify key factors influencing fares, and build a machine learning model to accurately predict flight ticket prices.

📊 Dataset Overview

Large flight dataset with multiple routes and airlines
Features: Airline, Class, Stops, Duration, Source, Destination, Days Left, Departure Time, Arrival Time, Price etc.
🚀 Key Business Insights

🛫 Pricing Behavior

There is no fixed price trend for any single route, since fares depend on multiple factors such as travel class, number of stops, airline, time of travel, and demand.
Late-night flights are generally the cheapest, as demand is lower.
Evening flights tend to be the most expensive, likely due to peak travel demand.

⏰ Arrival & Departure Analysis

Most flights depart in the early morning and evening, while most arrivals happen at night, indicating passenger preference for morning departures and night arrivals.
Night & Morning arrivals show higher prices with several outliers, mainly due to premium or business-class tickets.
Late-night & Early-morning arrivals show lower prices, although some high-priced outliers exist due to last-minute bookings or premium class.

✈️ Airline Insights:

Vistara dominates most routes and maintains premium pricing.
AirAsia is the cheapest airline on most routes, but sometimes other airlines may offer competitive prices.
Top 3 Cheapest Airlines:
AirAsia → Indigo → GoFirst
Most Expensive Airlines:
Vistara → Air India
Airline Flight Frequency:
Vistara → Air India → Indigo
Fastest Flights: Indigo, GoFirst & AirAsia

🏷️ Class & Price:

Economy class remains consistently cheaper.
Business class fares are significantly higher, especially for Air India and Vistara.

🕒 Days Left Impact:

There is a huge price difference based on booking time.
More days left → Lower price
Fewer days left → Price increases significantly

🚏 Stops & Duration:

Zero-stop flights usually have lower prices.
Two or more stops significantly increase price.
Flight duration has weak correlation with price — longer flights are not always more expensive.

📈 Statistical & Regression Findings:

(From regression coefficients – simple language)
2+ stops increase price by ≈ ₹2555 compared to 1 stop.
Non-stop flights reduce price by ≈ ₹7837.
Economy class is ≈ ₹45,990 cheaper than Business class.
Compared to AirAsia:
Air India costs ~₹152 more
GoFirst costs ~₹1748 more
Indigo costs ~₹2376 more
SpiceJet costs ~₹2728 more
Vistara costs ~₹4179 more
Every 1 extra day before travel reduces fare by ≈ ₹131
Every 1 unit increase in duration increases fare slightly (~₹54)
👉 All p-values statistically significant → results are reliable.

🤖 Machine Learning Model:

Linear Regression → MAPE: ~36.40%
(Not suitable as data is highly non-linear)

Decision Tree Tested

Random Forest Performed Best → MAPE ~4% 

👉 Indicates strong model performance & excellent prediction capability.

🏢 Real-World Business Impact

✔ Helps airlines in revenue optimization and dynamic pricing

✔ Helps customers identify best time to book

✔ Useful for travel companies and ticket platforms

✔ Shows understanding of real airline pricing systems

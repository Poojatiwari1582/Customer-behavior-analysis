Customer Behaviour Analysis using Python (5 Lakh E-Commerce Events)

This project analyzes 5 lakh+ e-commerce user events (views, cart additions, purchases) to understand customer behaviour and identify why conversions are low despite high user traffic.
Using Python, Pandas, NumPy and Seaborn, the analysis highlights user intent, drop-off patterns, popular categories/brands, pricing preferences, and peak activity hours.

⭐ Project Objectives

Understand how users interact with an e-commerce platform

Identify high-traffic but low-conversion categories

Analyze brand performance and trust behaviour

Study user activity patterns across time

Detect funnel drop-offs (where customers drop interest)

Provide insights to improve conversions and marketing strategy

🛠 Tools & Libraries Used

Python 3.12

Pandas (data cleaning & analysis)

NumPy (numeric operations)

Seaborn & Matplotlib (visualizations)

Jupyter Notebook / VS Code

📁 Dataset Overview

The dataset contains 500,000 rows sampled from November 2019 (event-level e-commerce data):

Column	Description
event_time	Timestamp of user action
event_type	view / cart / purchase
product_id	Unique product identifier
category_id	Product category ID
category_code	Product category
brand	Product brand
price	Product price
user_id	Unique user identifier
user_session	Unique session ID
🔍 Key Analyses Performed
✅ 1. Funnel Analysis (View → Cart → Purchase)

View events: 482,153

Cart events: 8,283

Purchase events: 9,563

➡ 98.35% drop-off from view to cart
➡ Low conversion explains poor sales despite high traffic

✅ 2. Category Performance Analysis

Highest drop-off categories (0% conversion):

accessories.umbrella

accessories.wallet

apparel.belt

apparel.costume

apparel.jeans

High-conversion categories:

electronics.camera.photo

electronics.smartphone

auto.accessories.radar

appliances.ironing_board

✅ 3. Brand Performance Analysis

Top engaged brands:

Samsung

Apple

Xiaomi

Highest drop-off brands (0% conversion):

willmark

turboair

ubisoft

umi

unit

✅ 4. Price Preference Analysis

Users primarily interact with:

Low-priced products

Medium-priced products

High-priced items have lower user engagement.

✅ 5. User Activity Pattern (Hourly Analysis)

Peak user activity occurs between:
⏰ 4 AM – 8 AM

Useful for:

Notification scheduling

Campaign timing

Server optimization

📈 Visualizations Included

Event distribution (View / Cart / Purchase)

Top categories & brands

Category-wise conversion rates

Price distribution

Hourly activity heatmap

Category vs Hour heatmap

Funnel visualization

💡 Key Insights

Platform has strong browsing activity but very poor conversion.

Apparel & accessory categories show highest drop-off.

Several brands get views but zero adds to cart → trust & listing issues.

Low–medium priced items dominate engagement.

User activity clusters early in the morning.

🚀 Business Impact

This analysis helps the business:

Improve low-performing product categories

Enhance product pages & brand listings

Offer better pricing/discount strategies

Focus marketing during peak activity hours

Reduce drop-offs at crucial funnel stages

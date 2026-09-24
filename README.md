What it is
A food delivery operations dataset — 5,000 individual orders placed between January and June 2026, across 10 Indian cities (Chennai, Coimbatore, Pune, Delhi, Mumbai, Bangalore, Kochi, Kolkata, Mysore, Hyderabad). Each row is one order with 20 fields: restaurant, cuisine, delivery partner, distance, delivery time vs. estimated time, order value, delivery fee, discount, payment mode, customer rating, order status, and basic customer demographics (gender, age).

What the dashboard shows
I turned that raw order log into an analytics dashboard covering:

Revenue & volume: ₹33.5L total revenue across 5,000 orders, ₹670 average order value, trended month by month
Reliability: a 10.6% cancellation rate, and only 22.9% of orders arriving at or before their estimated time — the biggest red flag in the data
Geography: which cities order most and generate the most revenue
Menu & restaurants: cuisine mix and the top 10 restaurants by order count (Haldiram's leads)
Delivery partners: average delivery time by fleet (Shadowfax is fastest, Blinkit Express slowest)
Customer behavior: payment mode split, rating distribution (surprisingly flat across 1–5 stars), peak ordering times (late night dominates), and weekday patterns

Likely purpose
This looks like an operations/analytics exercise for a food delivery platform — the kind of dataset used to spot where delivery SLAs are breaking down, which partners underperform, and where revenue is concentrated, so a team could act on it (e.g., renegotiate with slow partners, investigate the low on-time rate, or double down on high-revenue cities).

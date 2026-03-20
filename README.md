SmartShield – Income Protection for Delivery Partners

About the Project
In today’s fast-growing gig economy, delivery partners (like Swiggy, Zomato, Zepto workers) play a very important role. But one major issue they face is **loss of income due to external factors** like heavy rain, pollution, or sudden curfews.
Through this project, we are trying to build a **simple AI-based insurance system** that helps delivery workers get compensated when they are unable to work due to such conditions.

Target User (Persona)
We considered a typical delivery partner:
* Name: Ravi
* Works for: Swiggy
* Location: Vijayawada
* Problem: During heavy rain or high pollution days, he cannot deliver orders and loses his daily earnings
Our solution is designed mainly for users like him.

Our Idea
We are building a **parametric insurance platform**, where:
* The user pays a **small weekly premium**
* If a predefined condition (like heavy rain) occurs,
* The system automatically gives compensation (no need to manually apply for claims)

How the System Works
1. User signs up on the platform
2. Basic details like location and work type are collected
3. The system calculates a **weekly premium** based on risk
4. External data (like weather) is monitored
5. If a trigger condition is met (e.g., heavy rainfall),
6. Claim is automatically processed and payout is given

Weekly Premium Model
We are using a **weekly pricing system** because gig workers usually earn weekly.
Premium depends on:
* Area (high-risk or low-risk zone)
* Weather conditions
* Past disruption frequency

Example:
* Low risk area → ₹20/week
* Medium risk → ₹30–40/week
* High risk → ₹50/week

Parametric Triggers (Automatic Conditions)
Some example triggers we are considering:
* Rainfall exceeds a certain limit
* AQI (pollution level) is very high
* Flood alerts in the area
* Government curfew
When these happen, the system directly triggers payout.

Use of AI/ML
We are planning to use basic AI/ML for:
* Calculating risk and premium dynamically
* Predicting possible disruptions
* Detecting fraud (like fake claims or location mismatch)

Platform Choice
We are planning to build this as a **web application** because:
* Easy to access from any device
* No need to install
* Faster to develop within limited time

Tech Stack (Planned)
* Frontend: HTML, CSS, JavaScript
* Backend: Python (Flask)
* Database: SQLite / MongoDB
* APIs: Weather API (or simulated data)

Development Plan (Phase 1)
* Understanding problem and user needs
* Designing workflow
* Planning system architecture
* Setting up GitHub repository

Future Scope
In the next phases, we plan to:
* Build full working system
* Add automated claims and payouts
* Create dashboard for users and admin
* Improve AI models

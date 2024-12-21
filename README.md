# Duolingo Monetization & Revenue Insights using Tableau
## Project Overview
This project involves the analysis and visualization of user engagement and monetization patterns across different subscription tiers (Free, Super, MAX) and courses (English, Spanish, German, etc.) in the context of Duolingo. The goal is to uncover key insights into user behavior and revenue generation, to help make data-driven decisions to enhance user retention and maximize monetization strategies.

The analysis is presented through an interactive Tableau dashboard, which visualizes key metrics such as in-app purchases, active minutes, ad impressions, and course preferences. These insights help to identify high-value user segments and optimize revenue streams.

## Key Features
Subscription Tier Analysis: Breakdown of user behavior and revenue across Free, Super, and MAX subscription types.
In-App Purchase Revenue: Visualized data showing revenue contributions from different subscription tiers and courses.
Engagement Metrics: Weekly active minutes, learning streaks, and other user engagement metrics to identify retention patterns.
Course Preferences: Analysis of course preferences based on geographical region, identifying trends in language learning (e.g., non-English countries preferring English courses).
Monetization Insights: Understanding of how user behavior influences revenue generation, including ad impressions and in-app purchases

## Technologies Used
Python: Used to generate synthetic data for user behavior and monetization.
Tableau: Used for visualizing the data and creating an interactive dashboard.
Pandas & Numpy: For data manipulation and generating synthetic data.

## Dataset Overview
The synthetic dataset simulates user behavior and monetization data for 1000 users. It includes the following attributes:

UserID: Unique identifier for each user.
SubscriptionTier: Subscription type (Free, Basic, Premium).
InAppPurchases: Total revenue from in-app purchases in USD.
AdImpressions: Number of ads shown to the user.
LearningStreak: Number of consecutive days the user has used the app.
WeeklyActiveMinutes: Total time spent in the app per week.
Country: Country of the user.
Courses: Language course the user is enrolled in (e.g., English, Spanish, German, etc.).

## Insights & Findings
Revenue Breakdown: Free users generated $3081, Premium users $3436, and Max users $3713 in in-app purchase revenue. Despite higher revenue from paid users, Free users spent more time in the app on average.
Course Preferences: Spanish was the most popular course overall, with the highest revenue generation. Non-English users preferred learning English, while U.S. users showed a preference for Spanish.
Engagement Metrics: Free users exhibited higher weekly active minutes compared to Premium users, indicating potential areas to improve conversion rates for Free users.

## Dashboard
![Image Alt Text](images/your-image.png)

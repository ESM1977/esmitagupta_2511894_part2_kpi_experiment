# Task 1

## Problem Statement

"Should the company roll out the new onboarding campaign to all users, based on whether it significantly improves user conversion and early engagement without negatively affecting customer experience, revenue quality, or support burden?”

## Summary of the Business Problem
The company is evaluating whether to launch a new onboarding and activation campaign (Treatment) to all users instead of continuing with the current experience (Control).
The decision impacts new users, product and growth teams, revenue outcomes, and customer support operations.
The campaign is considered successful if it improves conversion to paid users and early engagement, supported by metrics like:

## Trial starts
- Onboarding completion
- Engagement score
- 30-day revenue 

### At the same time, the company must ensure there are no negative side effects, such as:

- Increased support tickets
- Higher refund rates
- Lower-quality revenue or engagement

### Before making a rollout decision, the company needs clear experimental evidence from the A/B test showing:

- Improvement in key success metrics
- No deterioration in guardrail metrics
- Consistent results across user segments


# Task 2

# North Star Metric Definition

## Selected North Star Metric
**Conversion to Paid Users (converted_to_paid)**

## Why this is the Main Success 
MetricConversion to paid users is the most critical metric because it directly reflects whether the onboarding experience successfully:- 
- Delivers value to users
- Moves users from exploration (free/trial) to commitment (paid)

The primary goal of the new onboarding campaign is to improve activation and monetization, and conversion to paid is the clearest, most direct measure of that success.   

## Why Other Metrics are Supporting Metrics
Other metrics are important but serve as leading indicators or diagnostics, not ultimate outcomes:- 
- Trial start rate (started_trial) : Indicates initial interest but not commitment
- Onboarding completion (completed_onboarding) : Shows usability and flow effectiveness but not business value
- Engagement score (engagement_score) : Reflects usage behavior but not revenue impact
- Revenue (revenue_30d) : Valuable but can be skewed by a small number of high-paying users

These metrics help explain *why* conversion changes, but they do not replace the core business outcome of paying users.   
---
## How This Metric Connects to Business Growth
Conversion to paid is directly tied to growth because:- 
- Revenue Growth : More paying users → higher total revenue
- Customer Acquisition Efficiency : Higher conversion reduces cost per acquisition (CAC)
-  Scalability : Improvement in conversion scales across all incoming users
-  Product-Market Fit Signal : Users are willing to pay → strong validation of product value

In short, improving conversion drives both top-line revenue and long-term business sustainability.   

---
## What Could Go Wrong if Optimized Blindly
Focusing only on conversion to paid can lead to unintended negative consequences:
### 1. Low-Quality Conversions
- Users may convert due to aggressive nudges but churn quickly
- Leads to weak long-term retention

### 2. Increased Refunds
- Users may feel misled or rushed into payment
- Higher refund_requested rates

### 3. Poor User Experience
- Over-optimized funnels may create friction or confusion
- Can increase support_tickets_30d

### 4. Reduced Engagement
- Users convert but do not actively use the product
- Lower engagement_score

### 5. Revenue Distortion
- Short-term gains in conversion but lower lifetime value (LTV)

---
## Final Summary
Conversion to paid is the best North Star metric because it directly measures business success and monetization impact.  However, it must be evaluated alongside supporting and guardrail metrics to ensure sustainable growth, high-quality users, and a positive customer experience.

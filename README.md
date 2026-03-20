# GigShield AI 
### AI-Powered Parametric Micro-Insurance for Gig Delivery Workers
---

## Overview

The income of food delivery partners who work with Swiggy and Zomato depends on their total number of delivered orders. Their pay is not set and changes every day according to demand and how many hours they can work. Environmental disruptions such as heavy rainfall, extreme heat, severe air pollution, and flooding create major impacts on delivery operations and staff work schedules.

The weekly income of delivery partners decreases by 20 to 30 percent during these disruptive events. The current insurance system lacks any specific protection for gig delivery workers who face income interruptions because of environmental factors.

The AI-powered parametric insurance platform known as GigShield AI provides financial protection to food delivery gig workers through its system. The system operates through automated environmental disruption detection. This activates compensation payments when specific predetermined conditions are met. Traditional insurance models require people to submit claims and perform verification tasks.

Employees enroll in a basic insurance plan, which charges them on a weekly basis to match their regular income schedule. The system determines revenue shortfalls and sends automated digital compensation payments to users when delivery operations stop because of disturbances.

## Problem Statement

Gig delivery workers experience significant income volatility because their compensation is dependent on the number of deliveries they make. Environmental disruptions such as:
*  Heavy rainfall
*  Heat waves
*  Severe air pollution
*  Flooding


Social Disruptions such as:

* Unplanned curfews
* Local strikes
* Sudden market/zone closures
can reduce delivery demand and make it more difficult for employees to complete deliveries.

Since gig workers are usually independent contractors, they frequently **do not receive income protection or insurance coverage**. Therefore, environmental disruptions have a direct effect on their financial stability.

## Proposed Solution

GigShield AI presents a **parametric micro-insurance model** designed specifically for gig delivery workers.

The platform continuously monitors environmental conditions using external data sources, such as weather and air quality services. When delivery activity decreases and disruption thresholds are reached, the system automatically calculates the estimated income loss and starts a payout.

To keep the system affordable, GigShield AI uses a **community micro-insurance pool model**. Employees who work in the same geographic delivery zone contribute a small weekly premium to a shared insurance pool. This pooled fund is then used to compensate workers who have verified income loss during disruptions.

By automating risk analysis, disruption detection, and payout processing, GigShield AI provides gig workers with **quick, transparent, and reliable income protection**.


## Community Micro-Insurance Pool 

To keep the system affordable and scalable, GigShield AI uses a community-based insurance pool model.
Delivery workers operating within the same 3–5 km geographic zone contribute a small weekly premium (₹30–₹50).These contributions form a shared pool
When a verified disruption occurs, payouts are made from this pool
This approach ensures:

* Low-cost participation

* Fair risk distribution

 ## Peak Hour Compensation Multiplier (NEW)

GigShield AI considers earning-sensitive time periods such as:

* Lunch hours
* Dinner peak hours

If a disruption occurs during these peak periods, the system applies a multiplier to the payout.
**Example:**
- Normal loss: ₹225
- Peak multiplier (×2): ₹450 payout
This ensures workers are compensated fairly when disruptions impact their highest earning windows.

## Key Features

### Prediction of AI Earnings

By examining past delivery data, weather forecasts, and demand trends, the system forecasts an employee's expected earnings for the upcoming day or week. This aids in estimating possible changes in income brought on by environmental disruptions.

### Plan Recommendation
The platform recommends the best insurance plan for each employee based on anticipated risk levels. Plans can differ in terms of coverage and premium levels, so employees can choose one that best suits their income and risk tolerance.

### Risk Alerts
When environmental disruptions like intense heat, heavy rain, or high pollution levels are likely to have an impact on delivery activity, GigShield AI sends out early warning notifications. These notifications assist employees in getting ready for a potential pay cut.

### Income Stability Score 
The platform offers a measure of an employee's earnings consistency over time. This score aids employees in determining their level of financial risk and selecting the right insurance plan.

## Automatic Premium Adjustment
Predicted risk levels are used to dynamically adjust insurance premiums. Premiums may drop during weeks when there is less chance of disruptions, making the system more accessible to employees.


## Machine Learning Models that we are using:

GigShield AI integrates multiple ML models to ensure accurate prediction and fair payouts:
* Random Forest → Environmental risk prediction

* XGBoost → Earnings prediction

* Gradient Boosting → Income loss estimation

* Prophet → Income stability analysis

* LightGBM → Insurance plan recommendation

* Bayesian Regression → Premium adjustment

* Isolation Forest → Fraud detection
##  AI Assistance (RAG + LLM)

GigShield AI integrates a **Generative AI assistant powered by RAG (Retrieval-Augmented Generation) and LLMs** to provide intelligent and explainable support to users.

###  Key Capabilities

- **Explain Decisions**  
  Provides clear explanations for payouts, rejections, and trust scores  

- **Fraud Awareness**  
  Helps users understand why certain activities are flagged as suspicious  

- **Personalized Insights**  
  Offers risk predictions and recommendations based on user behavior  

- **Plan Guidance**  
  Assists workers in selecting suitable insurance plans  

These models work together to provide a data-driven, automated insurance system.
## Adversarial Defense & Anti-Spoofing Strategy

To prevent GPS spoofing and coordinated fraud, our system uses a **multi-layered AI-driven detection framework** combining behavioral, contextual, and group-level analysis.

###  Key Signals

- **Movement Analysis**  
  Analyzes real-world movement patterns (pickup → transit → delivery)  
  Flags users with static or unrealistic mobility during active deliveries  

- **Delivery Validation**  
  Flags unrealistic delivery time or frequency  

- **Peer Comparison**  
  Identifies abnormal behavior within the same zone  

- **Group Fraud Detection**  
  Detects coordinated attacks (same location, time, patterns)  

- **Historical Analysis**  
  Flags sudden anomalies in user behavior  

- **Environmental Validation**  
  Cross-checks claims with real-world conditions (e.g., weather)  


###  Trust Score System

All signals are combined into a **dynamic Trust Score**:

-  **High Trust** → Approved  
-  **Medium Trust** → Flagged  
-  **Low Trust** → Rejected  



### Outcome

Ensures **accurate fraud detection**, prevents **mass spoofing attacks**, and maintains **fairness for genuine workers**.


## For Example:

Ramesh is a delivery worker who delivers food orders for about **₹4200 per week**.

After analyzing environmental data, the system forecasts:
* The likelihood of rain: **80%**
* Anticipated delivery decrease: **35%**
* Estimated weekly earnings: **₹2800**

In light of this forecast, the system suggests:
- Suggested Plan: Standard  
- Weekly Premium: ₹50  

The system automatically determines Ramesh's estimated income loss and transfers compensation via digital payment if environmental disruption takes place and delivery activity declines as anticipated.

##  Business Model

GigShield AI earns revenue through a **micro-insurance subscription model**:

* **Weekly Premiums:** Workers pay ₹30–₹50/week for insurance coverage
* **Platform Fee:** 5–10% commission from pooled contributions
* **Dynamic Pricing:** Premiums adjust based on risk (higher risk → slightly higher premium)
* **B2B Partnerships:** Collaborations with Swiggy, Zomato, and insurers
* **Data Insights (Future):** Sell analytics on delivery trends and climate impact

This ensures **affordable protection for workers** and **scalable revenue for the platform**.

## Advantages
* Offers gig delivery workers **financial protection**
* Makes use of **AI to forecast income disruptions**
* Uses **automated payouts** to do away with manual insurance claims
* Keeps insurance affordable through **community micro-insurance pooling**  
* Encourages gig economy workers to have stable incomes

## Target Users
* Food delivery partners using services like Zomato and Swiggy
* Gig workers who rely on delivery-based pay
* Employees in urban delivery zones who are impacted by environmental disturbances



## Contributors
Team InnovateX

# 🛵 AI-Powered Parametric Insurance Platform for Gig Delivery Workers

**Team:** Code_gapsy  
**Hackathon:** Guidewire DEVTrails 2026

---

## 📌 Introduction

Gig delivery workers form the backbone of today’s on-demand economy, working with platforms like Swiggy, Zomato, Amazon, and Zepto. Their income depends entirely on daily deliveries.

However, external disruptions such as heavy rain, floods, extreme heat, pollution, or curfews can suddenly stop their work. These events can reduce up to **20–30% of a worker’s monthly earnings**.

Currently, there is **no automated system** that protects gig workers from income loss during such uncontrollable situations.

---

## (1) 👤 Persona

* Food delivery rider working with platforms like Swiggy/Zomato
* Works 8–10 hours daily, mainly during lunch and dinner peak hours
* Earns approximately ₹700–₹1000 per day
* Operates in busy urban areas with unpredictable conditions
* Fully dependent on daily earnings for financial stability

---

## (2) 🚨 Problem Scenarios

Delivery riders frequently face income loss due to:

* Heavy rainfall → unable to deliver → loses ₹700–₹900
* Extreme heat (>42°C) → reduces working hours → loses ₹400–₹600
* Flooded roads → delivery demand drops
* High pollution (AQI > 300) → unsafe to work
* Platform/server downtime → no orders → zero income
* Sudden curfews → restricted delivery access

👉 These disruptions directly impact their livelihood.

---

## (3) 💡 Our Solution

We propose an **AI-powered parametric insurance platform** that provides automatic income protection.

* Weekly subscription-based insurance
* Real-time monitoring of environmental conditions using APIs
* Automatic detection of disruption events
* Instant payout without manual claim submission

🎯 Our goal is to ensure **financial stability and security for gig workers**.

---

## (4) ⚙️ System Workflow

1. Worker registers on the platform
2. Subscribes to a weekly insurance plan
3. AI calculates premium based on risk factors
4. System continuously monitors weather and environmental APIs
5. When disruption thresholds are exceeded, the system detects the event
6. Affected users are identified automatically
7. Claims are generated and verified instantly
8. Payout is processed through a simulated payment system

---

## (5) 💰 Weekly Premium Model

The platform operates on a **weekly subscription model**, aligned with gig workers' income cycle.

### 📊 Plans:

* Basic Plan
* Standard Plan
* Premium Plan

### 💡 Pricing Logic:

Premium = Base Price + (Risk Score × Location Factor)

* High-risk zones → higher premium
* Low-risk zones → lower premium
* AI dynamically adjusts pricing based on environmental risks

👉 Ensures fairness, affordability, and flexibility.

---

## (6) ⚡ Parametric Triggers

The system automatically detects disruptions using predefined triggers:

* Heavy rainfall above threshold
* Extreme temperature (>42°C)
* Severe air pollution (AQI > 300)
* Flood alerts
* Platform downtime > 2 hours
* Low order density (< 2 orders/hour)

👉 Once triggered, claims are processed automatically.

---

## (7) 🤖 AI/ML Integration

AI is a core component of the system:

* **Risk Prediction**

  * Calculates disruption probability using environmental data

* **Dynamic Pricing**

  * Adjusts weekly premiums using AI-based risk scoring

* **Fraud Detection**

  * Detects duplicate claims
  * Identifies GPS/location mismatches
  * Validates rider activity

---

## (8) 🛠️ Technology Stack

- **Frontend:** React.js  
- **Backend:** Node.js / Express  
- **Database:** PostgreSQL  
- **AI/ML:** Python (Scikit-learn)  
- **APIs:** Weather API, AQI API  

---

## (9) 🔮 Future Plan (Phase 2 & 3)

* User authentication and registration system
* Insurance policy management
* Automated claim processing system
* Instant payout integration (Razorpay / UPI sandbox)
* Dashboard:

  * Rider → earnings protected, coverage details
  * Admin → analytics, fraud insights, risk monitoring

---

## (10) 👨‍💼 Real User Scenario

### User: Ramesh (Food Delivery Rider)

* Works with Swiggy
* Works during evening peak hours
* Daily earnings: ₹800–₹1000

### 🚨 Situation:

On a Friday evening:

* Heavy rainfall started at 6 PM
* Roads became flooded
* Orders dropped drastically

👉 Earned only ₹250
👉 Lost around ₹600

### 💡 How Our System Helps:

* Ramesh subscribed to ₹50/week insurance plan
* System detected:

  * Rainfall above threshold
  * Peak-hour disruption

### ✅ Result:

1. Claim triggered automatically
2. AI verified conditions
3. ₹500 payout credited instantly

🎯 Outcome:

* Reduced financial loss
* Increased income stability
* Improved trust in the system

---

## (11) 🌟 Key Unique Features

### 🔹 Peak Hour Insurance

Coverage focused on high-income hours → better efficiency and lower premiums

### 🔹 Low Order Density Detection

Detects demand drop (< 2 orders/hour) as an income-loss trigger

### 🔹 Micro-Zone Risk Mapping

Different risk levels for different city zones → fair, location-based pricing

### 🔹 Smart Pause Detection

Validates that inactivity is due to real disruption → reduces fraud

### 🔹 Multi-Trigger Compensation

Higher payout when multiple disruptions occur together

---

## 🎯 Conclusion

Our platform provides **automated income protection for gig delivery workers**.

By combining:

* AI-driven risk prediction
* Parametric insurance
* Real-time environmental monitoring

we create a system that is:

* Simple
* Fast
* Reliable
* Worker-centric

👉 Our solution focuses on **predictive income protection**, helping gig workers stay financially stable even during unexpected disruptions.

---

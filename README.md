# PayGuard AI – Smart Income Protection for Gig Workers

### Protecting Delivery Workers from Income Loss using AI-powered Parametric Insurance

## 💡 Inspiration  

India’s delivery partners (Swiggy, Zomato, etc.) are the backbone of the digital economy. However, their income is highly unstable due to external disruptions like heavy rain, extreme heat, pollution, and sudden curfews. These disruptions can reduce their earnings by up to **20–30% monthly**.

Delivery workers are one of the most affected groups when there is a sudden change in weather. Due to unexpected conditions like heavy rain or extreme heat, they may not be able to work and can lose their entire income for that day.

At the same time, they still need to cover daily expenses such as fuel and vehicle maintenance. Since they depend on daily wages, even a single missed day can create financial stress.

A delivery worker earning ₹500/day can lose their entire income during such events. Despite this, there is **no effective financial safety net** to protect them.
 This inspired us to build PayGuard AI — a platform that ensures workers continue earning even when they cannot work.

# 2. Proposed Solution

WeatherShield is an **AI-powered parametric micro-insurance platform** that provides financial protection to delivery workers against income loss caused by external disruptions.
The system automatically monitors real-world conditions and provides **instant payouts** when predefined conditions are met — without requiring manual claims.

# 3. Target Persona

* Food Delivery Workers (Swiggy / Zomato)
* Workers dependent on daily delivery-based income
* Operate in outdoor environments affected by weather and external factors

# 4. System Workflow

1. User registers on the mobile application
2. User selects a weekly income protection plan
3. AI evaluates location-based risk and calculates premium
4. System continuously monitors external data (weather, pollution, etc.)
5. If disruption occurs (e.g., heavy rain), system triggers claim automatically
6. Fraud detection layer verifies authenticity
7. Instant payout is credited to the worker

# 5. Weekly Premium Model

Premium is calculated weekly based on risk level:

* Low Risk Area → ₹20/week
* Medium Risk Area → ₹30/week
* High Risk Area → ₹50/week

 Premium Formula:

Weekly Premium = Base Premium + Location Risk + Weather Risk − Safety Score

AI determines risk using:

* Historical weather data
* Area-specific disruption patterns
* User behavior

# 6. Parametric Triggers (Income Loss Events)

Payouts are triggered automatically when:

* Rainfall exceeds threshold
* Temperature exceeds 40°C
* AQI crosses hazardous level
* Curfew or area restriction occurs

 No manual claim process required

# 7. AI / ML Integration

7.1 Risk Assessment & Dynamic Pricing

AI models calculate risk score using:

* Location data
* Weather patterns
* Historical disruptions
* User activity

 7.2 Fraud Detection

AI detects fraud using:

* Behavioral pattern analysis
* Location verification (GPS + network data)
* Duplicate claim detection
* Weather-data correlation

 7.3 Predictive Risk Modeling

System predicts future risks using:

* Weather forecasts
* Environmental data
* Historical disruption patterns

# 8. Platform Choice

 Mobile Application

* Easy weekly subscription
* Real-time monitoring
* Push notifications

 Admin Dashboard

* Monitor claims
* Analyze fraud patterns
* View risk analytics

# 9. System Architecture

User App
↓
API Gateway
↓
Backend Server
↓
AI/ML Risk Engine
↓
Database
↓
Admin Dashboard

# 10. Tech Stack

 Frontend

* Flutter / React Native
* React.js (Admin Dashboard)

 Backend

* Node.js / Express.js / FastAPI

 Database

* PostgreSQL
* MongoDB

AI / ML

* Python
* Scikit-learn / TensorFlow

APIs

* Weather API
* Location API

 Cloud

* AWS / Google Cloud

# 11. Key Features

* Weekly subscription model
* Automated claim triggering
* Instant payout system
* AI-based risk calculation
* Advanced fraud detection and anti-spoofing protection

# 12.  Adversarial Defense & Anti-Spoofing Strategy (Market Crash)
 Fraud Scenario

A coordinated fraud attack where multiple fake users use GPS spoofing to trigger false claims and drain system funds.

 Defense Mechanisms

 1. Multi-Source Location Verification

* GPS + IP + device sensor validation
* Detect mismatched locations

 2. Movement Pattern Analysis

* Real users → continuous movement
* Fake users → abnormal jumps
* AI flags anomalies

 3. Weather Correlation Check

* Validate claims against real weather data
* Reject invalid claims

 4. Behavioral Analytics

* Detect mass claim patterns
* Identify fraud rings

5. Device Fingerprinting

* Track device ID
* Prevent multiple fake accounts

6. Risk Scoring System

* Assign fraud risk score
* High-risk users → delayed/manual verification

 7. Fairness Protection

* Genuine users not penalized
* Only suspicious cases flagged

Outcome

* Prevents large-scale fraud attacks
* Ensures system stability
* Protects genuine workers

# 13. Future Enhancements

* Integration with delivery platforms
* Personalized insurance plans
* Advanced AI prediction models
* Real-time disruption alerts

# 14. Conclusion

WeatherShield provides a **simple, automated, and reliable safety net** for delivery workers.
By combining AI with parametric insurance, the platform ensures **financial protection against income loss** while maintaining strong fraud prevention mechanisms.

 GitHub Repository
https://github.com/RajeshwariPothkam/AI-enabled-parametric-insurance-platform-?tab=readme-ov-file

 Demo Video
https://youtu.be/HNv8NOT7uUs?feature=shared

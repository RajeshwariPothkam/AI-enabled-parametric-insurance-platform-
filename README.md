# PayGuard AI – Smart Income Protection for Gig Workers

### Protecting Delivery Workers from Income Loss using AI-powered Parametric Insurance

##  Inspiration  

India’s delivery partners (Swiggy, Zomato, etc.) are the backbone of the digital economy. However, their income is highly unstable due to external disruptions like heavy rain, extreme heat, pollution, and sudden curfews. These disruptions can reduce their earnings by up to **20–30% monthly**.

Delivery workers are one of the most affected groups when there is a sudden change in weather. Due to unexpected conditions like heavy rain or extreme heat, they may not be able to work and can lose their entire income for that day.

At the same time, they still need to cover daily expenses such as fuel and vehicle maintenance. Since they depend on daily wages, even a single missed day can create financial stress.

A delivery worker earning ₹500/day can lose their entire income during such events. Despite this, there is **no effective financial safety net** to protect them.
 This inspired us to build PayGuard AI — a platform that ensures workers continue earning even when they cannot work.

##  Proposed Solution  

PayGuard AI is an **AI-powered parametric micro-insurance platform** that provides financial protection to delivery workers against income loss caused by external disruptions.

The system continuously monitors real-world conditions and automatically provides payouts when predefined conditions are met — eliminating the need for manual claims.

The platform strictly focuses on income protection and does not include health, accident, or vehicle insurance
---

## 👤 Target Persona  

PayGuard AI is designed for gig workers who rely on daily or weekly earnings, with an initial focus on delivery partners.

- Gig workers dependent on daily/weekly income  
- Delivery partners (Swiggy, Zomato, Rapido, etc.)  
- Workers operating in outdoor environments affected by weather and external disruptions  

 The platform is initially focused on delivery workers and can be expanded to other gig sectors in the future.
---

##  System Workflow  

User → AI Risk Analysis → Weekly Premium → Real-time Monitoring → Trigger Detection → Fraud Verification → Instant Payout  

### Step-by-step:

1. User registers on the mobile application  
2. Selects a weekly income protection plan  
3. AI evaluates location-based risk and calculates premium  
4. System continuously monitors external data (weather, pollution, etc.)  
5. If disruption occurs (e.g., heavy rain), claim is automatically triggered  
6. Fraud detection layer verifies authenticity  
7. Instant payout is credited to the worker  

---

##  Weekly Premium Model  

Premium is calculated weekly based on risk level:

- Low Risk Area → ₹20/week  
- Medium Risk Area → ₹30/week  
- High Risk Area → ₹50/week  

### Premium Formula:
Weekly Premium = Base Premium + Location Risk + Weather Risk − Safety Score  

### AI determines risk using:
- Historical weather data  
- Area-specific disruption patterns  
- User behavior  

---

##  Parametric Triggers (Income Loss Events)  

Payouts are triggered automatically when:

- Heavy rainfall exceeds predefined threshold  
- Official weather alerts (Red/Orange alerts) are issued  
- Severe weather conditions disrupt normal operations  
- Air Quality Index (AQI) reaches hazardous levels  
- Government-imposed curfews or area restrictions occur  

 Triggers are based on *high-impact disruption events*, not normal environmental conditions  

 No manual claim process required — fully automated system
---

## 🤖 AI / ML Integration  

### 1. Risk Assessment & Dynamic Pricing  
AI models calculate risk score using:
- Location data  
- Weather patterns  
- Historical disruptions  
- User activity  

### 2. Fraud Detection  
AI detects fraud using:
- Behavioral pattern analysis  
- Location verification (GPS + network data)  
- Duplicate claim detection  
- Weather-data correlation  

### 3. Predictive Risk Modeling  
System predicts future risks using:
- Weather forecasts  
- Environmental data  
- Historical disruption patterns  

---

## 🏗️ Platform Choice  

### 📱 Mobile Application  
- Easy weekly subscription  
- Real-time monitoring  
- Push notifications  

### 📊 Admin Dashboard  
- Monitor claims  
- Analyze fraud patterns  
- View risk analytics  

---

## 🛠️ System Architecture  

User App → API Gateway → Backend Server → AI/ML Risk Engine → Database → Admin Dashboard  

---

## 🧩 Tech Stack  

Frontend:
- Flutter / React Native  
- React.js (Admin Dashboard)

Backend:
- Node.js / Express.js / FastAPI  

Database:
- PostgreSQL / MongoDB  

AI / ML:
- Python  
- Scikit-learn / TensorFlow  

APIs:
- Weather API  
- Location API  

Cloud:
- AWS / Google Cloud  

---

##  Key Features  

- Weekly subscription model  
- Automated claim triggering  
- Instant payout system  
- AI-based risk calculation  
- Advanced fraud detection and anti-spoofing protection  

---

#  Adversarial Defense & Anti-Spoofing Strategy  

### 1. Differentiation (Real vs Fake Users)  
- Real users → continuous movement patterns  
- Fake users → abnormal jumps or static behavior  
- AI detects inconsistencies in movement and routes  

### 2. Data Used (Beyond GPS)  
- GPS + IP address validation  
- Device sensors (accelerometer, motion data)  
- Network latency and signal variations  
- Route validation using maps  
- Group behavior analysis to detect fraud rings  

### 3. UX Balance (Protecting Genuine Users)  
- Suspicious claims are flagged, not rejected instantly  
- Additional verification is triggered only when needed  
- Genuine users continue to receive fair service  

### Final Strategy  
- Risk scoring system assigns trust score to users  
- High-risk users → additional verification  
- Low-risk users → instant payout  

---

##  Future Enhancements  

- Integration with delivery platforms  
- Personalized insurance plans  
- Advanced AI prediction models  
- Real-time disruption alerts  

---

## 🏁 Conclusion  

PayGuard AI provides a simple, automated, and reliable safety net for delivery workers. By combining AI with parametric insurance, the platform ensures financial protection against income loss while maintaining strong fraud prevention mechanisms.

 GitHub Repository
https://github.com/RajeshwariPothkam/AI-enabled-parametric-insurance-platform-?tab=readme-ov-file

 Demo Video
https://youtu.be/HNv8NOT7uUs?feature=shared

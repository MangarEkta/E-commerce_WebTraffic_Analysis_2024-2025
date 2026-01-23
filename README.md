# E-commerce Web Traffic Analysis (2024–2025)

This repository contains a comprehensive data analysis of web traffic patterns for an e-commerce platform over the period **2024–2025**. 

The purpose of this analysis is to evaluate the performance of different web traffic channels, devices, and platforms for e-commerce business by understanding user engagement, conversion metric, and to identify areas for marketing.This analysis also aim to understand seasonal or time-
based performance trends to derive meaningful insights.

---

## 📌 Project Objective

The objective of this analysis:

**Channel Performance:** Determine which traffic sources (Organic, Paid, Social, Email) yield the highest conversion rates.

**Device Insights:** Analyze how user behavior differs between Mobile, Tablet, and Desktop users.

**Engagement Metrics:** Evaluate Bounce Rates and Session Durations to identify friction in the user journey.

**Seasonality:** Identify time-based trends to predict peak shopping periods.

This analysis is designed for stakeholders in digital marketing, product management, and business analytics teams.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `README.md` | Project overview |
| `EcommerceWebTraffic_Analysis.ipynb` | Jupyter Notebook containing all analysis workflows |
| `ecommerce_web_traffic_dataset` | Folder containing datasets used for visualization |

---

## 🗂 Data Description

The dataset used for this analysis represents simulated e-commerce web traffic and customer behavior across multiple marketing channels, devices, and platforms. It captures user engagement, conversion activity, and channel performance over time to evaluate how different sources contribute to the overall sales funnel.
The data spans the period January 2024 to October 2025 and includes 13 key variables that collectively describe user interactions — from impressions to final purchases. Each record represents aggregated session-level activity. Data contains 12k rows and 13 columns.

| **Column Name**      |                  **Description**                                       |
| -------------------- | ---------------------------------------------------------------------- |
| `date`               | Session date between Jan 2024 – Oct 2025                               |
| `country`            | User’s country (e.g., United Kingdom, Germany, France, etc.)           |
| `traffic_channel`    | Source of web traffic (Organic, Paid, Social, Referral, Direct, CRM)   |
| `device_type`        | Device used to access the website (Desktop, Mobile, Mobile Web, Tablet)|
| `platform`           | Operating system (iOS, Android, Others)                                |
| `visits`             | Number of visits or sessions generated                                 |
| `session_duration`   | Average time spent per session (in minutes)                            |           
| `no_of_customers`    | Count of customers involved in the session(s)                          |
| `impressions`        | Number of ad or content impressions generated                          |
| `views`              | Number of page or product views resulting from impressions             |
| `wishlist_adds`      | Number of items added to wishlist                                      |
| `cart_adds`          | Number of items added to shopping cart                                 |
| `items_purchased`    | Number of items successfully purchased                                 |

---

## 📊 Key Insights

- **Traffic Channel Analysis:** Organic and Paid drive the most visits, while Direct visitors engage longer per session. CRM and Direct channels deliver higher CTR, while Paid and Social underperform. CRM users spend more and abandon less, and Paid/Social show high abandonment.

- **Engagement Behavior Analysis:** Traffic volume alone doesn’t drive purchases. Focus should be on quality traffic (impressions & views). Longer sessions slightly boost views and purchases, especially for Organic, Direct, and CRM channels. High correlation among views, wishlist, cart adds, and purchases indicates a strong conversion funnel.

- **Device Type & Platform Analysis:** Android drives the highest traffic, while Desktop/iOS and Tablet/iOS lead in engagement and conversions. Mobile Web/Others show the weakest performance.

- **Country level Analysis:** Italy drives high traffic but low conversion efficiency, while Ireland delivers lower-volume yet higher-intent traffic
 
- **Time-based Trends:** 2025 mirrors 2024’s seasonal behavior but underperforms overall, with a sharp dip in April and a standout recovery in August. Platform is attracting a steady audience regardless of day type.

- **Seasonality:** Holiday season contributes only ~15–18% of annual performance, showing minimal uplift. Overall performance remains similar to the rest of the year, with slightly stronger holiday intent from iOS users and minor traffic increases across channels indicating holiday campaigns are underutilized and need improvement.

---

## 🧠 Methodology

The analysis workflow includes:

1. **Data Cleaning & Preprocessing:**  
   - Handling missing and inconsistent values  
   - Converting date/time fields to proper formats  
   - Feature engineering such as session day, weekday, and session hour

2. **Exploratory Data Analysis (EDA):**  
   - Summary statistics  
   - Visualization of temporal patterns  
   - Breakdown by traffic sources and devices

3. **Insights and Recommendations:**  
   - Highlighting actionable findings  
   - Strategic recommendations based on user behavior and traffic dynamics

---

## 🛠 Tools & Technologies

- **Python**
- **pandas & NumPy** — For data manipulation
- **Matplotlib & Seaborn** — For visualizations
- **Jupyter Notebook** — For exploratory and reproducible analysis

---

## 📬 Contact

For questions or feedback, feel free to connect:

**Ekta Mangar** – Data Analyst & Project Author


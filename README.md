# Google Data Analytics Capstone: Amazon Delivery Optimization Analysis

## 📋 Project Overview

This case study analyzes 43,000+ Amazon delivery records from March 2022 to identify key factors 
affecting on-time delivery performance. Using the 6-step Data Analysis Life Cycle (Ask, Prepare, 
Process, Analyze, Share, Act), the analysis uncovers critical insights about traffic impact, 
agent performance, and weather effects on delivery times.

**Key Finding:** Traffic jam conditions cause 22 additional minutes of delay compared to 
normal traffic, presenting the highest opportunity for operational improvement.

---

## 🎯 Business Task

Analyze shipment data to understand current on-time delivery performance and identify key factors 
(traffic, weather, agent rating) influencing delivery time to recommend efficiency improvements.

**Stakeholders:** Dispatch Team, Logistics Manager

---

## 📊 Dataset

- **Source:** Kaggle (publicly available Amazon delivery dataset)
- **Records:** 43,000 initial deliveries → 30,624 cleaned records
- **Timeframe:** March 2022
- **Key Columns:** Order_ID, Delivery_Time, Traffic_Conditions, Weather, Agent_Rating

---

## 🔄 Analysis Methodology (6-Step Framework)

### Phase 1: Ask ❓
Defined business question: What factors most significantly impact delivery times?

### Phase 2: Prepare 📂
- Data source: Kaggle public dataset
- 43,000 initial records
- Data limitations documented

### Phase 3: Process 🛠️
**Data Cleaning in Excel:**
- Filtered to March 2022 records only
- Removed 35 invalid rows (Agent_Rating > 5)
- Replaced 75 NaN cells with "Unknown"
- Verified: 0 duplicates, 0 empty values in key columns
- **Final: 30,624 clean records**

### Phase 4: Analyze 📈
Used Excel pivot tables and AVERAGEIF functions to calculate:
- Average delivery time by traffic condition
- Average delivery time by agent rating
- Average delivery time by weather condition

**Key Findings:**
| Factor | Best Performance | Worst Performance | Difference |
|--------|-----------------|------------------|-----------|
| **Traffic** | Low Traffic: 101 min | Traffic Jam: 147 min | +46 min |
| **Agent Rating** | 4.5-5.0: 110 min | 1.0-2.0: 155 min | +45 min |
| **Weather** | Clear: 118 min | Fog: 152 min | +34 min |

### Phase 5: Share 📢
- Dashboard: [View Google Slides Presentation](link-to-your-google-slides)
- Visualization outputs saved as PNG files (see Visualizations folder)

### Phase 6: Act 🚀
**Recommendations:**
1. Validate traffic data classification (data quality issue identified)
2. Document high-performing agent tactics for team training
3. Integrate traffic-aware routing into dispatch algorithms
4. Increase overnight/early-morning delivery shifts to avoid peak traffic

---

## 🛠️ Tools & Skills Demonstrated

- **Data Cleaning:** Filter, sort, error detection, null value handling
- **Data Analysis:** Pivot Tables, AVERAGEIF, conditional analysis
- **Data Visualization:** Chart creation, trend analysis
- **Documentation:** Case study write-up, methodology explanation
- **Problem-Solving:** Data quality issue identification and recommendation

---

## 📁 Files in This Repository

- `amazon_delivery.xlsx` - Complete dataset with cleaning log and pivot tables
- `Readme Amazon Delivery optimization project.`  Comprehensive case study report following the complete 6-step Data Analysis Life Cycle (Ask, Prepare, Process, Analyze, Share, Act). Documents the full methodology from business objective definition through data cleaning validation and actionable recommendations.
- `Visualizations/` - Charts and graphs supporting findings
- `README.md` - This file

---

## 💡 Key Insights

1. **Traffic is the dominant factor** affecting delivery times (46-minute impact)
2. **Data quality issue discovered:** Traffic jam volume nearly equals low traffic volume, 
   suggesting possible logging error
3. **Agent performance matters:** High-rated agents (4.5-5) deliver ~45 minutes faster
4. **Weather is secondary:** Only 34-minute variance between best and worst conditions

---

## 🎓 What I Learned

This project reinforced the importance of:
- Thorough data cleaning and validation before analysis
- Critical evaluation of data quality (discovering the traffic anomaly)
- Presenting findings to non-technical stakeholders
- Recommending actionable solutions based on data insights

---

## 📧 Contact & Connect

- **LinkedIn:** https://www.linkedin.com/in/kims009/
- **Email:** kimskh009@gmail.com

---

*Project completed as capstone for Google Data Analytics Certificate*


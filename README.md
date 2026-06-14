# Sakani Insights — Integrated Housing Market Analysis 

An advanced Business Intelligence and Data Engineering project developed during the Executive Master's program in Business Analytics at King Saud University. This project transforms scattered real estate data into a unified strategic benchmark to empower housing policy decison-making.


##  Business Value & Impact
Unlike traditional dashboards that only visualize past data, this project bridges the gap between commercial real estate dynamics and government support frameworks. The core value includes:
1. **Affordability Monitoring:** Tracks the monthly gap between financed support and actual market prices to adjust subsidy ceilings.
2. **Regional Planning Support:** Highlights real estate capital concentration (revealing that 78% of financed value is centered in Riyadh, Makkah, and Eastern Province) to optimize geographic quota distribution.
3. **Product-Mix Risk Management:** Aids in balancing the portfolio by identifying the heavy reliance on Market-Ready Units (101K contracts) vs. Under-Construction or Self-Build tracks.

---

##  Data Sources & Architecture
The architecture integrates and harmonizes three traditionally isolated data domains into a single conformed environment:
* **Government Support:** Sakani program beneficiary data.
* **Free Market Trends:** Aqar platform listings.
* **Tourism/Short-Term Rentals:** Airbnb property performance metrics.


##  Key Metric: The Price Gap Index
Using **Advanced DAX** scripting, we formulated a custom metric called the **Price Gap Index**. 
> **Key Finding:** The index exposed a substantial gap of **SAR 1.82M** between the government's average financed contract value and the actual market price of villas in the free market. 

---

## Dashboard Preview

### 1. Sakani Executive Dashboard
*Comprehensive insights into beneficiary demographics, geographic distribution, and product types.*
<img width="641" height="356" alt="sakani dashboard" src="https://github.com/user-attachments/assets/2a6651b4-40be-4a43-bc2d-651c2191a99e" />


### 2. Aqar & Airbnb Market Dashboard
*Analyzing free-market villa benchmarks and short-term tourism rental spikes driven by pilgrim demand in Makkah.*
<img width="719" height="313" alt="Aqar screen shot" src="https://github.com/user-attachments/assets/4bb28b91-6d21-47a8-bc21-bc09f135cc2f" />

<img width="413" height="267" alt="dimensional model" src="https://github.com/user-attachments/assets/44a530de-5296-426e-9b19-7d535673c469" />
<img width="624" height="353" alt="data quality power query" src="https://github.com/user-attachments/assets/ac96edb9-6750-43e5-9cc0-9ed1aa390488" />




---

## Strategic Action Roadmap
* **Policy Improvements:** Calibrate REDF support dynamically based on the Price Gap Index and establish a dedicated path to elevate female beneficiary representation.
* **Future Technical Enhancements:** Transition from static snapshot data to automated Live API feeds and append a Predictive Analytics layer to forecast regional demand 12–18 months out.


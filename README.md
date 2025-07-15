# 🏙️ Dubai House Price Analysis Dashboard

This project presents a comprehensive housing price analysis using **Power BI**, focusing on key property attributes in Dubai. The goal is to uncover trends related to **price**, **location**, **size**, **number of rooms**, and **property age**. These insights assist **real estate stakeholders** in making informed investment and development decisions.

---

## 📌 Project Objectives

* Explore Dubai housing price trends across **neighborhoods**, **property sizes**, and **listing categories**.
* Identify pricing patterns based on **bedroom/bathroom count**, **property age**, and **urban zones**.
* Analyze average price per square foot to assess **real estate valuation**.
* Provide actionable insights for **developers, buyers, and investors**.

---

## 🧾 Dataset Overview

* **Total Listings**: 50,000 properties
* **Features Included**:

  * Price, Size (Sqft), Year Built, Neighborhood, Bedrooms, Bathrooms
  * Derived fields: Price per Sqft, Property Age, Price Category (Budget/Mid/High-End)
* **Time Frame**: Built Years ranging from 1950 to 2025

---

## 🧮 Phase 1: Power Query Preprocessing (Power BI)

Preprocessed and cleaned data using Power Query Editor in Power BI:

* ✅ No **duplicates** or **missing values** found.
* 📊 **Data Type Validation**: Numeric (Price, Size), Categorical (Neighborhood, Category)
* 📐 **Calculated Columns**:

  * `Price per Sqft` = Price / Size
  * `Property Age` = 2025 - Year Built
  * `Listing Category` = Budget / Mid-Range / High-End (based on price quantiles)

---
## 📊 Phase 2: Power BI Dashboard & Insights
Created an interactive dashboard using Power BI with filters for deep-dive analysis across regions and property segments.


### ✅ Key Visuals & Insights

#### 1. Property Price Across Years

* Price trends from **1950 to 2020** remain relatively stable.
* Minor **fluctuations** observed, indicating a **mature real estate market**.

#### 2. Price Category Distribution (Pie Chart)

* Properties are **almost equally distributed**:

  * **High-End**: 34%
  * **Mid-Range**: 33%
  * **Budget**: 33%

#### 3. Price Per Sqft by Category & Neighborhood

* **High-End listings in Urban areas** have the **highest price per sqft**.
* **Budget listings dominate** in **Rural and Suburb** zones.
* **Mid-Range properties** show consistent pricing across all locations.

#### 4. Neighborhood Distribution

* Listings are **evenly spread**:

  * Urban: 33.4%
  * Rural: 33.4%
  * Suburb: 33.2%

#### 5. Price and Price/Sqft vs Property Age

* Properties aged **<20 years** and **40–60 years** have **higher average prices**.
* Indicates **preference** for newer and established-age properties.

#### 6. Prices by Bedrooms & Bathrooms

* Property prices **increase with room count**.
* **5-bedroom, 3-bathroom** homes fetch the **highest average prices**.

---

## 🔍 Conclusion

The Dubai housing analysis reveals:

* 🏙️ **Urban areas** dominate in **price per sqft** for High-End listings.
* 🏠 **Larger homes** command significantly higher prices.
* 🧱 **Properties aged <20 or 40–60 years** are the **most valuable**.
* 💸 Market shows **balanced listing distribution** across all segments.
* 📈 Stable growth pattern indicates **low volatility** and **investment reliability**.

These insights can **empower real estate buyers, investors, and developers** to make **data-backed strategic decisions**.

---

## 🛠️ Tools & Technologies Used

* **Power BI** – Dashboarding & Visualization
* **Power Query Editor** – Data Cleaning and Transformation
* **DAX** – Calculated Fields and Measures

---

## 📁 Project Structure

```
Dubai-House-Price-Analysis/
│
├── data/
│   └── dubai_property_data.csv
│
├── dashboard/
│   └── Dubai_Housing_Insights.pbix
│
├── reports/
│   └── README.md
│
└── images/
    └── [dashboard visual screenshots]
```

---

## 📬 Contact

**Isha Chaudhary**

📧 \[[ishadvay3928@gmail.com](mailto:ishadvay3928@gmail.com)]

🔗 [LinkedIn](https://www.linkedin.com/in/ishachaudhary18)

📍 Noida, India


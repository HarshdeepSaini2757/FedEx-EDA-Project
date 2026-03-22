# FedEx-EDA-Project
FedEx Supply Chain EDA
# FedEx Supply Chain EDA: Global Logistics Performance & Delivery Analytics

## 📊 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of FedEx's SCMS (Supply Chain Management System) delivery history dataset, encompassing **4,592 global shipments across 28 countries**. 

The analysis examines critical logistics metrics including delivery times, freight costs, shipment modes, and on-time performance to extract actionable insights for supply chain optimization.

## 🎯 Business Objectives

The primary goals of this analysis are to:

1. **Reduce Late Deliveries** - Improve on-time delivery performance
2. **Improve Delivery Speed** - Reduce average delivery time
3. **Reduce Shipping Costs** - Optimize freight and operational costs
4. **Improve Vendor Performance** - Enhance supplier quality and reliability

## 📈 Key Findings

### Dataset Overview
- **Original Records:** 10,324 shipments
- **Cleaned Records:** 4,592 shipments
- **Columns:** 33 original, 42 after feature engineering
- **Geographic Coverage:** 28 countries
- **Shipment Modes:** Air, Ocean, Air Charter, Truck

### Critical Insights

#### Cost Efficiency
- Average freight cost: **$11,397 per shipment**
- Cost-per-KG: **$41.82 (ranging $1.23 - $847.65)**
- Freight costs can exceed 50% of product value in some cases
- **Optimization Opportunity:** 5-10% cost reduction potential ($2-3M annually)

#### Delivery Performance
- Average delivery time: **117.8 days (range: 12-616 days)**
- On-time delivery rate varies by mode: **60-100%**
- Ocean freight slowest (170 days) but most cost-effective
- Air freight fastest (95 days) but most expensive

#### Operational Patterns
- **Peak shipping month:** March (354 shipments = 12.2% of annual)
- **Lowest shipping month:** December (187 shipments)
- **Busiest quarter:** Q3 (810 shipments = 28.1%)
- **Weekday dominance:** 99.1% weekday, only 0.9% weekend shipments

#### Critical Risks Identified
1. **Vendor Concentration:** 71.8% in EXW terms (CRITICAL - 40-50% above best practice)
2. **Fulfillment Channel:** 100% Direct Drop (ZERO alternatives)
3. **Weekend Service:** Only 0.9% weekend shipments (missing $140-160M market)
4. **Cost Structure:** Highly variable by mode and route

## 📊 Data Visualizations

The project includes **15 comprehensive charts** covering:

### Univariate Analysis (5 charts)
- Delivery time distribution
- Freight cost distribution
- Cost-per-KG distribution
- Product value distribution
- Insurance cost distribution

### Bivariate Analysis (5 charts)
- Shipment mode analysis
- Weight vs. freight cost correlation
- Delivery time by mode
- Top countries by volume
- On-time vs late rate

### Multivariate Analysis (5 charts)
- Shipments by month
- Shipments by quarter
- Shipments by day of week
- Correlation heatmap
- Total shipment cost distribution

## 🔧 Technologies Used

- **Language:** Python 3.x
- **Libraries:**
  - pandas (data manipulation)
  - numpy (numerical computing)
  - matplotlib (visualization)
  - seaborn (statistical plotting)
  - plotly (interactive charts)

- **Platform:** Google Colab (Jupyter Notebook)

## 📁 Project Structure
FedEx-EDA-Project/
├── FecX_EDA_Project.ipynb          # Main notebook with all analysis
├── SCMS_Delivery_History_Dataset.csv  # Source dataset
├── README.md                        # This file
└── Documentation/
├── Problem_Statement.md
├── Business_Objectives.md
├── Data_Wrangling_Summary.md
└── Recommendations.md


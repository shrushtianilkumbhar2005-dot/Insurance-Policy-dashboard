# Insurance Policy Performance Dashboard

An interactive, data-driven Excel dashboard designed to transform raw insurance data into actionable business insights. This project analyzes policy performance, claim distributions, and customer demographics to track key performance indicators (KPIs) and support data-backed business reporting.

## 📊 Project Overview & Objectives
The primary objective of this project is to analyze a sample insurance dataset to evaluate policy sales, premium generation, claim statuses, and customer demographic trends. 

By building this interactive dashboard, the project aims to:
- Monitor and track overall corporate insurance metrics through KPI cards.
- Identify seasonal sales trends across months.
- Group and analyze policy performance by customer segments (Age Group and Gender).
- Map total premium revenues against claim liabilities across various policy types.

---

## 🛠️ Tools & Techniques Used
- **Software:** Microsoft Excel
- **Data Engineering:** Data Cleaning, Type Conversion, and Transformation
- **Logical Modeling:** Advanced `IF` formulas for demographic segmentation
- **Analytics Engine:** Excel PivotTables & calculated fields
- **Visualization & UI:** PivotCharts, Slicers, KPI Cards, and Slicer Connections for a fully interactive dashboard experience

---

## 🧼 Data Preparation & Transformation
Before building the visual layers, the raw dataset underwent comprehensive preprocessing:
1. **Data Cleaning:** Handled missing inputs, eliminated anomalies, and validated structural formatting.
2. **Demographic Segment Construction:** Utilized Excel logical formulas to add a custom `AgeGroup` column based on customer age inputs:
   - **Young Adult** (Ages 18–25)
   - **Adult** (Ages 26–35)
   - **Middle Age** (Ages 36–55)
   - **Senior** (Ages 56+)
3. **Data Aggregation:** Summarized transactional records into multi-dimensional arrays optimized for pivot cache routing.

---

## 📈 Key Insights & Dashboard Components

Based on the parsed pivot architecture, the final dashboard delivers metrics across several critical business dimensions:

### 1. High-Level Financial Performance (KPI Cards)
- **Total Policies Sold:** 10,000 policies
- **Total Coverage Amount Issuance:** \$600,331,240
- **Total Claims Liability:** \$16,904,332

### 2. Premium Contribution by Demographic Segment
- **By Gender:** Premium generation is highly balanced between genders, with **Female** customers contributing \$2,990,575 and **Male** customers contributing \$2,983,532.
- **By Age Group:** **Seniors** drive the largest revenue share, accounting for **45.32%** of total premiums, followed by Middle Age at 29.06%, Adults at 14.30%, and Young Adults at 11.31%.

### 3. Policy Performance & Revenue Vectors
- **Travel Insurance** is the highest volume channel, representing **41.44%** of the premium pool and generating \$7,088,888 in claim value.
- **Health Insurance** closely follows as the second-highest source of claim volume at \$3,432,317.
- Remaining performance pools are split across **Auto**, **Life**, and **Home** policy types.

### 4. Operational Claim Status Lifecycle
- **Pending Claims:** 2,260 cases
- **Settled Claims:** 3,386 cases
- **Rejected Claims:** 4,354 cases

### 5. Sales Seasonality Analytics
- Monthly trends show consistent transactional activity throughout the calendar year, peaking slightly during the month of **October (8.84%)** and **August (8.71%)**.

---

## 📂 Repository Structure
```filesystem
├── data/
│   └── raw_insurance_data.csv       # Pre-transformed sample dataset
├── dashboard/
│   └── Insurance_Performance.xlsx   # Final macro-enabled interactive workbook
└── README.md                        # Documentation file
```

---

## 🚀 How to View the Dashboard
1. Clone this repository to your local system.
2. Navigate to the `dashboard/` directory and open `Insurance_Performance.xlsx` using Microsoft Excel.
3. Ensure macros or data connections are enabled if prompted to allow interactive slicer synchronization.
4. Interact with the demographic and product slicers at the top of the sheets to filter the charts dynamically.

---

## 🎯 Conclusion
This project successfully demonstrates how raw operational records can be transformed into a strategic corporate asset using Microsoft Excel. By centralizing critical policy, product lifecycle, and demographic datasets into a synchronized interface, the dashboard provides a complete view of business health, helping stakeholder tracking and driving informed operational pivots.

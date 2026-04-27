# Power-BI-Sales-Analytics-Dashboard

## 📊 Project Overview

A comprehensive **Power BI Dashboard** built using **Star Schema** methodology with 500+ rows of realistic business data. This project demonstrates best practices in data modeling, DAX measures, and interactive visualizations for sales analytics.

### 🎯 Key Features
- ✅ **Star Schema Design** - Optimized data model with 3 dimensions & 3 fact tables
- ✅ **7 Interactive Pages** - 42 Cards + 42 Visualizations
- ✅ **30+ DAX Measures** - Time intelligence, customer analytics, profitability metrics
- ✅ **500 Rows Each Table** - Production-ready dataset
- ✅ **Complete Documentation** - Step-by-step implementation guide

---

## 📁 Dataset Structure

### Dimension Tables (Lookup)
| Table | Rows | Key Columns |
|-------|------|-------------|
| Store Table | 500 | StoreID (PK), Region, City, StoreType |
| Product Table | 500 | ProductID (PK), Category, SubCategory, UnitPrice |
| Customer Table | 500 | CustomerID (PK), AgeGroup, MembershipTier |

### Fact Tables (Measures)
| Table | Rows | Key Columns |
|-------|------|-------------|
| Fact_Sales | 500 | DateKey, StoreID, ProductID, Quantity, SalesAmount |
| Fact_Returns | 500 | DateKey, ReturnReason, RefundAmount |
| Fact_Target | 500 | Year, Month, SalesTarget, QuantityTarget |

🛠️ Technologies Used
Power BI Desktop - Data modeling & visualization

DAX - Measures & calculated columns

Python - Synthetic data generation (Pandas, Random)

Star Schema - Dimensional modeling

📈 Business Insights Generated
✅ Customer Segmentation - Age group & membership tier analysis
✅ Product Profitability - Margin analysis by category
✅ Store Performance - Regional & store-type comparisons
✅ Return Pattern Analysis - Root cause identification
✅ Target Tracking - Real-time goal monitoring


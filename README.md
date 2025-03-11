# 2Market : Consumer-Analytics

### 📋 Project Brief
I conducted customer purchase behaviour analysis for 2Market, a global retailer, delivering actionable insights across demographics, advertising channels, and product preferences. 

### ✅ Objectives
The analysis supported key business objectives: 
- increasing profitability
- improving market position in different markets
- enhancing customer experience by targeted marketing strategies</b>&nbsp;&nbsp;&nbsp;
</div>

### 🎯 Conclusion
The analysis of 2Market's customer data revealed significant opportunities to increase revenue and market share through targeted strategies. Spain currently dominates revenue (49%), while child-free customers and social media channels demonstrate exceptional value. 

**Key Recommendations:**
- Expand beyond Spain to diversify market presence
- Target high-value child-free segments through Instagram
- Prioritize social media over traditional marketing (4x more effective)
- Enhance mid-life customer basket size and in-store experience
- Diversify beyond liquor and meat product categories
---

### Project Overview:
<div>
  <table>
    <tr align="center">
      <th align="center">⏱️ Duration</th>
      <th align="center">🏆 Grade</th>
      <th align="center">🛠️ Tools</th>
    </tr>
    <tr>
      <td align="center"><b>6 Weeks <b></td>
      <td align="center"><b>96% (High Distinction)</b></td>
      <td align="center">
        <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">
        <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white">
        <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white">
      </td>
    </tr>
  </table>
</div>

---

### Analytical Approach:
#### 1. Data Preparation & Cleaning

| Process | Highlights |
|---------|---------|
| **Data Import** | Imported raw marketing data into Excel as structured table |
| **Data Cleaning** | • Converted data types for proper analysis<br>• Checked data integrity (duplicates, missing values)<br>• Identified and addressed outliers using min/max/average<br>• Standardized categorical data (marital status) with VLOOKUP<br>• Normalized date fields using TEXTSPLIT, IF, and DATE functions |
| **Initial Analysis** | • Created demographic distributions with box plots and line graphs<br>• Analyzed relationships between customer features (age, income, marital status, family composition) |

#### 2. SQL Analysis

| Process | Highlights |
|---------|---------|
| **Data Loading** | Loaded cleaned Excel data into SQL data-table |
| **Query Development** | Wrote complex SQL queries using Joins, Subqueries and Case Statements for detailed analysis. |
| **Analysis Focus** | • Identified best-selling products by country<br>• Determined most effective advertising methods by country<br>• Calculated marketing revenue attribution<br>• Compared social media effectiveness across channels |

#### 3. Tableau Dashboard Development

| Component | Highlights |
|-----------|---------|
| **Dashboard Suite** | Developed three interconnected dashboards:<br>• Customer Demographics<br>• Marketing Effectiveness<br>• Product Sales & Purchase Patterns |
| **Technical Elements** | • Created 41 calculated fields for dynamic analysis<br>• Implemented data source filters for outliers |
| **Visualization Techniques** | • Utilized Dynamic zone visibility for detailed exploration of different marketing channels<br>• Treemap for country-wise Revenue and Customer analysis<br>• Interactive KPIs based on filtered segments<br>• Cross-referenced visualizations |

---

### 🗝️ Key Insights:

**Customer Demographics**
- Identified Spain, South Africa, and Canada as top markets by revenue and customer count
- Discovered *Midlife segment (45-54 years)* constitutes the largest customer group across countries
> [!IMPORTANT]
  > **Value Discovery:** Child-free customers demonstrate significantly higher value, generating:
  > - $695,384 in revenue from just 630 customers
  > - 2-5× higher spending across all product categories
  > - Higher average income across all age groups

<div align="center">
  <img src="https://github.com/user-attachments/assets/a44af12e-fb0c-4ba5-aee3-1f61fd918eda" alt="Customer Demographics Dashboard" width="85%"/>
  <p><em>Dashboard showing revenue distribution across countries and spending patterns by demographic segments</em></p>
</div>

**Marketing Effectiveness**
- Quantified marketing attribution at **8% of overall revenue** from Q3 2012 to Q2 2014
> [!IMPORTANT]
> **Value Discovery:** Determined *social media channels* (Facebook, Twitter, Instagram) were **4x more effective** than traditional channels
- Highlighted Instagram as the highest-value channel (highest basket value at $126, lowest deal usage at 1.1)
- Measured recent campaign success rates: Instagram (56%), Facebook (55%), Twitter (38%)

<div align="center">
  <img src="https://github.com/user-attachments/assets/21af8a48-6e92-48e4-9613-759339931a19" alt="Marketing Effectiveness Dashboard" width="85%"/>
  <p><em>Dashboard comparing Marketing Channels and their effectiveness across customer demographies and product patterns</em></p>
</div>  

**Product & Purchase Analysis**
- Identified Liquor and Meat products as dominant sales categories (75% of overall revenue)
- Discovered *child-free customers* **outspend** those with children by **2-5x** across all categories
- Recognized global preference for walk-in shopping despite improvements in online ratios
> [!IMPORTANT]
> Tracked significant improvements in online purchase-to-web-visits ratio in Q1 2014

<div align="center">
  <img src="https://github.com/user-attachments/assets/74c0cd49-805e-46bb-815e-14336a1a2065" alt="Products and Purchasing Patterns Dashboard" width="85%"/>
  <p><em>Dashboard showing product category performance and purchasing behavior across demographic segments</em></p>
</div>

---
### 📊 Recommendations to Business:

Based on the comprehensive data analysis, the following strategic recommendations were presented to enhance 2Market's business performance:

**Business Recommendations**
- Mitigate risk by expanding customer base outside Spain.
- Increase basket size for mid-life customers.
- Focus on high-revenue customer segments, particularly child-free customers.
- Prioritize Social media marketing, Instagram and Twitter
  - Instagram for child-free high value customers
  - Twitter for mid-life customers with children.
- Diversify product offerings beyond liquor and meat.
- Enhance in-store shopping experience for customers with children.

**Technical Recommendations**
- Conduct further analysis at regional levels to tailor marketing and product strategies more effectively.
- Gather more granular product, invoicing and marketing data to refine sales and marketing strategies.

---
### The Tableau Dashboard is available here: [2Market Customer Analysis](https://public.tableau.com/views/2Market_Analysis_SujithKumaarKC/MarketingEffectivenessDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

# Amazon Seller Analysis for Acquisition Targeting

## Overview
This analysis provides a comprehensive profile of Amazon sellers, aimed at identifying the most promising acquisition targets for the Acquisitions team. The report evaluates seller profiles based on inventory size, customer satisfaction ratings, and geographical distribution. By leveraging data cleaning and visualization techniques, we have identified key sellers and regions that could offer strategic advantages.

The analysis was conducted using **Tableau Prep** for data cleaning and **Tableau** for visualization.

---

## Data Cleaning Process
Before analyzing the seller data, we ensured data quality and consistency through the following steps in Tableau Prep:

1. **Handling Missing Values**: 
   - Missing data points were either imputed or removed if extensive, to avoid bias in the analysis.

2. **Data Standardization**: 
   - Key fields such as `sellerproductcount`, `Positive Rating Percentage`, and `Hero product ratings` were standardized for consistency.

3. **String Extraction and Conversion**:
   - Extracted numerical values from text fields (e.g., `sellerproductcount`) and converted necessary fields to appropriate data types (e.g., integers, percentages).

4. **Data Aggregation**:
   - Aggregated data at the seller level to create a summary table, accurately representing each seller’s performance metrics.

---

## Dashboard Analysis and Insights
The following insights and conclusions were derived from Tableau visualizations:

### 1. Inventory Distribution Across Top Sellers
   - **Insight**: Sellers such as "Visit the Technoline Store" and "Visit the TFA Dostmann Store" have the largest inventories with 200 and 193 products, respectively. These sellers are prime acquisition candidates due to their extensive product offerings.
   - **Conclusion**: High product count sellers indicate market presence and operational efficiency, making them attractive for acquisition.

### 2. Comparing Seller Product Count with Customer Satisfaction Across Regions
   - **Insight**: A scatter plot shows that sellers like "Visit the TFA Dostmann Store" and "Visit the tesa Store" have large inventories and high customer satisfaction, especially in Germany.
   - **Conclusion**: Sellers who balance high product counts with positive customer feedback are ideal acquisition targets, particularly in strategic markets like Germany.

### 3. Seller Inventory Overview for 2020
   - **Insight**: A packed bubble chart highlights key sellers by inventory size for 2020, showing "Visit the Technoline Store" and "Visit the tesa Store" as consistent in sustaining supply and meeting market demand.
   - **Conclusion**: Sellers with large inventories in 2020 demonstrate strong market positions, making them reliable acquisition targets.

### 4. Global Distribution of Seller Performance
   - **Insight**: Map visualization reveals Germany and the US as regions with high product counts and positive customer ratings, highlighting these areas as key for market expansion.
   - **Conclusion**: Acquisitions in Germany and the US could strategically enhance market coverage and access to reliable sellers.

---

## Overall Strategic Insights

### Strategic Seller Selection
   - The analysis highlights sellers with high product counts and high customer satisfaction, particularly in Germany and the US, as promising acquisition targets. Sellers like "Visit the Technoline Store," "Visit the tesa Store," and "Visit the TFA Dostmann Store" are top candidates due to their robust inventory levels and market presence.

### Geographical Focus
   - Concentrating on sellers in Germany and the US could provide strategic advantages, as sellers in these regions show strong performance in inventory management and customer satisfaction.

### Yearly Performance Emphasis
   - Analyzing 2020 performance suggests that sellers who maintained strong inventory and customer satisfaction during that year are reliable acquisition targets for continued performance.

---

## Conclusion
This analysis offers actionable recommendations for strategic acquisitions based on inventory size, customer satisfaction, and geographical distribution. The data cleaning process ensured high-quality, reliable data, resulting in valuable insights for identifying promising Amazon sellers for acquisition.

--- 

### Visualizations
The visualizations used in this analysis are as follows:
1. **Inventory Distribution Bar Chart**
2. **Product Count vs. Customer Satisfaction Scatter Plot**
3. **Packed Bubble Chart for 2020 Inventory Overview**
4. **Global Map of Seller Performance**

Each visualization is available within the Tableau dashboard.

---

## How to Use This Analysis
This report is designed to assist the Acquisitions team in making informed decisions about potential acquisition targets on Amazon. By focusing on the top-performing sellers identified in this analysis, the team can strategically expand market coverage and acquire sellers with proven inventory management and customer satisfaction.

---

## Authors
- **Data Analysis and Report**: Naman Pant
- **Visualization and Insights**: Tableau Dashboard Team
- **Data Cleaning**: Tableau Prep Team

---

## License
This project is licensed under the MIT License.

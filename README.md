# HALModa-Nova-sales-performance-analysis-2014
# **Technical Report: Moda Nova Group Sales Performance Analysis – 2024**

**By:** Adebayo Haleemah Olajumoke
**Tool Used:** Microsoft Excel
**Industry:** Retail / E-Commerce

## **1. Outline**

This technical report presents a comprehensive sales performance analysis for Moda Nova Group for the year 2024. It explores the company’s sales trends, customer behavior, education impact on purchases, shipping and product preferences, as well as social media influence on performance. The report includes:

* Introduction
* Story of Data
* Data Splitting and Preprocessing
* Pre-Analysis
* In-Analysis
* Post-Analysis and Insights
* Data Visualizations & Charts
* Recommendations and Observations
* Conclusion
* References & Appendices

---

## **2. Introduction**

### **Objective of the Project**

To analyze the sales data of Moda Nova Group in 2024, understand customer buying behavior, product performance, regional influence, and how social media and shipping preferences affect overall sales.

### **Problem Being Addressed**

What are the most significant drivers of sales for Moda Nova Group? How do customer demographics, education level, location, and digital influence impact performance?

### **Key Datasets and Methodologies**

* Datasets used: Sales data, customer demographics, shipping preferences, product reviews
* Tools in Excel: PivotTables, slicers, bar and line charts, pie charts, and conditional formatting


## **3. Story of Data**

### **Data Source**

Internal company records from Moda Nova Group's 2024 sales database.

### **Data Collection Process**

Data was aggregated monthly and segmented by category, geography, gender, education level, and customer ID.

### **Data Structure**

Each row represents a unique sales transaction. Columns include date, product category, customer ID, sales amount, gender, region, and education level.

### **Important Features and Their Significance**

* **Sales Amount** – key performance metric
* **Product Category** – for identifying bestsellers
* **Customer ID** – used to determine loyalty and value
* **Gender/Education** – reveals consumer segment patterns
* **Location** – identifies high-performing regions
* **Social Media Level** – measures digital influence

### **Data Limitations or Biases**

* Data lacks detailed timestamps (hour/day granularity)
* Minor inconsistencies in category labels required cleaning
* Customer sentiment not directly measured beyond ratings


## **4. Data Splitting and Preprocessing**

### **Data Cleaning**

* Removed duplicate entries
* Standardized inconsistent product names
* Handled minor label formatting issues

### **Handling Missing Values**

Used Excel’s `IFERROR`, `ISBLANK`, and `AVERAGEIFS` functions to handle missing data. No major gaps found.

### **Data Transformations**

Created calculated fields such as “Average Sale per Customer,” grouped months by quarter, and aggregated social media levels into categories (Low, Medium, High).

### **Data Splitting**

* **Dependent variable:** Sales Amount
* **Independent variables:** Product Category, Gender, Education, Region, Shipping Preference, Social Media Level

### **Industry Context**

Retail (E-commerce): highly dependent on seasonal patterns, digital marketing, and logistic efficiency.

### **Stakeholders**

* Marketing Team
* Sales Department
* Product Managers
* Logistics and Fulfillment Teams
* Senior Executives

### **Value to the Industry**

The insights provide decision-makers with clarity on how to optimize product focus, customer targeting, and shipping strategies to maximize revenue.


## **5. Pre-Analysis**

### **Identify Key Trends**

* Highest sales occurred in **April**.
* **Jewelry & Accessories** is the most profitable product category.
* Customers with no shipping preference generated the **highest revenue**.
* Social media significantly influenced buyer behavior.

### **Potential Correlations**

* Strong link between educational background and spending behavior
* High correlation between customer gender and product rating

### **Initial Insights**

* Bachelor’s degree holders are Moda Nova’s most valuable customer group
* Oslo is the top-performing city by sales
* Female customers dominate product engagement


## **6. In-Analysis**

### **Unconfirmed Insights**

* Express shipping is less used despite assumptions about speed-based customer preferences
* Despite high product ratings from women, sales are not equally distributed by gender—warrants deeper behavioral analysis

### **Recommendations**

* Focus on targeting Bachelor-degree holders in cities like Oslo and Magdalena
* Double down on social media advertising (particularly influencer campaigns)
* Prioritize Jewelry & Accessories in product promotions

### **Analysis Techniques Used in Excel**

* PivotTables for aggregating and slicing data
* Pie charts and bar graphs for categorical comparisons
* Line graphs for monthly sales trend
* Conditional formatting to highlight top customers
* Custom sorting and filtering by education level and shipping preference


## **7. Post-Analysis and Insights**

### **Key Findings**

* April is the most lucrative month
* Jewelry & Accessories drive the most revenue
* Social media with high engagement resulted in the best sales performance
* Female customers and Bachelor’s degree holders are Moda Nova’s primary contributors to revenue

### **Comparison with Initial Findings**

Initial assumptions about the value of express shipping and education levels held true for Bachelor’s, but were disproven for Master’s degree holders, who spent significantly less than expected.


## **8. Data Visualizations & Charts**

### **Charts and Graphs**

* **Line Chart**: Sales Trend (Jan–Dec)
* **Bar Chart**: Best Selling Categories
* **Pie Chart**: Shipping Preferences & Geographical Sales
* **Bar Chart**: Customer Performance and Educational Impact
* **Horizontal Bar**: Gender-Based Product Ratings
* **Stacked Columns**: Social Media Influence vs. Sales

### **Explanation of Visualizations**

* The sales trend chart highlights strong Q2 performance
* The pie chart shows “No Preference” shipping led in revenue
* Oslo dominated regional sales, followed by Magdalena
* Ratings were highest among female-identifying customers


## **9. Recommendations and Observations**

### **Actionable Insights**

* Promote Jewelry & Accessories heavily during Q2
* Leverage female customer feedback for marketing
* Focus digital ad spend on high social media influence segments
* Target educated buyers in urban areas like Oslo

### **Optimizations or Business Decisions**

* Expand product lines within Jewelry & Accessories
* Introduce loyalty programs for top-spending customers
* Reevaluate shipping strategy to offer incentives on faster delivery

### **Unexpected Outcomes**

* Master’s degree holders underperformed
* Express shipping was less preferred than anticipated despite value-added speed


## **10. Conclusion**

### **Key Learnings**

* Demographics, education, and digital influence are powerful drivers of sales
* “No Preference” customers are not indecisive; they’re simply flexible, reducing logistical friction
* A well-timed campaign in April can generate peak performance

### **Limitations**

* Data didn’t include real-time social media interaction
* No psychographic data for deeper sentiment analysis
* Customer age segmentation was present but not deeply analyzed

### **Future Research**

* Incorporate customer feedback and sentiment analysis
* Analyze repeat purchase behavior and churn
* Integrate Google Trends or TikTok insights for market forecasting


## **11. References & Appendices**

### **References**

* Moda Nova Group Internal Sales Database
* Excel Formulas Documentation (Microsoft)
* Industry Benchmarks from Statista

### **Appendices**

* Raw Pivot Table Snapshots
* List of Top 10 Products by Region
* Monthly Category Breakdown Chart
* Excel Formulas Used (`VLOOKUP`, `SUMIFS`, `AVERAGEIFS`, etc.)


![MODA NOVA GROUP SALES DASHBOARD](https://github.com/user-attachments/assets/45ced833-7497-4186-a366-140ff7019faf)

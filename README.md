# Smart-Vendor-Insights-Sales-Margin-Stock-Flow


##  Objectives

- **Identify** top-performing and underperforming vendors based on sales and profit metrics.
- **Analyze** inventory turnover rates to optimize stock levels and reduce holding costs.
- **Evaluate** the impact of bulk purchasing on unit costs and overall profitability.
- **Recommend** pricing and promotional strategies for brands with high margins but low sales volumes.
- **Assess** dependency on key vendors to mitigate supply chain risks.

---

## Dataset Description

The dataset encompasses detailed transactional records, including:

- `Vendor Name`: Supplier of the product.
- `Brand`: Product brand associated with the vendor.
- `Purchase Quantity`: Number of units purchased.
- `Sales Quantity`: Number of units sold.
- `Purchase Price`: Cost price per unit.
- `Sales Price`: Selling price per unit.
- `Freight Cost`: Shipping and logistics expenses.
- `Gross Profit`: Revenue minus cost of goods sold.
- `Profit Margin`: Gross profit as a percentage of revenue.
- `Stock Turnover`: Rate at which inventory is sold and replaced.

---

## 🛠️ Tools and Technologies

- **Python**: Data manipulation and analysis using `pandas`, `numpy`.
- **Data Visualization**: Insights presented through `matplotlib`, `seaborn`.
- **Jupyter Notebook**: Interactive environment for exploratory data analysis.
- **Power BI**: Dashboard creation for interactive data visualization.
- **Custom Scripts**: Automation of data ingestion and vendor summary generation.

---

## 🔍 Key Analyses and Findings

### 1. Data Cleaning and Preparation

- Removed records with zero sales, negative gross profit, or invalid profit margins to ensure data quality.

### 2. Exploratory Data Analysis (EDA)

- Identified outliers in freight costs and purchase prices, indicating potential inefficiencies.
- Detected products with zero sales, highlighting overstock or obsolete inventory.

### 3. Correlation Analysis

- Weak correlation between purchase price and gross profit suggests pricing strategies have limited impact on profitability.
- Strong correlation between purchase and sales quantities indicates efficient inventory turnover.

### 4. Vendor Segmentation

- Top 10 vendors account for 65.7% of total purchases, indicating a reliance that could pose supply chain risks.
- 198 brands exhibit high profit margins but low sales volumes, suggesting potential for targeted promotions or pricing adjustments.

### 5. Statistical Testing

- Conducted hypothesis testing to compare profit margins between top and low-performing vendors.
- Results confirm a significant difference, necessitating distinct strategies for each group.

---

## Visualizations

- **Sales and Profit Trends**: Line charts depicting monthly performance.
- **Vendor Contribution**: Bar charts illustrating each vendor's share in sales and profit.
- **Inventory Turnover**: Heatmaps identifying slow-moving stock.
- **Profit Margin Distribution**: Box plots comparing margins across vendors.

---

## Recommendations

- **Promotional Strategies**: Implement targeted marketing for high-margin, low-sales brands to boost revenue.
- **Vendor Diversification**: Reduce dependency on top vendors to mitigate potential supply disruptions.
- **Bulk Purchasing**: Encourage bulk orders to capitalize on reduced unit costs.
- **Inventory Management**: Address slow-moving inventory through discounts or stock adjustments.
- **Performance Monitoring**: Establish regular reviews of vendor performance metrics to inform strategic decisions.





# Sales and Shipping Performance Analysis

## Project Overview

This project provides a comprehensive data-driven analysis of sales and shipping performance by integrating multiple data sources. The analysis identifies key performance indicators (KPIs), uncovers trends in product profitability, geographical sales distribution, channel effectiveness, and shipping efficiency. The final output includes actionable business insights and recommendations.

The entire analysis was performed using **Google Colab (Python)**, with data stored in **Google Drive** and initial data exploration/small transformations done in **Excel**.

## Technologies Used

- **Google Colab** – Cloud-based Python environment for data processing, analysis, and visualization.
- **Python Libraries**:
  - `pandas` – Data manipulation and merging
  - `numpy` – Numerical operations
  - `matplotlib` & `seaborn` – Data visualization
  - `plotly` (optional) – Interactive charts
- **Excel** – Initial data inspection, quick cleaning, and creation of helper columns (e.g., region mapping) before loading into Python.
- **Google Drive** – Central storage for raw CSV files and exported results.

## Data Sources

Three CSV files were used, all stored in a Google Drive folder:

| File | Description |
|------|-------------|
| `countries.csv` | Country metadata (name, alpha‑2, alpha‑3, region, sub‑region) |
| `events.csv` | Sales events with order details, dates, product IDs, sales channel, units sold, unit price, and cost |
| `products.csv` | Product mapping (product ID to item type) |


 **Data Integration**  
   - Merge datasets (`countries`, `events`, `products`)

2. **Data Cleaning**  
   - Handle missing values  
   - Data type conversion  
   - Consistency validation

3. **Feature Engineering**  
   - Calculate:  
     - Revenue  
     - Cost  
     - Profit  
     - Shipping time

4. **Exploratory Data Analysis (EDA)**  
   - Sales distribution  
   - Performance by region  
   - Channel comparison

5. **Visualization**  
   - Bar charts  
   - Trends  
   - Regional comparisons

### 📈 Calculated KPIs

- Total orders  
- Total units sold  
- Total revenue  
- Total cost  
- Total profit  
- Average profit per order

### 🔍 Key Insights

#### 💰 Profitability
- **Most profitable products:** Cosmetics, Household, Clothes  
- **Europe leads in total profit**  
- **Offline channel** slightly more profitable than Online

#### 🚚 Shipping Efficiency
- **Countries with longest delays:** Montenegro, Serbia, Austria  
- **Asia** has longer shipping times than Europe  
- **Products with longest shipping time:** Office Supplies, Cereal

### 💡 Recommendations

- **📦 Product:** Focus on high-margin products; reassess underperforming categories  
- **🌍 Geography:** Expand successful European strategies; improve logistics in Asia  
- **🚛 Logistics:** Identify bottlenecks in delayed countries; optimize supply chain  
- **📢 Marketing:** Region‑specific strategies; strengthen most profitable channels  
- **😊 Customer Experience:** Improve delivery times; transparent shipping communication

---

## 👤 Author

[Sérgio Lopes]  
GitHub: [https://github.com/SLS02](https://github.com/SLS02)

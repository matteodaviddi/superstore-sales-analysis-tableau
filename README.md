# 📦 Superstore Sales Analysis
### Tableau · Sales Analytics · Profit Mapping · Product Performance

An interactive Tableau workbook analyzing global Superstore orders data across multiple dimensions — sales trends, geographic profit distribution, product performance, shipping modes and regional analysis. The project includes 11 analytical worksheets, 2 dashboards and 1 story presentation.

---


## 📊 Workbook Structure

### Worksheets (11)

| Sheet | Analysis |
|-------|---------|
| `sales trend` | Revenue trend over time |
| `profit map` | Geographic profit distribution by region/country |
| `regions performance` | Sales and profit comparison across regions |
| `products performance` | Top performing products by revenue and profit |
| `sales per sub-category` | Revenue breakdown by product sub-category |
| `products to delete` | Products with negative profit |
| `more budget` | Underperforming products with low-sales and high-margin |
| `less budget` | Low-margin and high-sales segments |
| `quantity by ship mode` | Units sold breakdown by delivery mode |
| `boxplot ship mode` | Profit distribution by shipping mode |
| `conclusion` | Summary insights and strategic recommendations |

### Dashboards & Story
- **Dashboard 1** — Executive overview combining key metrics
- **Dashboard 2** — Deep dive into product and regional performance
- **Story** — Narrative presentation of findings for stakeholders

---

## 🔍 Key Analyses

**Sales Trend**
Time-series analysis of revenue evolution, identifying seasonal patterns and growth periods across the dataset.

**Profit Map**
Geographic visualization of profit distribution — identifies high-performing and loss-making regions, enabling data-driven expansion or cost-reduction decisions.

**Product Performance**
Ranking of products by revenue and profit margin — highlights top performers and identifies products with negative margins that should be reconsidered or discontinued.

**Shipping Mode Analysis**
Boxplot and quantity analysis across delivery modes (Standard, Second Class, First Class, Same Day) — reveals the relationship between shipping speed, volume and profitability.

**Budget Segmentation**
Separation of high-value vs low-value customer and product segments to support targeted marketing and pricing strategies.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Tableau Desktop | Dashboard and visualization development |
| Tableau Story | Narrative presentation of insights |
| Superstore Dataset | Orders, customers, products, regions data |

---

## 📋 Dataset Structure

| Field | Description |
|-------|-------------|
| Order ID / Date | Order identifier and purchase date |
| Dispatch / Delivery Mode | Shipping method and dispatch date |
| Customer Name / Segment | Customer profile and segment (Consumer, Corporate, Home Office) |
| Region / Country / City | Geographic location hierarchy |
| Category / Sub-Category | Product classification |
| Product Name | Individual SKU |
| Sales | Revenue generated |
| Quantity | Units ordered |
| Discount | Discount applied |
| Profit | Net profit after costs and discounts |

---

## ⚙️ Setup

1. Download `Sales_Analysis_Project.twbx`
2. Open with **Tableau Desktop** or **Tableau Public** (free)
3. Data is embedded in the workbook — no external connections needed
4. Navigate through worksheets, dashboards and the story using the tabs at the bottom

---

## 💡 Key Insights

**Profitability vs Revenue**
High revenue does not always mean high profit — discount levels significantly erode margins in several sub-categories. Products with discounts above 40% consistently show negative profit.

**Geographic Opportunities**
Certain regions show strong sales volume but weak profitability — suggesting pricing or cost structure issues rather than demand problems.

**Product Rationalization**
Several products consistently generate losses across multiple orders. A product deletion or repricing strategy could significantly improve overall margins without impacting top-line revenue.

**Shipping Mode Impact**
Same Day delivery generates lower volume but higher margin per unit, while Standard Class drives the majority of volume at lower margins — a classic speed vs cost trade-off.

---

## 📁 Files

| File | Description |
|------|-------------|
| `Sales_Analysis_Project.twbx` | Complete Tableau workbook with embedded data |

---

## 📄 License

MIT — feel free to use, modify and share.

---

## 👤 Author

**Matteo Daviddi**
Data Analyst & Process Automation
[LinkedIn](https://www.linkedin.com/in/matteodaviddi) · [GitHub](https://github.com/matteodaviddi)

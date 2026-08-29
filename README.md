# Gift-E-Commerce-Sales-Analysis-FNP-Dataset-
Project Overview This project analyzes order, customer, and product data from a gift and e-commerce business (folder originally named `fnp`), exploring sales trends, revenue patterns, and customer behavior across occasions, locations, and time periods.

📂 Dataset
The project uses three core data files:
customers.csv— customer records
orders.csv — order-level transactional data
products.csv — product catalog details

📊 Analysis Included
The workbook contains several pivot-table style breakdowns of revenue and orders:
- **Revenue by day of the week** (e.g., Wednesday: 415,192; Thursday: 418,354;
  Friday: 475,447; Saturday: 444,960), with a grand total of 3,520,984. 
- **Revenue by product category**, including Cake, Colors, Mugs, Plants,
  Raksha Bandhan, Soft Toys, and Sweets, alongside revenue by occasion
  (Anniversary, Birthday, Diwali, Holi, Raksha Bandhan, Valentine's Day). 
- **Revenue by month**, covering January through December (e.g., January: 95,468;
  February: 704,509; March: 511,823; total orders: 1,000). 
- **Revenue by city/location**, tracking order counts across cities such as
  Bhatpara, Bidhannagar, Bilaspur, Dhanbad, and others. 
- Individual order-level records showing occasion, delivery timing, price, and
  revenue per transaction (e.g., Birthday, Anniversary, Holi, Raksha Bandhan,
  Valentine's Day orders).

 🛠️ Tools Used
The data structure (row labels, "Sum of Revenue," "Average of Revenue," and
"Total Orders" columns) suggests this analysis was built using **Excel PivotTables**
and/or **Power BI**, with data modeled from an `orders` table (referenced as
`orders[Column_Name]` in several fields).

📈 Key Insight
Across the full dataset, total revenue reached **3,520,984 INR** over **1,000 orders**,
with Friday generating the highest single-day revenue among the days analyzed.

🚀 How to Use
1. Clone this repository.
2. Open the CSV files (customers.csv, orders.csv, products.csv) in Excel,
   Power BI, or your preferred data tool.
3. Explore the pivot tables and revenue breakdowns by occasion, month, city, and
   day of week.

📌 Possible Next Steps
- Build visual dashboards (e.g., in Power BI or Tableau) from these pivot summaries.
- Perform customer segmentation using the `customers.csv` data.
- Analyze delivery time gaps (`diff_order_dilvery`) to assess fulfillment efficiency.


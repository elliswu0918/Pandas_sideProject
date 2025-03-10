# Side Project: Business Data Analysis

## 📌 Purpose

This project aims to analyze two business datasets from **Company A** and **Company B**. The goal is to extract valuable insights by examining different aspects such as **sales trends, product performance, employee performance, and customer behavior**.
---

## 📊 Dataset 1: Analysis of Company A’s Inventory, Sales, and Purchases

### 📂 Data Source

- **File:** [`company2.xlsx`](https://acupun.site/lecture/pandas/example/resource/company2.xlsx)
- **Tables:**
  - `categories`
  - `customers`
  - `employees`
  - `orderdetails`
  - `orders`
  - `products`
  - `region`
  - `shippers`
  - `suppliers`
  - `territories`

### 🔍 Key Analyses

1. **📅 Annual and Monthly Sales Trends**
   - Compute and visualize **total sales per year and per month** using bar charts.
   - Data preprocessing includes merging datasets, calculating total sales, and formatting for better readability.

2. **📦 Product Frequency Analysis**
   - Analyze the **count and proportion** of products in each category.
   - Visualized using a **pie chart** with highlighted lowest-performing categories.

3. **🧑‍💼 Employee Performance Analysis**
   - Identify the **top 3 and bottom 3** performing employees based on total sales.
   - Compare **sales performance by country**.
   - Generate **bar charts for sales ranking among employees**.

4. **🛍 Product Sales Performance**
   - Identify **top and bottom 5 products** based on sales revenue.
   - Analyze **top-performing products** in different categories.

5. **💳 Active Customer Analysis**
   - Identify **customers who have placed at least 20 orders**.
   - Identify **customers who have purchased at least 50 unique products**.

6. **📊 Product Sales Classification**
   - Categorize products into `low sales`, `moderate sales`, and `high sales` based on order quantity.

7. **📈 Potential Market Analysis**
   - Identify **customers who have not purchased products from the `Beverages` category**.

---

## 📊 Dataset 2: Business Sales Analysis of Company B

### 📂 Data Source

- **File:** [`sales.csv`](https://acupun.site/lecture/pandas/example/resource/sales.csv)

### 🔍 Key Analyses

1. **📅 Sales Trends Over Time**
   - Analyze **yearly and monthly sales trends** using bar and line charts.

2. **🏢 Pivot Table Analysis by Business Unit**
   - Compute **total sales volume and revenue for each business unit**.
   - Visualize data using **stacked and split bar charts**.

3. **📊 Performance Analysis by Gender**
   - Rank **sales representatives by sales revenue**.
   - Identify **top and bottom 3 performers** for both male and female employees.

4. **🏢 Performance Analysis by Business Unit**
   - Identify the **top 2 performers** in each business unit.

5. **📉 Sales Analysis Using Pivot Tables**
   - Cross-tabulate **sales data by business unit and product category**.
   - Compute and format **total, column, and row percentage tables** for quantitative analysis.

6. **📅 Quarterly Sales Performance**
   - Compare **seasonal sales trends over multiple years**.
   - Generate **stacked and split bar charts** to visualize quarterly sales.

7. **📆 Monthly Sales Impact**
   - Analyze **monthly trends in sales revenue**.

8. **📊 Seasonal Business Performance (2013-2014)**
   - Compare **business unit performance** over eight seasons.

9. **📱 Product-Specific Sales Analysis**
   - Focus on **mobile phone sales trends** across different seasons.

---

## ⚙️ Technical Implementation

- **📌 Data Processing:** `Python (Pandas, NumPy)`
- **📊 Visualization:** `Matplotlib, Seaborn`
- **☁️ Cloud Storage:** `Google Drive for data access in Google Colab`

## 🛠 How to Run the Analysis

```bash
# Clone the repository
git clone https://github.com/yourusername/side-project-business-analysis.git
cd side-project-business-analysis

# Set up virtual environment and install dependencies
python -m venv venv
source venv/bin/activate  # On Windows use 'venv\Scripts\activate'
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```

## 📂 GitHub Repository Structure

```plaintext
📦 side-project-business-analysis
├── 📂 data
│   ├── company2.xlsx
│   ├── sales.csv
├── 📂 notebooks
│   ├── analysis_company_a.ipynb
│   ├── analysis_company_b.ipynb
├── 📂 scripts
│   ├── data_processing.py
│   ├── visualization.py
├── README.md
├── requirements.txt
```

## 📌 Expected Output

- **Formatted tables** with sales statistics.
- **Visualizations**, including bar charts, line graphs, and pie charts.
- **Insights into sales performance, customer behavior, and business trends**.

## 🏁 Conclusion

This project provides a **structured approach to business data analysis**, offering insights into **sales trends, product performance, employee performance, and customer behavior**. The results can help organizations make **informed decisions** to optimize sales and operational strategies.



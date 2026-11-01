# Blinkit Business-Dashboard | Power BI

## 📌 Project Overview

This project presents an interactive **Blinkit Business - Dashboard** developed using **Microsoft Power BI**. The dashboard analyzes sales performance, outlet characteristics, product categories, customer ratings, and other key business metrics to generate meaningful insights.

The objective is to help understand business performance and identify trends across different outlets, product types, and locations.

---

## 🎯 Objectives

- Analyze overall sales and business performance.
- Understand sales distribution across different outlet types.
- Identify top-performing product categories.
- Analyze outlet establishment trends.
- Evaluate customer ratings and product visibility.
- Create an interactive dashboard for business decision-making.

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Excel / CSV Dataset**

---

## 📂 Dataset

The dataset contains information related to Blinkit outlets and products, including:

- Item Type
- Item Fat Content
- Item Visibility
- Item Weight
- Sales
- Rating
- Outlet Size
- Outlet Location Type
- Outlet Type
- Outlet Establishment Year

---

# 🔄 Project Workflow

## Step 1: Import Dataset

1. Open **Power BI Desktop**.
2. Select **Get Data**.
3. Import the Blinkit dataset from Excel/CSV.
4. Load the dataset into Power BI.

---

## Step 2: Data Cleaning Using Power Query

The dataset was cleaned and transformed using **Power Query**.

### Data cleaning activities:

- Checked for missing values.
- Removed unnecessary columns.
- Corrected data types.
- Standardized categorical values.
- Handled inconsistent values in categorical columns.
- Renamed columns where required.
- Verified numerical and text fields.

---

## Step 3: Data Transformation

The following transformations were performed:

- Converted columns to appropriate data types.
- Created useful calculated columns.
- Standardized **Item Fat Content** values.
- Prepared outlet-related fields for analysis.
- Checked data consistency before creating visualizations.

---

# 🧮 Step 4: DAX Measures

Important business measures were created using **DAX**.

### Total Sales

```DAX
Total Sales = SUM('BlinkIT Grocery Data'[Sales])
```

### Average Sales

```DAX
Average Sales = AVERAGE('BlinkIT Grocery Data'[Sales])
```

### Number of Items

```DAX
Number of Items = COUNTROWS('BlinkIT Grocery Data')
```

### Average Rating

```DAX
Average Rating = AVERAGE('BlinkIT Grocery Data'[Rating])
```

> Replace the table name with the actual table name used in your Power BI file if it is different.

---

# 📊 Step 5: Dashboard Development

The dashboard was designed using interactive Power BI visuals.

### KPI Cards

The dashboard includes key performance indicators such as:

- 💰 Total Sales
- 📦 Number of Items
- ⭐ Average Rating
- 📊 Average Sales

### Charts & Visualizations

The dashboard contains visualizations for:

- Sales by Outlet Type
- Sales by Item Type
- Sales by Fat Content
- Sales by Outlet Location
- Sales by Outlet Size
- Outlet Establishment Trend
- Item Visibility Analysis
- Product Category Performance

---

# 🎛️ Step 6: Interactive Filters

Slicers were added to allow users to dynamically filter the dashboard based on:

- Outlet Location Type
- Outlet Size
- Outlet Type
- Item Type
- Item Fat Content

This allows users to explore specific segments of the business.

---

# 🔍 Step 7: Key Insights

The dashboard helps identify:

- Overall sales performance.
- High-performing outlet types.
- Product categories contributing the most revenue.
- Sales differences between outlet locations.
- Impact of outlet size on sales.
- Sales trends based on outlet establishment year.
- Customer rating patterns across different product categories.

---

# 📈 Step 8: Business Analysis

The dashboard can be used by business teams to:

- Monitor sales performance.
- Compare outlet performance.
- Identify high-performing products.
- Understand customer preferences.
- Evaluate outlet expansion opportunities.
- Support data-driven business decisions.

---

# 🖥️ Dashboard Preview

Add your Power BI dashboard screenshot here:

```markdown
![Blinkit Dashboard] (images/https://github.com/CHANDURISARANYA/Blinkit-dashboard/blob/main/Blinkit%20dashboard.png)
```

---

# 📁 Project Structure

```text
Blinkit-PowerBI-Dashboard/
│
├── Dataset/
│   └── BlinkIT_Grocery_Data.xlsx
│
├── Dashboard/
│   └── Blinkit_Business_Analysis.pbix
│
├── Images/
│   └── blinkit-dashboard.png
│
└── README.md
```

---

# 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. If required, update the dataset/file path.
4. Refresh the data.
5. Use the slicers and visuals to explore the dashboard.

---

# 💡 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Power Query
- DAX
- Data Visualization
- Business Intelligence
- Exploratory Data Analysis
- KPI Development
- Dashboard Design
- Business Analysis

---

## 👩‍💻 Author

**Saranya**

B.Tech – Electronics & Communication Engineering

**Skills:** Power BI | DAX | SQL | Excel | Python | Data Analytics

---

⭐ **If you found this project useful, feel free to star the repository!**

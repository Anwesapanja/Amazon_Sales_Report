#  Amazon Sales Report Dashboard  

##  Links  
- **GitHub Repository:** https://github.com/Anwesapanja/Amazon_Sales_Report.git  
- **Live Dashboard (Looker Studio):** https://datastudio.google.com/reporting/7db5b0cd-27fc-4c8d-b8e5-3d5771e5653a  

---

##  Project Overview  
This project analyzes Amazon sales data and presents insights using an interactive dashboard built in Looker Studio. It helps in understanding sales performance, category trends, and financial metrics.

---

##  Objectives  
- Analyze overall sales performance  
- Identify top-performing categories  
- Track revenue and profit trends  
- Build an interactive dashboard  

---

##  Workflow  
1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Data Transformation  
5. Dashboard Creation  
6. Insight Generation  

---

##  Project Structure  
Amazon_Sales_Report/
│
├── data/ # Dataset files
├── dashboard/ # Dashboard images
│ ├── page1.png
│ ├── page2.png
│ └── page3.png
├── notebooks/ # Jupyter notebooks
├── src/ # Scripts
└── README.md


---

##  Data Summary  
- Contains Amazon sales records  
- Includes order details, category, sales, and profit  
- Used for trend and performance analysis  

---

##  Data Dictionary  

| Column Name | Description |
|------------|------------|
| Order ID | Unique ID for each order |
| Date | Order date |
| Category | Product category |
| Sales | Revenue |
| Quantity | Items sold |
| Profit | Profit earned |

---

##  Financial Overview  
- Revenue Analysis  
- Profit Analysis  
- Sales Trends Over Time  

---

##  Category Distribution  
- Category-wise sales breakdown  
- Identification of top-performing categories  

---

Dashboard

### Page 1: Sales Overview Dashboard 

![Sales Overview](Dashboard/Screenshot%202026-04-19%20015659.png)

**Description:**  
This page provides a comprehensive overview of overall sales performance.

**Key Insights:**
- Displays key KPIs such as **Total Sales Amount, Total Quantity, Total Orders, and Average Order Value**  
- Shows **sales trends over time** using time-series analysis  
- Highlights **size-wise performance** to identify popular product sizes  
- Includes **category distribution** for quick business understanding  
- Tracks **courier status trends** for operational monitoring  

---

### Page 2: Category & Geographic Analysis 

![Category Analysis](Dashboard/Screenshot%202026-04-19%20015734.png)

**Description:**  
This page focuses on geographical and category-level sales insights.

**Key Insights:**
- Displays **state-wise and location-based sales distribution** using maps  
- Shows **shipping activity across different regions**  
- Provides **category performance by state**  
- Includes **courier status breakdown**  
- Visualizes **shipping trends over time**  

---

### Page 3: Customer & Product Insights

![Financial Insights](Dashboard/Screenshot%202026-04-19%20015811.png)

**Description:**  
This page provides detailed insights into customer behavior and product performance.

**Key Insights:**
- Identifies **top customers based on purchase amount**  
- Shows **category distribution by size**  
- Displays **total orders and revenue contribution**  
- Helps analyze **customer purchasing patterns**  

---

##  Tools Used  
- Python (Pandas, NumPy)  
- Looker Studio  
- Jupyter Notebook  
- Git & GitHub  

---

##  Conclusion  
This project provides meaningful insights into Amazon sales data and supports data-driven decision-making through an interactive dashboard.

---

##  Future Enhancements  
- Real-time data integration  
- Predictive analysis using Machine Learning  
- Improved dashboard interactivity  

---

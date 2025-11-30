# 📊 Power BI Sales & Product Performance Dashboard

This project is a **Power BI end-to-end data analysis dashboard** created using two connected tables: **Products Table** and **Orders Table**.  
Dashboard focuses on **sales trends, product performance, regional comparison** and overall business insights.

---

## 📁 Dataset Details

### **1️⃣ Products Table**
Contains product-level information.
| Column Name    | Description |
|----------------|-------------|
| Category       | Product category (Electronics, Furniture, Accessories etc.) |
| ProductID      | Unique ID for each product |
| ProductName    | Name of the product |
| SubCategory    | Sub-category of the product |
| UnitPrice      | Price per unit of the product |

---

### **2️⃣ Orders Table**
Contains order transaction details.
| Column Name | Description |
|-------------|-------------|
| OrderDate   | Date of purchase |
| OrderID     | Unique order number |
| ProductID   | Links to Products table |
| Quantity    | Units sold |
| Region      | Sales region (North, South, East, West) |

---

## 🔗 Data Modeling (Relationship)
- **Products.ProductID ↔ Orders.ProductID** (One-to-Many relationship)
This relationship enables product-wise and category-wise analysis.

---

## 📈 Dashboard Insights

### ✔ **1. Category Performance**
- Shows total quantity sold by category.
- Helps identify which product groups perform best.

### ✔ **2. Sub-Category Analysis**
- Breakdown of sales within each category.
- Helps compare product families (e.g., Laptops vs. Mobiles).

### ✔ **3. Region-Wise Sales Distribution**
- Donut chart showing sales percentage by region.
- Useful for geographic performance comparison.

### ✔ **4. Product Quantity Analysis**
- Bar chart showing quantity sold per product.
- Quickly highlights top-selling products.

### ✔ **5. Category & Region Matrix**
- Combined view to analyze category performance across regions.

### ✔ **6. Order Trends**
- Monthly or daily order count based on OrderDate hierarchy.

### ✔ **7. KPI Cards**
- **Total Quantity Sold**
- **Total Unit Price Value**
- **Total Number of Orders**
- **Unique Products Count**
- **Total Regions Covered**

---

## 🛠 Tools & Skills Used
- **Power BI Desktop**
- **Data Cleaning**
- **Data Modeling (Relationships)**
- **DAX (Basic aggregations like SUM, COUNT, DISTINCTCOUNT)**
- **Interactive Visualizations**
- **Dashboard Design & Formatting**

---

## 🎯 Objective of the Project
To provide an interactive dashboard that helps understand:
- What products sell the most?
- Which region performs better?
- Which category generates more volume?
- How many orders come over time?

---

## 📎 Output
The final dashboard provides **clear business insights** and can be used by:
- Managers  
- Sales teams  
- Business analysts  
- Decision makers  

---

## 📂 File Included
- `"sale dashboard (1).pbix"` – Complete dashboard file
- README with dataset explanation and insights

---

## ✨ Author
**Aditi Choubey**  
Power BI | SQL | Excel | Data Analysis  
GitHub: *https://github.com/Aditichoubey-adi*

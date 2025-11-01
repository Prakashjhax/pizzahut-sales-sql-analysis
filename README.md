# 🍕 PizzaHut Sales Analysis using SQL

## 📖 Project Overview
This project focuses on analyzing **PizzaHut’s sales data using SQL** to uncover key business insights.  
The main goal is to explore sales performance, customer preferences, and product demand patterns by writing SQL queries ranging from basic to advanced complexity.

The analysis is performed on four main tables:
- **orders**
- **order_details**
- **pizzas**
- **pizza_types**

These tables are connected through foreign keys to ensure proper data relationships for analysis.

---

## 🎯 Project Objectives
- Understand customer purchasing behavior  
- Analyze sales trends and revenue performance  
- Identify top-performing pizzas and categories  
- Generate data-driven business insights  
- Practice and apply SQL for real-world analytics  

---

## 🧩 Database Structure

**Tables Used:**

| Table | Description |
|--------|--------------|
| `orders` | Contains order ID, date, and time |
| `order_details` | Contains order details including pizza ID and quantity |
| `pizzas` | Contains pizza size, price, and related pizza type |
| `pizza_types` | Contains pizza name, category, and ingredients |

**Relationships:**
- `orders` 🔗 `order_details` via `order_id`  
- `order_details` 🔗 `pizzas` via `pizza_id`  
- `pizzas` 🔗 `pizza_types` via `pizza_type_id`

---

## 🧮 SQL Analysis

### 🔹 Basic Level
- Retrieve total number of orders placed  
- Calculate total revenue generated from pizza sales  
- Identify the highest-priced pizza  
- Find the most common pizza size ordered  
- List the top 5 most ordered pizza types with quantities  

### 🔸 Intermediate Level
- Find total quantity of each pizza category ordered  
- Determine distribution of orders by hour of the day  
- Category-wise distribution of pizzas  
- Group orders by date and calculate average pizzas ordered per day  
- Identify top 3 most ordered pizza types based on revenue  

### 🔺 Advanced Level
- Calculate percentage contribution of each pizza type to total revenue  
- Analyze cumulative revenue generated over time  
- Determine top 3 most ordered pizza types by revenue for each category  

---

## 💡 Key Insights
- “Large” size pizzas are the most frequently ordered  
- “Classic” and “Supreme” categories contribute the most to total revenue  
- Peak order time: **7 PM – 9 PM**  
- The **BBQ Chicken Pizza** generated the highest revenue  
- Top 3 pizzas contributed over 25% of the total sales revenue  

---

## ⚙️ Tools & Technologies Used
- **SQL (MySQL)** – Data querying and analysis  
- **Excel / Power BI** – Visualization (optional)  
- **GitHub** – Project hosting and version control  

---
# 📫 Contact

**Prakash Kumar Jha**  
🔗 **LinkedIn:** [linkedin.com/in/prakashjhax](https://www.linkedin.com/in/prakashjhax)  
📧 **Email:** [jhaprakashkumar122@gmail.com](mailto:jhaprakashkumar122@gmail.com)


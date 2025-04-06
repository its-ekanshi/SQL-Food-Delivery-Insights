# 🍕 SQL Food Delivery Insights

This SQL project is focused on analyzing food delivery data to derive actionable business insights. It simulates real-world use cases faced by growth and marketing teams in a food delivery business, like customer acquisition, retention, and promotions.

---

## 📦 Dataset

The dataset contains a single `orders` table with the following columns:
- `Order_id`
- `Customer_code`
- `Placed_at`
- `Restaurant_id`
- `Cuisine`
- `Order_status`
- `Promo_code_Name`

All data is simulated and covers various cuisines, promo usage, and customer behaviors across multiple cities.

---

## 📌 Business Questions Solved

| # | Problem Statement |
|---|-------------------|
| 1️⃣ | Top outlets by cuisine without using `LIMIT` or `TOP` |
| 2️⃣ | Daily new customer count from the launch date |
| 3️⃣ | Count of users acquired in Jan 2025 who placed only one order in Jan and none after |
| 4️⃣ | Customers with no orders in the last 7 days but were acquired a month ago using a promo |
| 5️⃣ | Trigger target customers after every third order |
| 6️⃣ | List customers who only ordered using promos and ordered more than once |
| 7️⃣ | % of users organically acquired in Jan 2025 (without a promo code) |

---

## 🧰 Tools Used

- SQL Server (T-SQL syntax)
- SSMS (SQL Server Management Studio)

---

## 🧠 Key Learnings

- Use of `CTE`, `ROW_NUMBER()`, `WINDOW FUNCTIONS`
- Conditional Aggregation
- Temporal Filtering (based on `GETDATE()`)
- Real-world business thinking in SQL

---


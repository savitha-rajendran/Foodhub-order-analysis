# 🍔 FoodHub Order Analysis
### Exploratory Data Analysis | Python · Pandas · Matplotlib · Seaborn

---

## 📌 Project Overview

FoodHub is a food aggregator app that connects customers with multiple restaurants through a single platform. This project performs a comprehensive **Exploratory Data Analysis (EDA)** on FoodHub's order data to uncover insights about customer behavior, restaurant performance, cuisine popularity, and delivery patterns — helping the business make data-driven decisions to improve customer experience.

---

## 🎯 Business Problem

The food aggregator company has stored data on different orders made by registered customers across various restaurants. The Data Science team was tasked with analyzing this data to:

- Understand demand across different restaurants and cuisines
- Identify patterns in food preparation and delivery times
- Analyze customer ratings and satisfaction
- Provide actionable recommendations to improve operations

---

## 📂 Dataset

**File:** `foodhub_order.csv`

| Column | Description |
|---|---|
| `order_id` | Unique ID for each order |
| `customer_id` | ID of the customer who placed the order |
| `restaurant_name` | Name of the restaurant |
| `cuisine_type` | Type of cuisine ordered |
| `cost_of_the_order` | Cost of the order (USD) |
| `day_of_the_week` | Whether the order was placed on a Weekday or Weekend |
| `rating` | Customer rating (1–5) or "Not given" |
| `food_preparation_time` | Time (minutes) taken by restaurant to prepare food |
| `delivery_time` | Time (minutes) taken to deliver the order |

**Dataset size:** ~1,898 rows × 9 columns

---

## 🔍 Analysis Performed

### 1. Data Overview & Cleaning
- Loaded and inspected the dataset (shape, dtypes, head/tail)
- Identified and handled missing values
- Treated `rating` column (mixed "Not given" strings and numeric values)

### 2. Univariate Analysis
- Distribution of order costs
- Most popular cuisines
- Weekend vs Weekday order volumes
- Rating distribution

### 3. Bivariate & Multivariate Analysis
- Cost vs cuisine type
- Delivery time vs day of week
- Food preparation time across restaurants
- Rating vs delivery time relationship

### 4. Business Insights & Recommendations
- Which restaurants and cuisines drive the most orders
- Peak ordering days and time patterns
- Factors affecting customer ratings
- Recommendations to reduce delivery time

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data manipulation & cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots |
| Google Colab | Development environment |

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/foodhub-order-analysis.git
   cd foodhub-order-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. **Run the notebook**
   - Open `foodhub_project.ipynb` in Jupyter Notebook or Google Colab
   - Upload `foodhub_order.csv` when prompted
   - Run all cells

---

## 📊 Key Findings

- 🍕 **American and Japanese cuisines** are the most ordered
- 📅 **Weekends** see significantly higher order volumes than weekdays
- ⏱ Average total delivery time (prep + delivery) is approximately **50 minutes**
- ⭐ Orders with faster delivery tend to receive **higher ratings**
- 🏆 Top-rated restaurants consistently maintain **preparation times under 25 minutes**

---

## 📁 Repository Structure

```
foodhub-order-analysis/
│
├── foodhub_project.ipynb     # Main Jupyter Notebook
├── foodhub_order.csv         # Dataset (add if allowed to share)
├── README.md                 # Project documentation
└── images/                   # Saved plot images (optional)
```

---

## 👩‍💻 Author

**Savitha Rajendran**
- 🎓 PGP in AI & Machine Learning — Great Learning
- 🔗 [LinkedIn](https://linkedin.com/in/your-linkedin)
- 💻 [GitHub](https://github.com/your-username)
- 📧 oxford2012raj@gmail.com

---

## 📜 License

This project is for educational purposes as part of the PGP AI/ML program.


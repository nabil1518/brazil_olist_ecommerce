# 🛒 Brazilian E-Commerce (Olist) Data Analysis

## 📌 Project Overview

This project analyzes the **Brazilian E-Commerce Public Dataset** (Olist), which contains real-world e-commerce order data. The dataset includes information about orders, customers, products, sellers, payments, reviews, and geolocation.

The goal is to perform exploratory data analysis (EDA), derive business insights.

---

## 📊 Dataset Description

The dataset consists of 9 CSV files (relational schema):

| File | Description |
|------|-------------|
| `olist_customers_dataset.csv` | Customer information and unique IDs |
| `olist_geolocation_dataset.csv` | Brazilian zip codes with lat/long |
| `olist_order_items_dataset.csv` | Items within each order |
| `olist_order_payments_dataset.csv` | Payment methods and installments |
| `olist_order_reviews_dataset.csv` | Customer reviews and scores |
| `olist_orders_dataset.csv` | Core order status and timestamps |
| `olist_products_dataset.csv` | Product details (category, dimensions, weight) |
| `olist_sellers_dataset.csv` | Seller information |
| `product_category_name_translation.csv` | Portuguese → English category mapping |

> 📥 Download from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 🧰 Tech Stack

- **Python 3.9+**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – visualization
- **Jupyter Notebook** – exploratory analysis
---

## 📁 Project Structure

```
brazil_olist_ecommerce/
│
├── data/ 
        ├── raw/
        ├── processed/
├── notebooks/
├── README.md
└── .gitignore
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/brazil_olist_ecommerce.git
cd brazil_olist_ecommerce
```

### 2. Download dataset
- Download from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Place all CSVs in `data/raw/`

### 3. Run analysis
Open `notebooks/01_.ipynb` and execute cells.
# Exploratory Data Analysis for Inventory Analytics

This repository contains a comprehensive exploratory data analysis (EDA) notebook focused on inventory and demand behavior using supply chain data.  
The objective is to demonstrate how data-driven insights can support inventory planning, risk assessment, and managerial decision-making.

The notebook is designed for learning, teaching, and analytical illustration rather than model building.

---

## 📘 Notebook

**File:** `eda_for_inventory_analytics.ipynb`

The notebook walks through a structured exploratory analysis of inventory-related variables with a strong emphasis on interpretability and real-world relevance.

---

## 📊 Key Analyses Covered

### 1. Demand Analysis
- Distribution of daily demand
- Identification of demand patterns
- Relationship between demand and inventory levels

### 2. Inventory Risk Assessment
- Practical definition of low-inventory risk using thresholds
- SKU-level inventory risk analysis
- Warehouse-level inventory risk comparison
- Risk measured as percentage of time inventory falls below a threshold

### 3. Demand Variability
- Computation of coefficient of variation (CV)
- Classification of SKUs into:
  - Low variability
  - Moderate variability
  - High variability
- Portfolio-level visualization of demand stability

### 4. Lead Time Analysis
- Distribution of lead times
- Segmentation into low, moderate, and high lead-time categories
- Visual identification of operational risk

### 5. Pareto (ABC) Analysis
- SKU-level sales aggregation
- Cumulative sales contribution
- Visualization of the 80/20 principle
- Identification of high-impact SKUs

---

## 🧠 Analytical Approach

The analysis emphasizes:
- Practical definitions over theoretical extremes
- Metrics aligned with real inventory management practices
- Visual clarity and simplicity
- Consistent logic across analyses

Rather than focusing on prediction, the notebook focuses on **diagnostic and descriptive analytics** to support understanding and decision-making.

---

## 🛠️ Tools and Libraries Used

- Python
- pandas
- numpy
- matplotlib
- plotly (for interactive visualizations)

---

## 🎯 Intended Audience

- Students of supply chain, operations, and business analytics
- Instructors seeking applied teaching material
- Analysts exploring inventory and demand behavior
- Practitioners interested in exploratory inventory diagnostics

---

## ▶️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ejazurrehman/EDA_for_Inventory.git
2. Open the notebook:

eda_for_inventory_analytics.ipynb

📌 Notes

Thresholds used in the analysis (e.g., inventory risk levels, CV cutoffs) are illustrative and can be adjusted.

Visualizations are designed for clarity in presentations and classroom discussion.

The notebook assumes the dataset is available within the environment.

👤 Author

Ejaz Ur Rehman
Exploratory Analytics for Inventory and Supply Chain Systems

📜 License

This project is shared for educational and analytical purposes.
You are welcome to fork, adapt, and reference the work with attribution.

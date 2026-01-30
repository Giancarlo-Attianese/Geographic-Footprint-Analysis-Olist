# 📊 Geographic Footprint Analysis – Olist E-commerce

Business & data analysis project focused on understanding the **geographic distribution of customers** in the Brazilian e-commerce platform Olist.  
All the analysis, cleaning, visualizations, and strategy are implemented **entirely inside Jupyter/Colab notebooks**.

---

## 🎯 Objectives

- Analyze customer distribution across Brazil
- Measure geographic concentration and inequality
- Detect market risks and dependencies
- Identify underserved regions with growth potential
- Provide data-driven business recommendations

---

## 📂 Project Structure

```
project/
│
├── notebooks/          ← ALL THE CODE IS HERE
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_visualization.ipynb
│   └── 04_recommendations.ipynb
│
├── data/
│   └── olist_customers_dataset.csv
│
├── requirements.txt
└── README.md
```

### 📌 Note
All logic, functions, and analysis are developed **directly inside the notebooks**  
(no separate Python scripts).

---

## 📊 Dataset Information

| Metric | Value |
|--------|---------|
| Records | 99,441 |
| Unique customers | 96,096 |
| States | 27 |
| Cities | 4,119 |
| Features | 5 (geographic data) |

**Source:** Olist Brazilian E-commerce Public Dataset

---

## ⚙️ Tech Stack

- Python
- Pandas
- NumPy
- Plotly / Matplotlib
- Jupyter Notebook
- Google Colab

---

## 🔍 Workflow

### 1️⃣ Data Cleaning (`01_data_cleaning.ipynb`)
- Standardized city names
- Validated Brazilian states
- Removed duplicates and inconsistencies
- Built clean dataframe (`df_clean`)

### 2️⃣ Exploratory Data Analysis (`02_eda.ipynb`)
- Customer distribution by state and city
- Market share computation
- Concentration metrics
- Pareto analysis

### 3️⃣ Visualizations (`03_visualization.ipynb`)
- State bar charts
- Market share pie charts
- Diversity scatter plots
- Top cities ranking

### 4️⃣ Strategic Recommendations (`04_recommendations.ipynb`)
- Risk assessment
- Opportunity identification
- Expansion targets
- Business roadmap

---

## 📈 Key Metrics

```python
metrics = {
    'total_customers': 99441,
    'unique_customers': 96096,
    'sp_share_percent': 41.98,
    'top3_states_share': 66.6,
    'top10_cities_share': 35.2,
    'gini_coefficient': 0.68,
    'avg_customers_per_city': 24.1,
    'median_customers_per_city': 2
}
```

---

## 📊 Main Insights

### ⚠️ Risks
- São Paulo concentration: **42% of customers**
- Southeast dependency: **67% of total market**
- Low penetration: median **2 customers per city**
- High inequality (**Gini = 0.68**)

### 🚀 Opportunities
- Northeast expansion potential
- 4,000+ underserved cities
- Center-West growing region
- Tier 2–3 city strategy

---

## 🎯 Business Recommendations

### 🔴 High Priority
- Reduce São Paulo dependency (42% → 35%)
- Increase Northeast share (16.5% → 20%)

### 🟡 Medium Priority
- Tier-based city expansion strategy
- Regional logistics hubs

### 🟢 Long Term
- Interactive geographic dashboard
- Automated reporting
- Continuous monitoring

---

## ▶️ How to Run

### Google Colab (recommended)
1. Upload the repository to Colab or open notebooks directly
2. Run cells sequentially

### Local Setup

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
pip install -r requirements.txt
jupyter notebook
```

Then open notebooks in this order:
1. 01_data_cleaning
2. 02_eda
3. 03_visualization
4. 04_recommendations

---

## 🔮 Future Improvements

- Integrate orders & payments datasets
- Customer Lifetime Value by region
- Time-series geographic growth analysis
- Choropleth maps with geolocation
- Streamlit / Power BI dashboard
- Expansion impact simulations

---

## 📌 Skills Demonstrated

- Data Cleaning Pipelines
- Exploratory Data Analysis
- Statistical Metrics (Gini, Pareto)
- Data Visualization
- Business Intelligence
- Strategic Thinking
- End-to-End Analytics Workflow

---

## 👤 Author

**Giancarlo Attianese**  
Data Analysis • Business Intelligence • Python • SQL • Strategy

---

## ⭐ Project Impact

This project demonstrates how raw geographic data can be transformed into  
**clear business insights and actionable growth strategies**, bridging  
analytics and strategic decision-making.

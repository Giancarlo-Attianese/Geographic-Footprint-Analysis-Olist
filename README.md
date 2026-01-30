# 📊 Geographic Footprint Analysis – Olist E-commerce

Business & data analysis project focused on understanding the **geographic distribution of customers** in the Brazilian e-commerce platform Olist, identifying **market concentration risks, growth opportunities, and expansion strategies** through data-driven insights.

---

## 🎯 Project Goals
- Analyze customer geographic distribution across Brazil
- Measure market concentration and inequality
- Identify under-penetrated regions with high potential
- Provide actionable business recommendations for expansion

---

## 📂 Project Structure

notebooks/
├── 01_data_cleaning.ipynb
├── 02_eda.ipynb
├── 03_visualization.ipynb
└── 04_recommendations.ipynb

data/
└── olist_customers_dataset.csv


---

## 📊 Dataset

- **Records:** 99,441 customers  
- **States:** 27  
- **Cities:** 4,119  
- **Features:** geographic information (city/state/zip)

Source: Olist Brazilian E-commerce Public Dataset

---

## ⚙️ Tech Stack

- Python
- Pandas / NumPy
- Plotly / Matplotlib
- Google Colab
- Jupyter Notebooks

---

## 🔍 Key Analyses

### Data Cleaning
- Standardized cities/states
- Removed inconsistencies
- Validated Brazilian state codes

### Exploratory Analysis
- Customer distribution by state and city
- Concentration metrics (Pareto + Gini)
- Market share ranking

### Visualizations
- State distribution bar chart
- Market share pie chart
- Geographic diversity scatter
- Top cities ranking

### Metrics Calculated
- Gini coefficient
- Pareto 80/20 rule
- State & city penetration
- Concentration ratios

---

## 📈 Key Findings

### ⚠️ Risks
- São Paulo concentration: **42% of customers**
- Southeast region: **67% of total market**
- Median penetration: **2 customers per city**

### 🚀 Opportunities
- Northeast growth potential (16.5% → 20%)
- 4,000+ Tier 2–3 cities underserved
- Emerging regions in Center-West Brazil

### 📊 Concentration Metrics
- **Gini coefficient:** 0.68 (high inequality)
- **Top 5 states:** 80% of customers
- **Top 10 cities:** 35% of customers

---

## 🎯 Business Recommendations

### High Priority
- Reduce São Paulo dependency (42% → 35%)
- Expand in Northeast region

### Medium Priority
- Tier-based city expansion strategy
- Regional logistics hubs

### Long Term
- Geographic analytics dashboard
- Automated monitoring

---

## ▶️ How to Run

### Google Colab
Open each notebook and run all cells.

### Local
```bash
pip install -r requirements.txt
jupyter notebook
🔮 Future Improvements
Integrate orders & payments datasets

Customer value by region (LTV)

Time-series geographic growth

Interactive dashboard (Streamlit/Power BI)

Choropleth maps with geolocation data

👤 Author
Giancarlo Attianese
Data Analysis | Business Intelligence | Python

⭐ Project Value
This project demonstrates:

Data cleaning pipelines

Exploratory data analysis

Business-focused insights

Strategic thinking from data

End-to-end analytics workflow

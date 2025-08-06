# Customer Lifecycle Mapping — Behavioral Analysis with a CRM Perspective

This project simulates a CRM database and performs a full customer lifecycle analysis, focusing on **retention**, **churn**, **value segmentation**, and **marketing campaign responsiveness**. It was created to showcase analytical skills applied to real CRM scenarios, using realistic synthetic data.

---

## Project Goals

- Simulate a business environment with realistic customer, transaction, and campaign data.
- Calculate key metrics such as **RFM**, **LTV**, **churn rate**, and **inactivity periods**.
- Identify **behavioral customer segments** to guide CRM strategies.
- Visualize the customer journey from acquisition to churn or reactivation.
- Build an interactive dashboard with actionable insights.

---

## Business Questions

- Which customers have the highest potential Lifetime Value?
- What profile tends to respond best to marketing campaigns?
- What are the early signals of customer churn?
- How can we segment customers to improve campaign performance?
- How long do customers stay active based on acquisition channel or region?

---

## Tech Stack

- **Python**: Pandas, NumPy, Faker, Seaborn, Matplotlib
- **SQL**: SQLite (simulated database environment)
- **Streamlit**: For interactive dashboard development (week 3)
- **GitHub**: Project versioning and collaboration

---

## Project Structure

```bash
crm-lifecycle-analysis/
├── data/
│   ├── clientes.csv         # Simulated customer database
│   ├── transacoes.csv       # Monthly transaction records
│   └── campanhas.csv        # Campaign history and response behavior
├── notebooks/
│   └── eda.ipynb            # Exploratory analysis and CRM metrics
├── streamlit_app/
│   └── dashboard.py         # Interactive dashboard (coming soon)
├── insights/
│   └── segments.txt         # Segment descriptions and actionable insights
└── README.md

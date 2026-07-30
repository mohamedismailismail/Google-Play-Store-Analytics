# 📱 Google Play Store Analytics & Sentiment Suite

An end-to-end data analytics project exploring over **10,000+ Google Play Store apps** and user sentiment. Built with **Python, Excel, Power BI, and DAX**, this project provides strategic recommendations for mobile developers and business stakeholders to maximize downloads and user satisfaction.

---

## 🛠️ Data Pipeline & Architecture
1. **Data Extraction & Cleaning (Python & Pandas):** Processed raw Google Play datasets, handled missing values, formatted app sizes, and cleaned numerical installations and pricing data via custom Python scripts (`scripts/`).
2. **Data Modeling & Transformation (Excel & Power Query):** Structured tables and validated clean data models (`data/`).
3. **Analytics & Visualization (Power BI):** Engineered dynamic measures using **DAX** (e.g., Sentiment Numerical conversion, Average Ratings, Total Installs) across a custom interactive 5-page report.
4. **Strategic Reporting (PDF):** Translated analytical findings into actionable business recommendations (`reports/`).

---

## 📊 Dashboard Preview

### 📈 1. Market Overview
<img width="1313" height="805" alt="Screenshot 2026-07-31 010553" src="https://github.com/user-attachments/assets/18a35571-a9b8-4bf3-99d2-53b1f6207793" />


### 📁 2. Category Performance
<img width="1315" height="809" alt="Screenshot 2026-07-31 010649" src="https://github.com/user-attachments/assets/6bff6847-e880-4907-876d-02bd218366c5" />

### ⭐ 3. App Quality & Ratings
<img width="1310" height="804" alt="App Quality   Ratings" src="https://github.com/user-attachments/assets/ade0d2d8-7627-4c85-b781-b205b3ce9a74" />

### 💬 4. Sentiment Analysis
<img width="1312" height="809" alt="Seintiment Analysis" src="https://github.com/user-attachments/assets/045f23c3-678c-433f-b7a5-9c15e37b0f57" />

---

## 💡 Key Business Recommendations

* **Address High Negative-Review Apps:** Priority engineering resources must be allocated to fix top-rated apps suffering from high negative review volumes (resolving crashes and excessive ads).
* **Freemium Acquisition Model:** Monetization strategy should lean towards Freemium models to minimize friction during initial user acquisition.
* **Real-time Sentiment Monitoring:** Implement automated sentiment keyword tracking to detect post-update bugs before they reflect on average star ratings.
* **App Size Optimization:** Optimize APK sizes to prevent drop-offs in markets with mid-range hardware and bandwidth limitations.

---

## 📂 Project Structure
```text
├── data/              # Raw & Cleaned Excel/CSV datasets
├── scripts/           # Python data cleaning scripts (.py / .ipynb)
├── reports/           # Executive PDF Strategic Report
├── images/            # Dashboard page screenshots
├── Google_Play_Store_Analytics.pbix # Interactive Power BI Dashboard
└── README.md          # Project documentation

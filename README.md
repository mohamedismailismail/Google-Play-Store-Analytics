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
<!-- اسحب صورة overview.png وارميها هنا -->
![Overview Page](C:\Users\Dell\OneDrive\الصور\Screenshots\Screenshot 2026-07-31 010553.png)

### 📁 2. Category Performance
<!-- اسحب صورة category_performance.png وارميها هنا -->
![Category Performance](C:\Users\Dell\OneDrive\الصور\Screenshots\Category Performance.png)

### ⭐ 3. App Quality & Ratings
<!-- اسحب صورة app_quality.png وارميها هنا -->
![App Quality](C:\Users\Dell\OneDrive\الصور\Screenshots\App Quality & Ratings.png)

### 💬 4. Sentiment Analysis
<!-- اسحب صورة sentiment_analysis.png وارميها هنا -->
![Sentiment Analysis](C:\Users\Dell\OneDrive\الصور\Screenshots\Screenshot 2026-07-31 010905.png)

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

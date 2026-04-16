# Meta Ad Performance Analysis 📊

## Dashboard Preview

---

## 📌 Project Overview

This project analyzes **Meta (Facebook & Instagram)** advertising campaign performance using a comprehensive Power BI dashboard.

### Business Problem
The marketing team needs visibility into campaign performance across Facebook and Instagram to:
- Identify the most effective platform
- Track campaign ROI and optimize budget allocation
- Understand audience engagement patterns

---

## 📊 Key Metrics at a Glance

| Metric | Value | Status |
|--------|-------|--------|
| Impressions | 216K | ✅ Good reach |
| Clicks | 25.4K | ✅ Strong |
| CTR | 11.76% | ✅ Above industry avg (1-2%) |
| Engagement Rate | 13.56% | ✅ Very healthy |
| Conversion Rate | 5.21% | ✅ Good |
| Purchase Rate | 0.61% | ⚠️ Needs improvement |
| Total Budget | 2.5M | - |
| Avg Budget/Campaign | 50.7K | - |

---

## 🎯 Dashboard Visualizations

| # | Visualization | Purpose |
|---|---------------|---------|
| 1 | Donut Chart | Target Gender analysis |
| 2 | Bar Chart | Age Group engagement |
| 3 | Map | Country-wise performance |
| 4 | Calendar Heat Map | Monthly trends |
| 5 | Stacked Column | Weekly trend by ad type |
| 6 | Area Chart | Hourly engagement |
| 7 | Matrix | Ad type vs Platform |

---

## 💡 Key Insights

### 1. Funnel Analysis
Top of Funnel (Awareness) → Middle of Funnel (Engagement) → Bottom of Funnel (Purchase)
216K Impressions 29K Engagements 1.3K Purchases
↓ ↓ ↓
11.76% CTR 13.56% ER 0.61% PR
✅ Strong ✅ Healthy ⚠️ Weak

text

### 2. Audience Insights
- **Gender:** Female (43%) > Male (22%)
- **Age:** 18-30 group drives majority engagement
- **Top Countries:** India, Brazil, US, Germany, UK

### 3. Ad Type Performance (Best to Worst)
| Rank | Ad Type | CTR | Conversion Rate | Engagement Rate |
|------|---------|-----|-----------------|------------------|
| 🥇 1 | Video | 11.9% | 5.2% | 13.7% |
| 🥈 2 | Stories | 11.8% | 5.2% | 13.6% |
| 🥉 3 | Carousel | 11.7% | 5.1% | 13.4% |
| 4 | Image | 11.7% | 4.9% | 13.5% |

### 4. Timing Optimization
- **Best Time:** Afternoon & Evening (15-20 hours)
- **Lowest Engagement:** Early morning (0-5 hours)

---

## 📈 Recommendations

| # | Recommendation |
|---|----------------|
| 1 | Optimize landing pages and retargeting to improve purchase conversion |
| 2 | Target young females (18-30) in India & Brazil |
| 3 | Increase budget allocation to Video & Stories ad formats |
| 4 | Schedule ads during afternoon & evening hours |
| 5 | Segment strategies: Volume from India/Brazil, Value from Germany/UK |

---

## 🗄️ Data Model (Star Schema)
┌─────────────────┐
│ campaigns │
│ (Dimension) │
└────────┬────────┘
│
▼
┌─────────────────┐ ┌─────────────────┐
│ ads │────▶│ ad_events │
│ (Dimension) │ │ (Fact Table) │
└─────────────────┘ └────────┬────────┘
│
▼
┌─────────────────┐
│ users │
│ (Dimension) │
└─────────────────┘

text

### Table Relationships
| From | To | Join Key |
|------|-----|----------|
| ad_events | ads | ad_id |
| ads | campaigns | campaign_id |
| ad_events | users | user_id |

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `Business_Requirements_Document.md` | Complete BRD with KPIs and visualizations |
| `Dashboard_Insights.md` | Detailed dashboard findings and metrics |
| `Domain_Knowledge_Document.md` | Data dictionary and table structures |
| `Project_Explanation_Interview.md` | Interview-ready project explanation |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard creation |
| Excel/CSV | Data processing |
| GitHub | Version control |

---

## 📖 How to Use This Repository

1. Read `Business_Requirements_Document.md` first
2. Review `Domain_Knowledge_Document.md` to understand data structure
3. Check `Dashboard_Insights.md` for key findings
4. Use `Project_Explanation_Interview.md` for presentations/interviews

---

---

## 📝 License

MIT

---

## 👨‍💻 Author

**Sachin Kumar**  
Data Scientist
📧 sachinkrtech05@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sachin-kumar-0a9185251/)  
🐙 [GitHub](https://github.com/sachinkr-05)

---

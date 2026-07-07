# Hi, I'm Neha 👋

**Supply Chain Program Manager & Data Engineer** | Apple · Dell · Adobe · HCL  
I build Python pipelines, analytics dashboards, and automated data systems at the intersection of supply chain and engineering.

---

## 🛠 What I Build

| Project | Stack | Live |
|---|---|---|
| [Vendor Intelligence Dashboard](https://github.com/nehamishra1212/vendor-dashboard) | React · Python · Git · GitHub Pages | [▶ Open App](https://nehamishra1212.github.io/vendor-dashboard) |
| [Reverse Auction Analytics Pipeline](https://github.com/nehamishra1212/reverse-auction-analysis) | Python · pandas · matplotlib · Jupyter | Notebook |
| [Supply Chain Data Validation Pipeline](https://github.com/nehamishra1212/data-validation-pipeline) | Python · pandas · Jupyter · IQR | Notebook |

---

## 🔬 Featured: Vendor Intelligence Dashboard

A live, interactive vendor scoring platform I built from scratch for Apple's supply chain ops:

- **50+ vendors** across 5 categories and 3 global regions
- **Sortable, filterable table** with per-column search
- **Analytics tab:** quality distribution, delivery performance, cost scoring, engagement breakdown
- Built with **React**, reads from **CSV data**, deployed via **GitHub Pages**

👉 **[Try it live →](https://nehamishra1212.github.io/vendor-dashboard)**

---

## 🐍 Featured: Reverse Auction Analytics Engine

Python pipeline analyzing 4,000+ vendor bids across 10 suppliers:

- Engineered **Consistency Score** (bid reliability) and **Competitiveness Score** (pricing aggressiveness)
- Classified vendors into **4 performance quadrants** via scatter plot analysis
- Built custom scoring algorithms in pandas — no ML library needed

---

## 📊 Featured: Data Validation Pipeline

Automated quality checks for supply chain vendor data (7 checks, 42 records, 20 intentional issues):

| Check | Method |
|---|---|
| Schema validation | Column presence + dtype check |
| Completeness | Null + empty string detection |
| Range validation | 0–100 score bounds, valid lead times |
| Duplicate detection | Exact row + name-level duplicates |
| Enum validation | Category, status, NPI/MP capable fields |
| Outlier detection | IQR × 1.5 fence method |
| Business logic | Weighted formula cross-check |

Auto-cleans and exports a validated CSV — designed to run on a schedule in a production pipeline.


```

---



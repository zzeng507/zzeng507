# Hi, I'm Ziqi Zeng 👋

**Financial/Data Analyst** focused on turning messy public filings into clear, defensible insights.  
I build small but reliable analysis pipelines (Python + Colab + GitHub) and explain results in plain English.

- 📌 Interests: peer benchmarking, revenue/margin trends, valuation sanity checks  
- 🧰 Tools: Python (pandas, numpy, matplotlib, requests), SQL, Jupyter/Colab, Git/GitHub  
- 🗂 Data: SEC EDGAR (companyfacts), Yahoo Finance  
- ✉️ Contact: **zzeng507@gmail.com**

---

## 🔥 Featured Project — SEC Financial Analysis
**Repo:** https://github.com/zzeng507/sec-financial-analysis

A 5-year peer comparison of **Tesla (TSLA)**, **Nvidia (NVDA)**, and **Ford (F)** using the SEC EDGAR API.

**What it does**
- Fetches company facts (annual) via EDGAR with a proper User-Agent (name + email)
- Cleans frames (10-K / 20-F), aligns fiscal years, and normalizes series
- Calculates **Revenue CAGR**, **EBITDA margin**, **PE**, and **PEG** with error-handling  
  (e.g., skip PEG if PE ≤ 0 or growth ≤ 0)
- Plots revenue trends and a lightweight 2-year **revenue forecast**
- Exports a recruiter-friendly CSV and charts

**Key visuals**
<p>
  <img src="imagesrevenue_by_year.png.png" width="420" />
  <img src="imagesebitda_margin.png.png" width="420" />
</p>
<p>
  <img src="imagesrevenue_forecast.png.png" width="560" />
</p>

**Why it’s useful**
- Shows how to handle real-world data issues (wrong revenue tags, missing CapEx, negative PE)
- Keeps the code readable so others can reuse the pipeline in minutes
- Comes with a short PDF/README summary for non-technical readers

---

## 🧪 Skills Snapshot
- **Data/Code:** Python (pandas, numpy, matplotlib, requests), SQL, Jupyter/Colab, Git/GitHub  
- **Analysis:** growth/retention, margin & unit economics, valuation sanity checks  
- **Delivery:** clean tables/charts + concise written takeaways for stakeholders

---

## 📌 What I’m working on next
- Adding CapEx/FCF fallbacks to complete cash-flow ratios  
- Expanding the peer set (e.g., GM, Toyota)  
- Automating quarterly refresh

---

## 📫 Find me
- Email: **zzeng507@gmail.com**
- LinkedIn: **https://www.linkedin.com/in/zengziqi/**

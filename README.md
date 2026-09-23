# 🤖 AI Job Market Analysis 2025–2026

**IBM Data Analytics and AI Internship — Final Project**

A complete Python data analytics project examining 1,500 AI job postings across 25 job roles, 14 countries, and 12 industries for the period 2025–2026.

---

## 📋 Project Description

This project performs an end-to-end data analytics workflow on the AI Jobs Market 2025–2026 dataset. It covers:

- Data loading, inspection, and quality assessment
- Data cleaning and feature engineering
- Exploratory data analysis (EDA) with 12+ professional visualizations
- KPI calculations: average salary, median salary, demand score, YoY growth, remote work %, AI salary premium, and more
- Salary analysis by job role, experience level, country, industry, company size, and education
- Skill frequency analysis (Python, SQL, Cloud, LLMs, and 25 more)
- Demand and growth trend analysis
- LLM vs non-LLM role comparison
- Interactive Streamlit dashboard with 8 analysis tabs and 10+ KPI cards
- Professional Word project report with embedded screenshots

---

## 📊 Dataset

| Property | Value |
|---|---|
| **Dataset Name** | AI Job Market Dataset 2025–2026 |
| **Source** | [Kaggle — AI Job Market Dataset 2025-2026](https://www.kaggle.com/) |
| **Total Records** | 1,500 job postings |
| **Columns** | 25 |
| **Job Roles** | 25 unique roles |
| **Countries** | 14 |
| **Industries** | 12 |
| **Posting Years** | 2025, 2026 |

> **Note:** This dataset is a curated/synthetic collection designed for educational and analytical purposes. It does not represent the complete global AI job market.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python 3.x | Core language |
| pandas | Data manipulation and analysis |
| numpy | Numerical computations |
| matplotlib | Static visualizations |
| seaborn | Statistical charts and heatmaps |
| plotly | Interactive charts in dashboard |
| streamlit | Interactive web dashboard |
| python-docx | Word report generation |
| Jupyter Notebook | Interactive analysis |

---

## 📁 Project Structure

```
AI-JOB-ANALYSIS-2025-26 Project/
│
├── ai_jobs_market_2025_2026.csv              # Source dataset
│
├── Vetsa Sri Pushpa_AI_Job_Market_Analysis_2025_2026.ipynb     # Main analysis notebook
├── app.py                                                          # Streamlit dashboard
├── requirements.txt                                                # Python dependencies
├── README.md                                                       # This file
│
├── Vetsa Sri Pushpa_AI_Job_Market_Analysis_2025_2026_ProjectReport.docx  # Word report
│
├── screenshots/                              # Generated charts and dashboard screenshots
│   ├── 01_salary_distribution.png
│   ├── 02_job_role_analysis.png
│   ├── 03_experience_salary.png
│   ├── 04_remote_work.png
│   ├── 05_country_analysis.png
│   ├── 06_industry_analysis.png
│   ├── 07_skill_analysis.png
│   ├── 08_company_size.png
│   ├── 09_demand_growth.png
│   ├── 10_salary_heatmap.png
│   ├── 11_llm_analysis.png
│   ├── 12_education_analysis.png
│   ├── dashboard_01_kpi_overview.png
│   ├── dashboard_02_job_salary.png
│   ├── dashboard_03_country_industry_skills.png
│   ├── dashboard_04_insights_actions.png
│   └── dashboard_05_heatmap_trends.png
│
├── generate_charts.py                        # Chart generation script
├── generate_dashboard_screenshots.py         # Dashboard screenshot script
└── generate_report.py                        # Word report generation script
```

---

## ⚙️ Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Step 1: Clone or download the project

```bash
# If using git
git clone <your-repo-url>
cd "AI-JOB-ANALYSIS-2025-26 Project"
```

### Step 2: Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Analysis

### Run the Jupyter Notebook

```bash
jupyter notebook "Vetsa Sri Pushpa_AI_Job_Market_Analysis_2025_2026.ipynb"
```

Or open with JupyterLab:

```bash
jupyter lab "Vetsa Sri Pushpa_AI_Job_Market_Analysis_2025_2026.ipynb"
```

Execute all cells from top to bottom (Cell → Run All). The notebook will:
1. Load and inspect the dataset
2. Perform data quality checks
3. Clean and preprocess data
4. Calculate all KPIs
5. Generate 12 professional visualizations (saved to `screenshots/`)
6. Display key findings, risks, opportunities, and recommendations

### Run the Streamlit Dashboard

```bash
streamlit run app.py
```

This will open the interactive dashboard in your default web browser at `http://localhost:8501`.

The dashboard provides:
- **10 KPI cards** (salary, demand, growth, remote work, LLM metrics)
- **8 analysis tabs**: Job Roles, Salary, Skills, Country & Industry, Experience, Work Model, Trends, Insights & Actions
- **Interactive sidebar filters**: year, country, work model, experience level, industry, company size, salary range
- **Real-time filter updates** on all charts and KPIs

---

## ✨ Key Features

- ✅ **Complete EDA**: 12 visualization types covering all major dataset dimensions
- ✅ **Real KPIs**: All numbers calculated directly from the CSV — no invented data
- ✅ **Interactive Dashboard**: 8-tab Streamlit app with sidebar filters
- ✅ **Skill Analysis**: Frequency analysis of 25+ unique AI skills
- ✅ **Salary Deep-Dive**: By role, experience, country, industry, company size, education, and LLM status
- ✅ **Demand Analysis**: YoY growth rates, demand scores, and monthly trends
- ✅ **Remote Work Analysis**: Distribution, salary comparison, by role and country
- ✅ **Professional Report**: Word document with embedded screenshots and full analytics documentation
- ✅ **Beginner-Friendly Notebook**: Well-commented, executable top-to-bottom without code changes

---

## 📈 Key Findings

| KPI | Value |
|---|---|
| Total Job Postings | 1,500 |
| Average Annual Salary | $194,892 |
| Median Annual Salary | $180,000 |
| Avg Demand Score | 87.5 / 100 |
| Avg YoY Demand Growth | 31.3% |
| Fully Remote Roles | 29.7% |
| Hybrid Roles | 45.7% |
| AI Salary Premium | 10.9% |
| LLM Role Share | 21.8% |
| LLM Salary Premium | ~$16,437 |
| Highest-Paying Role | AI Solutions Architect ($251,577) |
| Fastest-Growing Role | RAG Engineer (55.3% YoY) |
| Top-Paying Country | USA ($226,190 avg) |
| Top-Paying Industry | Automotive ($212,306 avg) |
| Most In-Demand Skill | Python (942 postings) |

---

## ⚠️ Dataset Limitations

- The dataset contains **1,500 curated/synthetic postings** — not a complete global market sample
- **Geographic skew**: USA represents 34.3% of postings — Western market bias
- **Salary figures in USD** — purchasing power parity (PPP) not adjusted for cross-country comparisons
- **Two-year snapshot** (2025–2026) — insufficient for long-term trend analysis
- **Skill tags only** — depth and proficiency of skill requirements not captured
- Findings should be treated as **indicative trends**, not definitive market statistics

---

## 📄 Project Report

The full project report is available as:
`Vetsa Sri Pushpa_AI_Job_Market_Analysis_2025_2026_ProjectReport.docx`

It includes:
- Introduction, Problem Statement, and Objectives
- Dataset description and source
- Technologies used
- Data cleaning methodology
- Complete EDA with all 12 embedded visualisations
- KPI analysis table
- Dashboard screenshots (5 full-page views)
- Key findings, risks, opportunities
- Recommended actions (for job seekers and employers)
- Conclusion and limitations

---

## 🏫 About this Project

This project was completed as part of the **IBM Data Analytics and AI Internship** programme.

- **Project Title:** AI Job Market Analysis 2025–2026
- **Dataset Source:** [Kaggle](https://www.kaggle.com/datasets/alitaqishah/ai-jobs-market-2025-2026-salaries)
- **Tools:** Python, pandas, matplotlib, seaborn, plotly, streamlit

---

*Made with IBM Bob — IBM Data Analytics & AI Internship Project*

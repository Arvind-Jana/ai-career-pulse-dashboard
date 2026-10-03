# 📊 AI Career Pulse: Interactive Tech Salary & Skill Premium Dashboard (2024–2026)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Handshake AI Skills Studio](https://img.shields.io/badge/Mission-Turn_Data_into_an_Interactive_Dashboard-purple.svg)](https://app.joinhandshake.com/)
[![Zero-Dependency](https://img.shields.io/badge/Setup-Zero_Dependencies-emerald.svg)](#)

> **Empirical labor market intelligence quantifying the salary premium, geographic purchasing power, and hiring velocity of AI/LLM skills for early-career tech professionals.**

Built for the **Handshake AI Skills Studio X OpenAI Challenge: "Turn Data into an Interactive Dashboard"**.

---

## ⚡ Quick Start (Instant 1-Click Launch)

This project is built as a **self-contained standalone web application** with zero build tools or package managers required.

### Option 1: Direct File Open (Instant)
Simply double-click:
- **`dashboard.html`** (in the root directory), or
- **`interactive-dashboard/index.html`**

It opens immediately in your default browser (Google Chrome, Microsoft Edge, Safari, Firefox).

### Option 2: Local HTTP Server (Optional)
If you prefer testing through a local server:
```bash
# Python
python -m http.server 8080

# Or Node.js / npx
npx serve .
```
Then visit: `http://localhost:8080/dashboard.html`

---

## 📁 Repository Structure

```
├── dashboard.html                  # Standalone interactive dashboard (double-click to open)
├── dashboard_cover.jpg             # High-res project cover image for Handshake submission
├── SUBMISSION_DASHBOARD.md         # Ready-to-copy submission answers for Handshake
└── interactive-dashboard/
    ├── index.html                  # Core application source
    ├── data.csv                    # Clean tabular benchmark dataset
    ├── data.json                   # Structured JSON dataset
    ├── dashboard_cover.jpg         # Cover image asset
    └── README.md                   # Project documentation
```

---

## 🚀 Key Features

1. **5 Interactive Visualizations (Chart.js 4.4)**:
   - **Base vs. AI Salary by Role**: Comparative salary analysis across 6 disciplines.
   - **Top AI Skill Multipliers**: Granular % salary lift for LLMOps, RAG, Vector DBs, PyTorch, etc.
   - **Work Modality Tradeoffs**: Radar chart analyzing Remote vs. Hybrid vs. In-Office.
   - **2024–2026 Hiring Trajectory**: Multi-year growth projections.
   - **Geographic Purchasing Power**: Nominal base pay vs. cost-of-living adjusted net savings.
2. **Interactive AI Career ROI & Salary Calculator**:
   - Customize target role, experience level, and check off AI proficiencies to calculate projected salary, comp percentile, and next skill recommendations.
3. **Multi-Parameter Dynamic Filtering**:
   - Filter all metrics and charts in real-time by Experience Level, Domain, Modality, and Location.
4. **Data Explorer Table with Live Search & CSV Export**:
   - Search by role, skills, location, or company type. Sort any column. Download the filtered data as CSV.

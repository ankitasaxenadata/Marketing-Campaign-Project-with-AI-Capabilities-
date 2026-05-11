# 📊 Marketing Campaign AI Agent System - Group 1

> An intelligent multi-agent system that transforms 200,000+ marketing campaign records into real-time, actionable recommendations — covering strategy, ROI prediction, performance analysis, and budget allocation.

---

## 🚀 Project Overview

This project is a multi-agent AI system built on a marketing campaign dataset of 200,000 rows and 16 features, including campaign type, channel, ROI, conversion rate, acquisition cost, engagement score, and more.

Rather than static dashboards or manual analysis, the system routes user queries through four specialised AI agents that collaborate to deliver intelligent campaign decisions in real time.

---

## 🤖 One System, Four Superpowers

| Agent | Description |
|---|---|
| **Campaign Strategy Recommender** | Analyzes historical ROI across campaign types, channels, locations, and audiences to recommend the best strategy |
| **ROI Predictor** | Predicts expected return on investment before campaign launch, based on historical performance records |
| **Campaign Performance Analyzer** | Deep dives into CTR, CPC, Engagement Score, and Success Rate across all dimensions |
| **Budget Allocator** | AI-recommended spend reallocation to maximise campaign ROI in real time |

---

## 📁 Project Deliverables

### 📑 Presentation
The full project presentation (slide deck) covering problem statement, system architecture, the four core agents, process flowchart, and live demo walkthrough.

📎 [View Presentation (Canva)](https://canva.link/nf577o3hz4kwuxj)

> To upload the PPT locally: place the exported `.pptx` file in the `/deliverables` folder of this repo.

---

### 📓 Project Notebook
The full EDA and agent pipeline built in Google Colab, including:
- Data loading and cleaning (incl. `Acquisition_Cost` formatting)
- Exploratory Data Analysis (distributions, correlations, segment breakdowns)
- Agent logic and recommendation outputs

📎 *(Add your Colab notebook link or `.ipynb` file here)*

---

### 📊 Dataset
- **File:** `marketing_campaign_dataset.csv`
- **Rows:** 200,000
- **Columns:** 16 — `Campaign_ID`, `Company`, `Campaign_Type`, `Target_Audience`, `Duration`, `Channel_Used`, `Conversion_Rate`, `Acquisition_Cost`, `ROI`, `Location`, `Language`, `Clicks`, `Impressions`, `Engagement_Score`, `Customer_Segment`, `Date`

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Environment:** Google Colab
- **Storage:** Google Drive
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 📂 Repository Structure

```
📦 marketing-campaign-ai-agents
├── 📁 deliverables
│   ├── marketing_campaign_presentation.pptx
│   └── project_report.pdf          # optional
├── 📁 notebooks
│   └── marketing_campaign_eda.ipynb
├── 📁 data
│   └── marketing_campaign_dataset.csv
├── README.md
```

---

## 📌 How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/marketing-campaign-ai-agents.git
   ```
2. Open the notebook in Google Colab or Jupyter
3. Mount your Google Drive if using Colab
4. Run cells sequentially — data cleaning through agent outputs

---

## 👩‍💻 Author

**Ankita**  
*Data Analytics Project — Marketing Campaign AI Agent System*

---

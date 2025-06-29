# High Pressure Conversion Rate (HPCR) - Football Analytics Project

🎓 This project was developed as part of a postgraduate assignment focused on event-level analysis using OPTA's F24 feeds. The objective was to define and implement a custom metric in Python based on real match data and evaluate it across a full football season.

---

## 📌 Task Description

> Based on the F24 feeds provided by OPTA, the goal was to **create a meaningful football metric** and calculate it for all teams or players in a league. The metric could be conditional (e.g., by position, pitch zone, match phase, or game state). The evaluation focused on:
>
> - Relevance and correctness of the metric
> - Metric complexity
> - Code quality (PEP8)
> - Result analysis and contextualization
> - Quality of presentation

---

## 📐 Metric Definition: High Pressure Conversion Rate (HPCR)

The **High Pressure Conversion Rate (HPCR)** measures the efficiency of a team’s high pressing actions. Specifically, it captures the percentage of defensive actions in the **final third (Zone 3)** that result in a **goal within 2 minutes**.

### 🔢 Formula

HPCR = (Goals scored within 2 minutes of a high-press defensive action in Zone 3) / (Total defensive actions in Zone 3)

This metric provides a high-level view of how effective teams are at converting defensive pressure into scoring opportunities.

---

## 🧰 Tools & Libraries

- Python
- pandas
- ElementTree (for XML parsing)
- tqdm
- Jupyter Notebook

---

## 📁 Data Source

- OPTA F24 XML feeds
- League analyzed: **La Liga 2023 Season**

---

## 🔎 Methodology

1. **Parsing XML data**: Custom parser to extract and structure OPTA event data.
2. **Filtering by zone**: Identified defensive events (tackles, interceptions, recoveries) in Zone 3.
3. **Temporal linking**: Tracked goals scored within a 2-minute window following those events.
4. **Metric calculation**: Computed HPCR for each team.
5. **Analysis**: Compared HPCR across teams and contextualized results.

---

## 📊 Sample Insights

- Teams with high HPCR demonstrate efficient transitions from pressing to scoring.
- Some teams had a high volume of pressure actions but low HPCR, indicating inefficiency in capitalizing on them.

---

## 🎯 Outcome

This project illustrates how custom metrics, tailored to tactical concepts, can reveal deeper insights in football analytics and performance scouting.

---

👤 **Author**: Nikolaos Georgiadis  
📅 **Date**: March 2025  
🔗 For feedback or collaboration, feel free to [connect on LinkedIn](https://www.linkedin.com/in/nikosgeorg/)

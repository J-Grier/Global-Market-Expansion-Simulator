# 🌍 Global Expansion Strategy Simulator – CAGE Framework Dashboard

An interactive, data-driven decision support tool that uses the **CAGE framework** (Cultural, Administrative, Geographic, Economic) to help companies evaluate international market expansion opportunities. Designed to simulate real-world strategy alignment, this dashboard allows users to prioritize countries based on business objectives and global constraints.

---

## 📌 Project Overview

This project models and visualizes international market prioritization using structured global data. It features:

- Custom distance metrics for Cultural, Administrative, Geographic, and Economic differences
- Interactive sliders to reweight strategic priorities
- 7 prebuilt strategic scenarios for simulation
- Dynamic bar charts and tabular rankings for decision-making

---

## 💡 Skills Demonstrated

| Category            | Description |
|---------------------|-------------|
| Data Engineering    | Extracted and cleaned data from World Bank, Hofstede, and geospatial sources |
| Feature Engineering | Built normalized distance metrics for 20+ countries across 4 dimensions |
| Strategic Modeling  | Encoded CAGE logic with adjustable inputs and scenario testing |
| Interactive Design  | Built a live dashboard using `ipywidgets` with real-time scoring and plotting |
| Visualization       | Used `matplotlib` for dynamic bar chart comparisons and ranking outputs |

---

## 📊 Sample Strategies Included

| Button | Description |
|--------|-------------|
| 🎯 Cultural Fit | Prioritize brand alignment with culturally similar countries |
| ⚖️ Regulation Focused | Emphasize legal/tariff accessibility |
| 🧭 Geographic Push | Enter closer markets to minimize logistical friction |
| 💸 Cost Sensitive | Minimize admin + economic distance for affordable entry |
| 🎨 Brand Focused | Emphasize long-term cultural and brand identity fit |
| 📈 Growth-at-All-Costs | Maximize economic opportunity, ignore friction |
| 🔄 Balanced | Treat all CAGE factors equally |

---

## 📁 Repository Structure

```bash
├── Notebooks/
│   ├── 01_process_distances.ipynb   # CAGE distance calculations
│   └── 02_interactive_dashboard.ipynb # Full dashboard logic
├── Data/                            # Cleaned CSV files (optional)
├── README.md
└── requirements.txt
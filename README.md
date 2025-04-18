# 🌍 Global Market Expansion Simulator: A Data-Driven CAGE Strategy Advisor

## 📈 Overview
This project is a data-driven decision support tool designed to simulate and prioritize international market expansion using the CAGE Framework (Cultural, Administrative, Geographic, Economic). By combining structured global datasets with an interactive dashboard, it allows businesses to explore how strategic priorities affect market rankings across countries.

The tool was originally developed in response to a global strategy case study focused on Diageo PLC, a UK-based leader in the beverage alcohol industry. Accordingly, the model defaults to the United Kingdom as the home country and compares it to a curated set of high-potential international markets.


---

## 🎯 Objectives
- **Primary Goal**: Assist companies in identifying optimal international expansion markets based on quantifiable CAGE distances.
- **Practical Insights**: Provide strategic, actionable recommendations through an interactive scenario-modeling dashboard.

---

## 📚 The CAGE Framework Explained
The CAGE framework evaluates market entry decisions based on four dimensions:
- **Cultural**: Differences in language, values, norms, and traditions.
- **Administrative**: Differences in governance, regulatory environment, legal frameworks.
- **Geographic**: Physical distance, transportation logistics, time zones.
- **Economic**: Differences in market size, income levels, economic stability.

This simulator quantifies these differences using comprehensive datasets, transforming qualitative considerations into actionable, numeric insights.

---

## 🛠️ Methodology & Data Sources

### 🗃️ Data Integration
- **Economic Data**: World Bank indicators (GDP, market size, economic stability).
- **Cultural Data**: Hofstede cultural dimensions (Power Distance, Individualism, Uncertainty Avoidance, etc.).
- **Geographic Data**: Geopy-calculated physical distances, logistics considerations.
- **Administrative Data**: World Bank governance indicators, Ease of Doing Business rankings.

### 📊 Analytical Pipeline
1. **Data Collection & Cleaning**
   - Fetched and merged global datasets from multiple structured sources.
   - Normalized and standardized for fair comparisons across countries.

2. **CAGE Distance Calculation**
   - Computed cultural, administrative, geographic, and economic distances.
   - Normalized distances to create composite expansion suitability scores.

3. **Interactive Dashboard Development**
   - Built using Streamlit to allow dynamic scenario modeling and visual analytics.

---

## 💡 Key Features of the Simulator
- **Customizable Weighting**: Adjust importance of each CAGE factor (Cultural, Administrative, Geographic, Economic).
- **Interactive Exploration**: Instantly visualize market entry impacts with dynamic sliders and dropdowns.
- **Strategic Recommendations**: Offers clear, numeric insights to guide international expansion decisions.

---

## 🚀 Practical Impacts
- Enables businesses to quickly assess and prioritize global market opportunities.
- Reduces uncertainty by providing quantifiable insights on market suitability.
- Enhances strategic decision-making with clear, actionable visualizations.

---
## 🚧 Limitations & Future Work

### Limitations
- Current model assumes linear relationships within the CAGE framework.
- Some qualitative administrative and cultural nuances may not be fully captured numerically.

### Future Directions
| Idea                        | Goal                                           |
|-----------------------------|------------------------------------------------|
| Add real-time economic data | Improve responsiveness to economic changes     |
| Integrate sentiment analysis| Capture nuanced public and business perceptions|
| Enhance scenario simulations| Provide deeper forecasting capabilities        |

---

## 🔖 References
- Ghemawat, Pankaj. "Distance Still Matters: The Hard Reality of Global Expansion." *Harvard Business Review*, 2001.  
  [Harvard Business School Link](https://www.hbs.edu/faculty/Pages/item.aspx?num=27817)
- [CAGE Framework (Harvard Business Review)](https://hbr.org/2001/09/distance-still-matters-the-hard-reality-of-global-expansion)
- [World Bank Open Data](https://data.worldbank.org/)
- [Hofstede Insights](https://www.hofstede-insights.com/)
- [Streamlit](https://streamlit.io/)

---

## Author
**John Grier**  
MS Data Science Candidate, Illinois Tech  
[GitHub: J-Grier](https://github.com/J-Grier)

---

## 💬 Connect With Me
- [LinkedIn](https://linkedin.com/in/johngrier)
- Email: jgrier@hawk.iit.edu


## 📁 Repository Structure

```bash
├── Notebooks/
│   ├── 01_process_distances.ipynb   # CAGE distance calculations
│   └── 02_interactive_dashboard.ipynb # Full dashboard logic
├── Data/                            # Cleaned CSV files (optional)
├── README.md
└── requirements.txt

# 🚦 Calgary Traffic Safety & Collision EDA

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=flat&logo=pandas)
![Folium](https://img.shields.io/badge/Folium-Geospatial%20Vis-77B829?style=flat&logo=leaflet)

An exploratory data analysis (EDA) of over 55,000 historical traffic incidents across Calgary, Alberta. This project investigates temporal risk factors, seasonal fluctuations, and high-density collision corridors to derive actionable safety insights.

---

## 💡 Key Business & Public Safety Insights

1. **Dual Peak Commute Phenomenon**: Weekday collisions exhibit sharp dual-peak volume matching commute patterns (8:00 AM and 5:00 PM). Weekend incidents peak smoothly between 1:00 PM and 4:00 PM.
2. **Quadrant Disparities**: NE and NW quadrants consistently log higher collision volumes relative to South quadrants, driven by high-capacity transit corridors (e.g., Deerfoot Trail intersections).
3. **Seasonal Risk Factors**: Winter months show elevated minor incident rates corresponding with freezing rain and snowfall events, whereas high-severity off-peak crashes spike during summer weekends.

---

## 📊 Sample Visualizations

| Weekday vs. Weekend Density Pattern | Spatial Collision Heatmap |
| :---: | :---: |
| *Plots hourly commute risk profile* | *Interactive Folium HeatMap of density* |

*(Include exported PNG charts here)*

---

## 🛠️ Tech Stack & Methods

- **Language**: Python 3.10+
- **Data Wrangling**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Geospatial Intelligence**: `folium` (HeatMap & MarkerClusters)

---

## ⚙️ How to Run

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/Calgary-Traffic-EDA.git](https://github.com/your-username/Calgary-Traffic-EDA.git)
   cd Calgary-Traffic-EDA
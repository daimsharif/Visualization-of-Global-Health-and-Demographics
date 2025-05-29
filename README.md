# Global Health & Historical Visualizations

This project showcases a series of visualizations built for the Data Visualization MSc module (CS7DS4) at Trinity College Dublin. The work includes reproductions of iconic historical graphics and explorations of life expectancy trends across nations using GDP, population, and time as core variables.

---
## 📄 Full Report

View the full report with all the visualizations:

👉 [A1_SharifDaim.pdf](./A1_SharifDaim.pdf)

## 📊 Part A: Minard’s Napoleon Visualization (Python)

- Reproduced Charles Minard’s “Napoleon’s March to Moscow” using Python and GeoPandas
- Integrated historical latitude/longitude coordinates with geopolitically accurate country and river layers
- Applied `LineCollection` and `PathPatch` to draw troop paths and annotations
- Merged temperature data into a secondary subplot to reflect weather impact on troop loss
- Tuned font, color, and legend design for clean, period-consistent aesthetic

👉 [minard_code.ipynb](./minard_code.ipynb)


---

## 🌍 Part B: Life Expectancy vs GDP Analysis (Python)

- Used seaborn and matplotlib to build six exploratory visualizations:
  - GDP vs Life Expectancy with population encoded via size and brightness
  - Continent-wise comparisons using color, shape, and jittered plots
  - Time-series charts for continental life expectancy trends with dynamic encodings
- Highlighted Ireland across all graphs for consistent comparison
- Implemented transformations (log, quartile bins) to handle skewed data

👉 [global_health_viz.ipynb](./global_health_viz.ipynb)


---

## 📈 Part C: Tableau Dashboard

- Built an animated multi-axes scatter plot using Tableau
- Visualized year-wise life expectancy vs GDP with continent (hue) and population (size) encoding
- Tracked progression of Asian countries from 1952 to 2007 using color-coded growth trajectories

---

## 🛠️ Tools & Libraries

- `matplotlib`, `seaborn`, `geopandas`, `shapely`, `pandas`
- Tableau (for multi-dimensional dashboard)
- `PathPatch`, `LineCollection`, and custom legends

---

## 🧑‍💻 Author

- **Daim Sharif**, MSc in Computer Science (Data Science Strand), Trinity College Dublin


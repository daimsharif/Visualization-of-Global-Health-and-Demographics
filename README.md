# Global Health & Historical Visualizations

This project showcases a series of visualizations built for the Data Visualization module (CS7DS4) at Trinity College Dublin. The work includes reproductions of iconic historical graphics and explorations of life expectancy trends across nations using GDP, population, and time as core variables.

---

## 📊 Part A: Minard’s Napoleon Visualization (Python)

- Reproduced Charles Minard’s “Napoleon’s March to Moscow” using Python and GeoPandas
- Integrated historical latitude/longitude coordinates with geopolitically accurate country and river layers
- Applied `LineCollection` and `PathPatch` to draw troop paths and annotations
- Merged temperature data into a secondary subplot to reflect weather impact on troop loss
- Tuned font, color, and legend design for clean, period-consistent aesthetic

---

## 🌍 Part B: Life Expectancy vs GDP Analysis (Python)

- Used seaborn and matplotlib to build six exploratory visualizations:
  - GDP vs Life Expectancy with population encoded via size and brightness
  - Continent-wise comparisons using color, shape, and jittered plots
  - Time-series charts for continental life expectancy trends with dynamic encodings
- Highlighted Ireland across all graphs for consistent comparison
- Implemented transformations (log, quartile bins) to handle skewed data

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


# 🌍 O3Scope | Ozone Analysis and Prediction Using NASA Dataset

> Turning NASA satellite data into interactive ozone insights | from global trends to city-level risk classification.

**[▶ Live Demo](https://app.hex.tech/019bc84d-6d99-7005-ad5d-c5d4b1514cf3/app/O3Scope-Ozone-Analysis-and-Prediction-Using-Nasa-DataSet-032DBlWgYk46bGQvfCRhkz/latest)**
---

## 🧠 Motivation

The depletion of the ozone layer is one of the most pressing environmental challenges of our time, directly affecting UV exposure, human health, and global ecosystems. O3Scope was built to make this invisible crisis visible: transforming raw NASA satellite data into interactive maps, city-level risk classifications, and predictive forecasts that anyone can explore.

---

## ✨ Features

### 🗺️ Interactive World Map
- Visualizes global ozone distribution across **2012–2026**
- Color-coded ozone concentration levels using Matplotlib + Cartopy
- City-level drill-down for localized insights

### 🏙️ City Risk Classification
Cities are classified into three risk zones based on ozone column values:

| Zone | Description |
|------|-------------|
| 🟢 Normal | Ozone levels within healthy range |
| 🟡 Warning | Moderate depletion detected |
| 🔴 Severe | Significant ozone depletion: high UV risk |

### 📈 2027 Ozone Prediction
- Linear regression model trained on yearly global/city averages
- Forecast visualized with trend lines and uncertainty bands
- Communicates prediction confidence transparently

### ⚡ Interactive Hex App
- Dropdown selectors for city and year exploration
- Dynamic chart and map outputs
- AI-assisted analysis powered by Hex AI tools

---

## 🔧 Tech Stack

| Layer | Tools |
|-------|-------|
| Data Source | NASA OMPS HDF5 Satellite Datasets |
| Data Processing | Python, h5py, NumPy, Pandas |
| Visualization | Matplotlib, Cartopy |
| Prediction | Scikit-learn (Linear Regression) |
| App Platform | Hex (interactive notebooks) |
| AI Assistance | Hex AI Tools |

---

## ⚡ Challenges & Learnings

- **Large HDF5 files**: Efficiently parsing multi-dimensional satellite arrays required careful memory management
- **City mapping**: Projecting global grid data onto city coordinates for meaningful localization
- **Uncertainty communication**: Visualizing prediction confidence intervals in an accessible way
- **Scientific storytelling**: Making complex ozone data understandable to non-technical audiences through interactivity

---

## 🏆 Built At

**Hex-a-thon Hackathon** | a Hex-platform hackathon focused on data science and interactive notebook applications.

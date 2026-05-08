# 🚦 F1 Analytics Dashboard

An interactive Formula 1 analytics project built using **Python, Pandas, and Tableau** to explore driver performance, race strategies, constructor trends, and pit stop efficiency across multiple F1 seasons.

This project combines **data cleaning, feature engineering, exploratory analysis, and dashboard storytelling** to generate meaningful insights from historical Formula 1 race data.

---

# 📌 Project Overview

The goal of this project was to analyze Formula 1 race performance data and transform raw datasets into interactive analytical dashboards that help answer questions such as:

- Which drivers dominated across different eras?
- How strongly does qualifying position affect race results?
- Which constructors consistently performed well?
- How have pit stop strategies evolved over time?
- Which drivers demonstrated the most consistency?

The project includes:
- Data preprocessing using Python
- Feature engineering and dataset merging
- Interactive Tableau dashboards
- Strategy and performance analysis

---

# 🛠️ Tech Stack

### Programming & Data Processing
- Python
- Pandas
- NumPy

### Visualization & BI
- Tableau Desktop / Tableau Public

### Version Control
- Git
- GitHub

---

# 📂 Project Structure

```bash
F1-Analytics-Dashboard/
│
├── Dashboards screenshots/
│   ├── F1 Analytics Dshboard.png
│   └── F1 Strategy and Performance Analytics.png
│
├── data/
│   ├── circuits.csv
│   ├── constructors.csv
│   ├── drivers.csv
│   ├── races.csv
│   ├── results.csv
│   ├── pit_stops.csv
│   ├── qualifying.csv
│   ├── f1_final.csv
│   └── f1_strategy_final.csv
│
├── notebook/
│   ├── data_cleaning.ipynb
│   └── strategy_data_cleaning.ipynb
│
├── tableau/
│   ├── F1 Analytics Dashboard.twb
│   └── F1 Strategy and Performance Analytics.twb
│
└── README.md
```

---

# 🧹 Data Preparation

The raw Formula 1 datasets were cleaned and transformed using Python.

### Key preprocessing steps:
- Handling missing/null values
- Merging multiple datasets
- Standardizing driver and constructor names
- Creating derived metrics
- Filtering inconsistent records
- Preparing dashboard-ready datasets

### Final Processed Datasets
- `f1_final.csv`
- `f1_strategy_final.csv`

---

# 📊 Dashboards Included

---

# 1️⃣ F1 Analytics Dashboard

This dashboard focuses on historical driver and race performance analysis.

## Dashboard Components

### 📈 Driver Performance Over Time
Tracks seasonal driver points to analyze consistency and peak performance periods.

### 🏆 Total Wins Comparison
Compares all-time race wins among top Formula 1 drivers.

### 🎯 Strategy Scatter Plot
Analyzes the relationship between:
- Grid Position
- Final Race Position

Used to identify overtakes, race strategy effectiveness, and qualifying impact.

## Key Insights
- Top drivers maintain long-term scoring consistency
- Strong qualifying positions often correlate with better finishes
- Some drivers consistently outperform starting grid expectations

---

# 2️⃣ F1 Strategy & Performance Analytics Dashboard

This dashboard focuses on strategic race analysis and constructor performance.

## Dashboard Components

### 🔥 Qualifying vs Finish Analysis
Visualizes:
- Positions gained
- Positions lost

Green indicates strong race recovery/performance.  
Red indicates position losses.

### 🟩 Driver Consistency Heatmap
Analyzes finishing consistency across seasons using color intensity.

### 🏭 Constructor Trends
Tracks constructor points evolution across multiple seasons.

### ⏱️ Pit Stop Performance Over Time
Examines average pit stop durations and strategic evolution over the years.

## Key Insights
- Faster pit stop eras align with modern strategic racing
- Certain constructors maintained dominance across long periods
- Driver consistency varies significantly by era and team stability

---

# ✨ Features

- Interactive Tableau dashboards
- Common filters across multiple charts
- Hover tooltips and highlight actions
- Dynamic visual storytelling
- Multi-dashboard analytical workflow
- Responsive dashboard layouts

---

# 🚀 Future Improvements

Potential enhancements for future versions:
- Add lap-by-lap telemetry analysis
- Include weather and tire strategy datasets
- Deploy dashboards publicly on Tableau Public
- Build web-based dashboard embedding
- Add predictive analytics using machine learning

---

# 📥 How to Run

## Python Setup

```bash
pip install pandas numpy
```

Run notebooks:
```bash
jupyter notebook
```

---

# 📊 Tableau Usage

1. Open Tableau Desktop/Public
2. Open `.twb` dashboard files
3. Connect datasets if prompted
4. Explore interactive dashboards

---

# 📌 Repository Purpose

This project demonstrates:
- Data analytics skills
- Dashboard design
- Data storytelling
- Python-based preprocessing
- Tableau visualization expertise
- End-to-end analytics workflow

---

# 👨‍💻 Author

**Mrunal Kiran**

Master’s Student — Information Technology & Management  
Focused on:
- Data Analytics
- Business Intelligence
- Visualization
- Data Engineering
- Software & Strategy Analytics

---

# ⭐ If You Like This Project

Feel free to:
- Star the repository
- Fork the project
- Share feedback
- Connect on LinkedIn
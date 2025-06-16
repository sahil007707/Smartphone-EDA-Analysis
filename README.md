# Smartphone Dataset Exploratory Data Analysis 📱📊

This project performs an in-depth **Exploratory Data Analysis (EDA)** on a cleaned dataset of smartphones, covering key hardware and software features, brand trends, and visual breakdowns across several device specifications. It aims to reveal patterns across brands, highlight consumer-facing features like 5G, NFC, and refresh rates, and prepare the data for further machine learning tasks.

---

## 📁 Project Contents

- **Smartphone EDA Analysis.ipynb** – Main notebook containing:
  - Data cleaning and imputation
  - Feature-wise univariate & bivariate visualizations
  - Brand-wise aggregation
  - Frequency analysis of hardware specs
  - Visual comparison of features like refresh rate, 5G, and processor brands

---

## 📌 Key Features Analyzed

- `has_5g`, `has_nfc`, `has_ir_blaster`, `fast_charging`, `refresh_rate`
- Camera configurations (e.g., `num_front_cameras`, `primary_camera_front`)
- Hardware specs like `processor_brand`, `num_cores`, `battery_capacity`
- OS type, brand name, pricing distribution

---

## 🔍 Notable Insights

- **Top 100 smartphones** by price across all brands visualized in a bar chart
- **Pie chart** of most popular processor brands
- **Line plot** comparison of models with/without 5G
- **Histograms** of categorical variables (e.g., OS, processor brand)
- **Refresh rate breakdown** at key levels: 120Hz, 144Hz, 165Hz, and 240Hz

---

## 📊 Visualizations Used

- `seaborn`: histograms, bar plots, line plots
- `matplotlib`: pie charts, grid layouts
- `plotly`: available but not fully leveraged (placeholder)
- Visual groupings by brand, model, and feature category

---

## 🧹 Data Preprocessing

- Missing value handling using:
  - Median for numeric features
  - Mode or “Unknown” for categorical ones
- Dropped redundant columns like screen resolution width/height
- Converted certain columns to appropriate datatypes (e.g., `extended_upto` → int)
- Removed duplicates and verified shape/consistency

---

## 🛠️ Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `plotly` (imported but limited use)
- `warnings` for cleaner output

---

## 📈 Future Scope

- Extend EDA into machine learning (e.g., classification or clustering of phones by specs)
- Interactive dashboards with `plotly` or `streamlit`
- Feature engineering to score phones by price-to-spec ratio

---

## ▶️ Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/sahil007707/smartphone-eda.git
   cd smartphone-eda

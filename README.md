# 🍷 Wine Quality Analysis Dashboard (Power BI)

This project presents an interactive dashboard built in **Power BI** for analyzing red and white **Vinho Verde wine** data. It combines key metrics and visual insights to explore relationships between wine attributes and quality.

![Dashboard Snapshot](./Snapshot%20of%20the%20dashboard.png)

---

## 📊 Overview

The dashboard consolidates data from red and white wine datasets (UCI Wine Quality) into a single unified dataset, enabling cross-comparison of attributes and trends affecting wine quality.

**Key Features:**

- Combined red and white wine data using **Power Query Transform** into a single table: `Winedata`
- Clean, elegant layout with wine-themed color palette (deep red & white gold)
- Visual insights for physicochemical attributes and their correlation with quality

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository – Wine Quality Dataset](https://archive.ics.uci.edu/dataset/186/wine+quality)
- **Files Used**:
  - `winequality-red.csv`
  - `winequality-white.csv`
- **Target Variable**: `quality` (score between 0–10)
- **Features**: 11 physicochemical variables (e.g., alcohol, pH, sulphates, density, etc.)
- **Added Column**: `type` (Red or White)

---

## 📌 KPI Summary

The dashboard includes key performance indicators (KPI cards):

- 🧾 **Total Wines**: `6497`
- ⭐ **Average Quality**: `5.82`
- 🏅 **High Quality Wines** (quality ≥ 7): `1277`
- 📈 **High Quality Percent**: `19.7%`
- 🍷 **Average Alcohol**: `10.49`

---

## 📊 Visual Insights

### 📌 Visuals Included

| Visual | Description |
|--------|-------------|
| **Donut Chart** | Total Wines by Type (Red vs White) |
| **Scatter Plot** | Sulphates vs Residual Sugar with Quality color-coded |
| **Bar Charts** | Avg Quality by Chloride, Alcohol, pH, Density, Citric Acid, and Fixed Acidity |
| **Dot Plots** | Distribution of Quality vs Density and Citric Acid |
| **Slicer** | Wine Type selector (Image-based: red or white wine glass) |

---

## 🛠️ Data Transformations

Performed in **Power Query**:
- Merged `winequality-red.csv` and `winequality-white.csv` into `Winedata`
- Added a `type` column to distinguish red and white wines
- Converted data types appropriately for modeling and visual analysis

---

## 🧠 Key Insights

- **White wines dominate** the dataset (~75%)
- **Higher alcohol** tends to correlate with **higher quality**
- **Chloride, density**, and **pH** show subtle patterns across wine types
- Red and white wines exhibit different **residual sugar and sulphate** distributions
- Distribution of **citric acid** and **fixed acidity** differs by type and quality

---

## 🖥️ Getting Started

To run this dashboard:

1. Download the Power BI Template file:  
   [`Wine Quality Analysis Dashboard.pbit`](https://github.com/Ishatryingtocode/Wine_Quality_Analysis_Dashboard_PowerBI/raw/refs/heads/main/Wine%20Quality%20Analysis%20Dashboard.pbit)

2. Download the datasets:
   - [winequality-red.csv](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv)
   - [winequality-white.csv](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv)

3. Open the `.pbit` file in **Power BI Desktop**
4. When prompted, connect the CSV files to populate the data model

---

## 📌 Notes

- "High Quality Wines" are defined as wines with a **quality score ≥ 7**
- All visuals are dynamic and respond to slicer selections (wine type)
- Designed with clarity and storytelling in mind, using wine-themed visuals and colors

---

## 📚 Acknowledgements

- Dataset by:  
  P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis (2009)  
  *Modeling wine preferences by data mining from physicochemical properties*, Decision Support Systems, Elsevier.

- Data Source: [UCI ML Repository – Wine Quality Dataset](https://archive.ics.uci.edu/dataset/186/wine+quality)

---

## 📎 License

This project is for educational and analytical purposes. Dataset is publicly available.

---

## 🙌 Connect

Project by [Ishatryingtocode](https://github.com/Ishatryingtocode)  
Feel free to fork, contribute, or reach out for feedback or collaboration!

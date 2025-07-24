# 💧 EU Pollutant Releases to Water (2010–2023)

This project explores industrial **pollutant releases to water** across EU27 countries over a 13-year span using data from the **European Environment Agency (EEA)**. The visualizations track how pollutant types like heavy metals, nitrogen, and phosphorus have changed over time, helping reveal trends in water pollution regulation.

---

## 📊 Key Visualizations

| Chart Type     | Description |
|----------------|-------------|
| 📈 **Line Chart**     | Trends in pollutant release index values (2010–2023) |
| 📊 **Bar Chart**      | Indexed pollutant values in 2023 |
| 🔥 **Heatmap**        | Index values by pollutant vs. year |
| 🌊 **Area Chart**     | Cumulative pollutant release trends |
| 📉 **Slope Chart**    | Change comparison between 2010 and 2023 |

---

## 🧠 Insights by Chart

### 1. **Line Chart**
- Significant decline in heavy metals (e.g., mercury, lead)
- Stable levels in nitrogen, phosphorus, and organic carbon

### 2. **Bar Chart (2023)**
- **Zinc** and **nitrogen** dominate in recent discharges
- Low index values for regulated metals (cadmium, mercury)

### 3. **Heatmap**
- Reductions seen in metal pollutants over time
- Warm colors (high release) remain for phosphorus and nitrogen

### 4. **Area Chart**
- Stacked pollutant volumes show declining heavy metal layers
- Nutrients remain dominant in total pollution load

### 5. **Slope Chart (2010 vs 2023)**
- Visualizes which pollutants have improved or worsened
- Most heavy metals improved, nutrients remained stable

---

## 🗂️ Dataset Summary

- **Source**: European Environment Agency ([EEA IND_P05](https://www.eea.europa.eu/en))
- **Years**: 2010 to 2023
- **Format**: Indexed pollutant release values (2010 baseline = 100)
- **Pollutants**: Metals, nitrogen, phosphorus, organic pollutants, and others

---

## 🧹 Data Cleaning

- Removed prefixes in pollutant names
- Converted time values to integers
- Filtered for years 2010–2023
- Exported cleaned subsets

---

## 🛠️ Tools Used

- **Python** – `pandas`, `matplotlib`, `seaborn`
- **Jupyter Notebook** – Data exploration and visualization
- **Tableau** (optional) – Enhanced visual exploration

---

## 📁 Files in This Repository

| File Name                                                             | Description                                |
|-----------------------------------------------------------------------|--------------------------------------------|
| `EU Pollutant Releases to Water.ipynb`                                | Full notebook with code + visuals          |
| `pollution_data_cleaned.csv`                                          | Cleaned full dataset                       |
| `pollution_data_2023.csv`                                             | 2023-only data for bar chart               |
| `pollution_data_2010_vs_2023.csv`                                     | Data subset for slope chart                |
| `Line Chart – Pollutant Trends Over Time.png`                         | Line chart export                          |
| `Bar Chart – Compare Pollutants in 2023.png`                          | Bar chart export                           |
| `Heatmap – Year vs Pollutant.png`                                     | Heatmap export                             |
| `Area Chart – Stacked Area.png`                                       | Area chart export                          |
| `Slope Chart – First vs Last Year.png`                                | Slope chart export                         |

---

## 📌 How to Use

1. Open the `.ipynb` notebook in Jupyter or VS Code
2. Run all cells to generate visualizations
3. Use `.csv` files to build dashboards in Tableau or Excel

---

## 📎 License

This project is open for educational and non-commercial use. Please credit the original dataset source when referencing.

---

## 🔗 Source

Data retrieved from:  
[European Environment Agency (EEA)](https://www.eea.europa.eu/en)  
Indicator: [IND_P05 – Industrial pollution releases to water](https://www.eea.europa.eu/en/datahub/datahubitem-view/67b842c1-b87e-45ad-8428-80bfa4d489b2)



# 🌊 EU Pollutant Releases to Water (2010–2023)

This project analyzes pollutant discharges into European surface and groundwater from 2010 to 2023, using publicly available data from the **European Pollutant Release and Transfer Register (E-PRTR)**. The analysis focuses on trends in pollutant quantities, identifying which substances dominate water pollution, how those trends have evolved over time, and which pollutants remain most persistent.

---

## 📁 Dataset Summary

- **Source:** [European Environment Agency - E-PRTR](https://www.eea.europa.eu/en/datahub/datahubitem-view/57606b9d-73c5-4dd6-b2f1-68fd85eebf5c)
- **Years Covered:** 2010 to 2023
- **Geography:** European countries reporting to E-PRTR
- **Focus:** Releases to water only (excluding air or land)
- **Key Fields Used:**
  - Year
  - Pollutant name
  - Quantity released (kg/year)
  - Receiving area (freshwater, transitional, coastal)

---

## 🔧 Tools Used

- **Tableau Public:** For all data visualizations  
- **Microsoft Excel:** For minor data cleaning  
- **GitHub:** For publishing the project and sharing findings

---

## 📊 Key Visualizations & Insights

### 1. 📈 Total Water Pollutant Releases (Stacked Area Chart)
![Stacked Area](visualizations/Area Chart – Stacked Area.png)
- **Insight:** Overall pollutant releases to water show a fluctuating trend.  
- **Nitrogen** dominates by a large margin throughout the years.
- Despite variability, the total discharge decreased noticeably after 2020.

---

### 2. 🧪 Most Released Pollutants in 2023 (Bar Chart)
![Bar Chart](visualizations/Bar Chart – Compare Pollutants in 2023.png)
- In 2023, the **top 3 pollutants** released were:
  1. **Nitrogen**
  2. **Total Organic Carbon (TOC)**
  3. **Phosphorus**
- **Heavy metals** such as Zinc, Lead, and Copper were present in smaller yet significant quantities.

---

### 3. 📉 Pollutant Trends Over Time (Line Chart)
![Line Chart](visualizations/Line Chart – Pollutant Trends Over Time.png)
- **Nutrient pollutants** (Nitrogen and Phosphorus) remain consistently high.
- **Cadmium** and **Mercury** show steady decreases, suggesting effective regulation.

---

### 4. 🔥 Heatmap of Pollutants by Year
![Heatmap](visualizations/Heatmap – Year vs Pollutant.png)
- **Color intensity** reflects pollutant quantity (log scale).
- Highlights drastic drop-offs in several hazardous pollutants post-2015.
- Reveals reappearance of certain pollutants in later years (e.g. Zinc, Nickel).

---

### 5. ⛰️ Slope Chart – First vs Last Year
![Slope Chart](visualizations/Slope Chart – First vs Last Year.png)
- Displays change in total pollutant release from **2010 to 2023**.
- **Nitrogen** remained the highest despite some decrease.
- **TOC**, **Zinc**, and **Nickel** show increases, while **Cadmium**, **Lead**, and **Mercury** declined.

---

## 🧠 Summary of Findings

- **Nutrients (N and P)** are the most significant pollutants in European water bodies.
- **Heavy metal pollution** shows a declining trend, indicating effective environmental regulation.
- Some pollutants that previously declined (e.g., TOC, Zinc) show resurgence in later years.
- Data gaps or inconsistencies might exist for some years or countries, especially during 2020–2021.

---

## 🚀 Reflections & Next Steps

This project demonstrates how public environmental datasets can reveal trends in pollution that support both awareness and policy. Future directions could include:
- Mapping pollutant releases **by country or region**
- Comparing **pollutant loads with population or industrial activity**
- Including **toxicological scores** to assess environmental risk, not just quantity

---

## 👤 Author

**Amalina N. Hapsari**   
🌐 [GitHub Portfolio](https://github.com/amalinahapsari-12)

---

## 🗂️ Repository Structure

```
EU-Pollutant-Releases-to-Water-2010-2023/
│
├── data/
│   └── [Optional raw or cleaned dataset]
│
├── visualizations/
│   ├── Area Chart – Stacked Area.png
│   ├── Bar Chart – Compare Pollutants in 2023.png
│   ├── Heatmap – Year vs Pollutant.png
│   ├── Line Chart – Pollutant Trends Over Time.png
│   └── Slope Chart – First vs Last Year.png
│
├── README.md
└── .gitignore
```

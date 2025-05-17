# 🌍 Tuberculosis Global Dashboard (Tableau)

This project explores global Tuberculosis (TB) trends using visual analytics in Tableau. It uses publicly available data to answer key epidemiological questions through descriptive analysis, time-series, geographic visualization, and calculated insights.

📊 **Dataset Source**:  
[TB_Burden_Country.csv - Tableau Sample Data](https://public.tableau.com/app/sample-data/TB_Burden_Country.csv?_gl=1*1ar0bos*_ga*ODg5MTAwODE5LjE3NDcyMjU1MTk.*_ga_8YLN0SNXVS*czE3NDc0NTYxNzQkbzUkZzAkdDE3NDc0NTYxNzQkajAkbDAkaDA)

---

## 🔍 1. Basic Descriptive Analysis

- **a)** Which countries had the highest estimated TB prevalence in the latest available year?

  ![image](https://github.com/user-attachments/assets/ac584ddf-0216-4994-ae9f-1b694e9ac857)

- **b)** Which region has the highest average TB mortality (excluding HIV) per 100,000?

  ![image](https://github.com/user-attachments/assets/6383ae52-32be-4b57-a40f-2876e69f2463)

- **c)** What is the total estimated number of TB deaths (excluding HIV) globally every year?

  ![image](https://github.com/user-attachments/assets/7ea7365e-1468-4922-acc9-71d6250e9e35)

---

## 📈 2. Time-Series & Trends

- **a)** How has TB incidence (excluding HIV per 100,000) changed over time in a specific country or region?

  ![image](https://github.com/user-attachments/assets/5ef86a5e-ad3c-49fe-a530-a75fd9c65564)

- **b)** Which countries showed the largest decrease in TB mortality between two years?

  ![image](https://github.com/user-attachments/assets/fecdcf08-411e-4dc8-967e-aea861474e54)

- **c)** How has the case detection rate changed over time regionally?

  ![image](https://github.com/user-attachments/assets/ee1312a2-373b-49fe-8760-e902f513fb3d)

---

## 🗺️ 3. Geographic Visualization

- **a)** Map of TB prevalence per 100,000 for all countries in the most recent year

  ![image](https://github.com/user-attachments/assets/71a33947-07d1-4ac5-b59d-f8967deab576)

- **b)** TB-related deaths by country in regions like Africa, South-East Asia, etc.

  ![image](https://github.com/user-attachments/assets/cacde466-f22c-4c3d-add3-fe8a85b3dc2d)

---

## ⚖️ 4. Comparative Analysis

- **a)** Comparison of TB mortality rates (with and without HIV) across countries/regions

  ![image](https://github.com/user-attachments/assets/b7e59a74-dbc3-4d59-990c-0ca659b1a840)

- **b)** Difference between high and low bound estimates of TB prevalence for the top 10 affected countries

  ![image](https://github.com/user-attachments/assets/a4bcb2f0-5fcf-49df-a9dd-3683ee9e943b)

- **c)** Countries with the largest gap between estimated incidence and case detection rate

  ![image](https://github.com/user-attachments/assets/0de5f8d4-2e56-4635-aa72-5d7a0ad63f3a)

---

## 🧮 5. Advanced Calculated Fields

- **a)** Uncertainty margin for TB deaths (excluding HIV): `High Bound - Low Bound`

  ![image](https://github.com/user-attachments/assets/67c52b06-9244-47ee-9a01-12d06d10a0a1)

- **b)** Mortality-to-Incidence Ratio: `Mortality / Incidence`

  ![image](https://github.com/user-attachments/assets/c98c6c0d-e819-421a-8f6e-39a842c45ca1)

- **c)** HIV-positive TB Proportion: `TB_HIV_Cases / TB_Total_Cases`

  ![image](https://github.com/user-attachments/assets/8d32b2d9-4b14-4e9e-be83-1bfb8baf0b3b)

---

## 🎛️ 6. Filtering & Parameters

- **a)** Dashboard with a **country selector** to view TB stats over time

  ![image](https://github.com/user-attachments/assets/d7be6b68-8047-4963-8b31-6613b5ffa051)

- **b)** Region filter to compare stats across multiple regions side-by-side

  ![image](https://github.com/user-attachments/assets/f3b20427-1f90-4a23-847d-c76a07a70a2c)

---

## 📌 7. KPI Dashboard Elements

KPIs showing global totals for:

- ** Estimated TB deaths (with and without HIV) **

  ![image](https://github.com/user-attachments/assets/12343521-7e2d-4e31-937d-e73cf3ef9bb7)

---

## 🔗 8. Correlation & Scatter Plot

- Is there a correlation between:
  - TB Incidence  
  - TB/HIV Incidence  
  (by country)

  ![image](https://github.com/user-attachments/assets/67f5f0b3-d825-48e1-b825-f2b395089724)

---

## 📂 Files

- `TB_Dashboard.twbx` — Tableau workbook file with all visuals and dashboards  
- `TB_Burden_Country.csv` — Source data file (linked above)

---

## ✅ Requirements

- Tableau Desktop or Tableau Public (free)

---

## 📜 License

Data is from a public Tableau sample. Analysis is for educational and exploratory purposes.

---

## 🙌 Acknowledgments

Thanks to Tableau for providing the TB Burden dataset and powerful tools for visual data storytelling.


### Climate Change Emission Analysis & Prediction Dashboard   
This project analyzes **supply chain greenhouse gas (GHG) emission factors** across various industries using the *Greenhouse Dataset* from Kaggle. The goal is to identify high-emission sectors, understand the key drivers of emissions, and forecast potential future trends under current patterns.  

---

## 📊 Dataset Information  
**Source:** [Greenhouse Dataset (Kaggle)](https://www.kaggle.com/datasets/alamshihab075/greenhouse-dataset)  
**Files Used:**  
- `SupplyChainGHGEmissionFactors_v1.3.0_NAICS_CO2e_USD2022.csv`  

**Key Columns:**  
- `2017_NAICS_Code` → Industry code  
- `2017_NAICS_Title` → Industry name  
- `Supply_Chain_Emission_Factors_with_Margins` → Emission factor per dollar output (kg CO₂e/USD)

---

## ⚙️ Methodology  
1. **Data Cleaning:**  
   - Removed null and invalid values  
   - Standardized column names and units  
2. **Exploratory Data Analysis (EDA):**  
   - Created heatmaps and bar charts to visualize emission intensity  
   - Identified top 20 emission-intensive industries  
3. **Regression Forecasting:**  
   - Built a linear regression model to estimate **2030 emission factors**  
   - Modeled growth rates based on 2017–2022–2030 trends  

---

## 📈 Key Insights  
- ⚙️ **Manufacturing, energy, and chemical sectors** dominate emissions due to heavy supply chain intensity.  
- 💡 **Healthcare, finance, and education** have the **lowest emission factors**, indicating service-driven efficiency.  
- 📉 Without intervention, **average emissions could rise by 15–25% by 2030**, primarily from industrial and energy production.  
- 🌍 Emission factors are **unevenly distributed**, suggesting the need for targeted sustainability policies per industry rather than a one-size-fits-all approach.  

---

## 💡 Recommended Solutions  
1. **Adopt Cleaner Supply Chains:**  
   Encourage suppliers to switch to low-carbon production methods and renewable energy inputs.  
2. **Industry-Specific Carbon Caps:**  
   Implement regulatory emission ceilings tailored to high-emission industries like manufacturing and construction.  
3. **Incentivize Innovation:**  
   Offer tax benefits for companies that adopt carbon capture or efficiency technologies.  

---

## 📊 Visualizations  

### 🔸 Top 20 Industries by Predicted 2030 Emission Factor  
A bar chart showing the forecasted emission factors (kg CO₂e/USD) — highlights which industries need the most attention.  

### 🔸 Heatmap of Emission Intensities  
A Plotly heatmap visualizing emission levels across industries for quick comparative analysis.  

---

## Technologies Used  
- **Python**  
- **Pandas** — Data manipulation  
- **NumPy** — Statistical computation  
- **Plotly** — Interactive visualization  
- **Scikit-Learn** — Regression modeling  
- **KaggleHub** — Dataset integration  

---

## 🧾 Author  
**Kosha Antala**  
*Data Scientist | Sustainability Analyst*  
🌐 GitHub: [koshaantala](https://github.com/koshaantala)  

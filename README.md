# Global Investment Patterns Analysis  

This project analyzes global investment data to help **Company A** identify the most suitable **countries, industries, and investment opportunities** for allocating funds (between **$1M – $6M per round**). The analysis focuses on countries where English is an official language, with **China** also included in scope.  

---

## 🎯 Project Statement  

**Company A’s objective**:  
To determine the **optimal countries, sectors, and investment types** that align with current global investment trends, while fitting within the company’s target investment size.  

---

## 📌 Business Goals & Sub-Goals  

### 1. **Investment Type Analysis**  
- Evaluate common investment amounts across categories such as:  
  - Venture Capital  
  - Seed  
  - Angel  
  - Private Equity  
- Identify which investment type(s) align with Company A’s strategy ($1M–$6M).  

### 2. **Country Analysis**  
- Determine which countries attract the **highest levels of investment**.  
- Focus only on countries where **English is an official language** (plus China).  
- Provide a ranking of countries based on past investment patterns.  

### 3. **Sector Analysis**  
- Categorize investments into **8 major sectors** (as defined in the mapping file).  
- Map each sub-sector (from the `companies` and `rounds2` datasets) into its **main sector**.  
- Analyze sector-level trends and identify the most attractive industries for investment.  

---

## 📂 Dataset Overview  

The data comes from **[Crunchbase](https://www.crunchbase.com/)**, a leading platform for business and investment insights.  

We rely on **three primary data tables**:  

1. **Companies**  
   - Company details (name, location, sector, etc.)  
   - Mapping to main sectors  

2. **Rounds2**  
   - Investment round details (round type, investment amount, company ID, etc.)  

3. **Mapping**  
   - Sub-sector to sector mapping file (8 predefined sectors)  

---

## 🧭 Project Workflow  

1. **Data Preprocessing**  
   - Load and clean data from the three primary sources  
   - Handle missing values and ensure consistent formatting  
   - Map sub-sectors to major sectors  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of investment sizes by type  
   - Country-level investment aggregation  
   - Sector-wise investment breakdown  

3. **Analytical Insights**  
   - Identify suitable investment types for $1M–$6M rounds  
   - Highlight top-performing countries by total investment  
   - Recommend sectors with strong investment trends  

4. **Visualization**  
   - Charts for investment type distributions  
   - Country-level heatmaps / bar charts  
   - Sector-wise pie charts and time trends  

---

## 📂 Repository Structure  

- `data/` – Contains `companies`, `rounds2`, and `mapping` datasets  
- `EDA_Investment_Types.ipynb` – Investment type analysis  
- `Country_Analysis.ipynb` – Country-level investment analysis  
- `Sector_Analysis.ipynb` – Sector mapping and insights  
- `visualizations/` – Plots and figures from analysis  

---

## ⚙️ How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/global-investment-analysis.git
   cd global-investment-analysis

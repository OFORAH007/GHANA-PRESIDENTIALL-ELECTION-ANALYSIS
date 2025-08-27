# Ghana Presidential Election Analysis (1996–2004)  
*Comparative Analysis of NDC vs NPP Presidential Votes by Region*  

---

## 📌 Project Overview  
This project presents a **comparative analysis of presidential election results** in Ghana between the two major political parties: **National Democratic Congress (NDC)** and **New Patriotic Party (NPP)**.  

Focusing on elections held in **1996, 2000, and 2004**, the analysis explores:  
- National and regional voting trends.  
- Candidate-level performances.  
- Party dominance by region.  
- Vote share visualization using donut charts.  

The study provides insights into **how voting patterns evolved over time** and highlights regions of party strength and weakness.  

---

## 📊 Dataset  
- **Source:** `Election Command Centre.xlsx` (Sheet: `Region`)  
- **Format:** Excel file containing election results across Ghana’s regions from 1996–2024.  
- **Scope of this study:** Filtered to **1996, 2000, 2004** elections and parties **NDC** and **NPP** only.  

---

## 📑 Dataset Description  
The dataset includes the following columns:  

| Column       | Description |
|--------------|-------------|
| `Candidate`  | Name of the presidential candidate |
| `Percentage` | Candidate’s share of votes in the region (proportion) |
| `Votes`      | Absolute number of votes received |
| `Region`     | Region where votes were cast |
| `Status`     | Whether candidate won or lost in that region |
| `Year`       | Election year (1996, 2000, 2004 considered here) |
| `Party`      | Political party (NDC, NPP, Others) |
| `Image`      | Candidate image link (not used in this analysis) |

---

## 🎯 Objectives  
1. Compare **NDC and NPP national vote totals** between 1996–2004.  
2. Analyze **regional voting patterns** for both parties.  
3. Assess **candidate performance by region** (Rawlings, Atta Mills, Kufuor).  
4. Visualize **vote share percentages** using donut charts.  
5. Provide **insights and recommendations** for stakeholders.  

---

## 🛠️ Tools Used  
- **Python 3.11**  
  - `pandas` → Data wrangling  
  - `matplotlib` → Visualizations  
- **Excel** → Initial data review  
- **Markdown** → Documentation  
- **Git/GitHub** → Version control & repository management  

---

## 🔧 Data Preparation  
1. Imported dataset from Excel.  
2. Filtered to **NDC** and **NPP** results for **1996, 2000, 2004**.  
3. Cleaned columns (`Candidate`, `Party`, `Region`).  
4. Aggregated data:  
   - Total votes by **Party & Year**.  
   - Regional votes by **Party & Year**.  
   - Candidate votes and percentages.  
5. Exported processed data to `data/` folder.  

---

## 📈 Exploratory Data Analysis (EDA)  
The following analyses were performed:  

- **National Trends:**  
  - Line chart showing how NDC and NPP national vote totals evolved from 1996–2004.  

- **Regional Distribution:**  
  - Bar charts comparing NDC vs NPP across regions in each election year.  

- **Vote Share:**  
  - Donut charts of NDC vs NPP proportions per election year.  

- **Candidate by Region:**  
  - Bar charts of candidate vote totals by region for NDC and NPP candidates separately.  

---

## 📊 Dashboards & Visuals  

<img width="1266" height="774" alt="Ghana Election_1996-2004" src="https://github.com/user-attachments/assets/ae56fb4d-8ce7-41ad-9ad8-d38721edeafa" />


---

## 📌 Key Findings  
- **1996:** NDC (Rawlings) dominated nationally but lost heavily in **Ashanti Region** (NPP stronghold).  
- **2000:** NPP (Kufuor) gained momentum, flipping multiple regions and winning the presidency.  
- **2004:** NPP consolidated gains, maintaining dominance in Ashanti and making inroads in other regions.  
- **Regional Polarization:** Ashanti consistently favored NPP, while Volta and Northern regions favored NDC.  

---

## ✅ Recommendations  
1. **Party Strategy:**  
   - NDC should strengthen outreach in swing regions like Central and Greater Accra.  
   - NPP should consolidate gains in Ashanti but expand into traditionally NDC-leaning areas.  

2. **Resource Allocation:**  
   - Campaign resources should focus on swing regions with high voter populations.  

3. **Voter Engagement:**  
   - Increased civic education in high-turnout regions can significantly affect results.  

---

## ⚠️ Limitations  
- Dataset limited to **regional-level** results (no constituency breakdown).  
- Excludes smaller parties (“Others”) from deep analysis.  
- Dataset accuracy depends on source reliability.  

---

## 📌 Conclusion  
This analysis demonstrates how Ghana’s presidential elections between **1996 and 2004** were shaped by strongholds and swing regions. The **NDC-NPP rivalry** remains deeply regional, with Ashanti (NPP) and Volta (NDC) as consistent anchors.  

The project highlights the value of **data-driven electoral analysis** for understanding historical voting patterns and shaping future campaign strategies.  

---

## 📂 Repository Structure  


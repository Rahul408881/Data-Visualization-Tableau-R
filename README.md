# 🌍 Global Terrorism Analysis (1970–2017)

![cover page 3](https://github.com/user-attachments/assets/58378304-5904-4dea-8af3-6f4e217c9ef2)

This project explores the **Global Terrorism Database (GTD)** to analyze the evolution of terrorist activities worldwide from **1970 to 2017**.  
Our team performed extensive **data cleaning, preprocessing, exploratory data analysis (EDA), and visualization** using **R and Tableau**.  
The project highlights **temporal trends, regional disparities, casualties, active groups, and attack methods** — contributing to informed security strategies and global policies.

---

## 📂 Repository Structure
- `Project Report.pdf` → Full project report with detailed analysis and findings.

---

## 🧪 Methodology

- **Dataset**: [Global Terrorism Database (GTD)](https://www.start.umd.edu/gtd/)  
  - 180k+ incidents, 1970–2017 (except 1993).  
  - 100+ variables including year, location, attack type, target, weapon, casualties, and terrorist group.  
- **Preprocessing**:  
  - Handling missing values with imputation and placeholders.  
  - Standardizing country names using `countrycode`.  
  - Transforming and cleaning 135 original columns → 26 refined variables.  
- **Tools**: R (tidyverse, ggplot2), Tableau.  

---

## 📊 Key Findings

| Aspect | Insights |
|--------|----------|
| **Trends Over Time** | Spike in attacks after 2006; peak in 2014 with ~34k attacks. |
| **Regions** | Middle East & North Africa most affected (50k+ incidents); Oceania least (282 incidents). |
| **Countries** | Iraq (24,636), Pakistan (14,368), Afghanistan among worst affected. |
| **Casualties** | Iraq highest death toll (~78,589), followed by Afghanistan (~39,384). |
| **Groups** | Taliban (7,478) and ISIL (5,613) most deadly groups. |
| **Attack Methods** | Bombings/Explosions & Armed Assaults dominate (130k+ incidents). |

---

<img width="1027" height="609" alt="Line Graph" src="https://github.com/user-attachments/assets/44db5ab1-2ad7-4c02-8a37-6b927a00d12c" />


## 🖼️ Visualizations

Some examples of visualizations included:

- 📈 **Total Attacks per Year** – sharp rise post-2006.  
- 🌍 **Regional Distribution** – Middle East dominates in number of incidents.  
- 🗺️ **Choropleth Map of Attacks** – Iraq & Pakistan most targeted.  
- 🎯 **Terrorist Success Rate** – high in Iraq, Afghanistan, and South Asia.  
- ⚰️ **Bubble Chart of Total Deaths** – Iraq & Afghanistan suffered the highest tolls.  
- 🏴 **Most Active Terrorist Groups** – Taliban & ISIL lead.  
- 🔫 **Attack Methods by Region** – bombings most common worldwide.  

<img width="452" height="299" alt="Statistics of Attack" src="https://github.com/user-attachments/assets/b6ce162c-f1aa-4071-9fd3-a52ae7e7f519" />

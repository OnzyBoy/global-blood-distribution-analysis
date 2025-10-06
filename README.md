# 🌍 Global Blood Distribution Analysis (Power BI Dashboard)

## 🩸 Overview
This project explores the **global distribution of blood groups** across multiple countries and continents using an open dataset from Kaggle.  
The goal is to identify trends, regional patterns, and dominant blood types worldwide using **Power BI**.

This dashboard provides insights into:
- The most and least common blood groups globally
- Blood type composition by country and continent
- Population distribution and geographic trends

---

## 📊 Key Features
- **Interactive Map:** Displays the most common blood group per country  
- **Dynamic Filters:** Select by Continent, Blood Type, or Country for drill-down analysis  
- **Bar Chart:** Compare Top 10 countries by population  
- **Donut Chart:** Visualize the global proportion of blood groups  
- **Summary KPIs:** Show total population, number of countries, and most/least common blood types  

---

## 🧠 Insights Uncovered
- **O+** emerged as the most common blood group globally.  
- **AB−** is the rarest blood group in most regions.  
- Certain continents show higher variation in negative blood types compared to others.  
- Geographic trends suggest genetic and regional influences on blood type distribution.

---

## 🧰 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Power BI** | Data cleaning, transformation, and visualization |
| **Power Query** | Data preprocessing (removing blanks, errors, duplicates) |
| **DAX** | Creating calculated measures and interactive KPIs |
| **Kaggle Dataset** | Data source for global blood group distribution |

---

## 📂 Dataset
- **Source:** [Global Blood Group Distribution Worldwide Dataset – Kaggle](https://www.kaggle.com/datasets/shuvokumarbasak4004/global-blood-group-distribution-worldwide-dataset)  
- **Attributes:** Country, Blood Type, Percentage, Continent, Population  

*Note: Some countries percentage total for blood types didn't come to 100%.*

---

## 🪜 Steps Taken
1. **Imported and cleaned dataset** in Power Query (handled duplicates, blank values, and special characters).  
2. **Added a Continent column** using conditional mapping for each country.  
3. **Created DAX measures** for total population, number of countries, and most/least common blood groups.  
4. **Built visuals** including map, donut, matrix, and KPI cards for easy interpretation.  
5. **Enhanced interactivity** with slicers for Continent, Blood Type, and Country.  
6. **Applied consistent color themes** and layout for readability and visual balance.

---

## 💻 How to View the Dashboard
1. Download the `.pbix` file from this repository  
2. Open it using **Microsoft Power BI Desktop**  
3. Use the slicers or click on the map to explore interactive visuals

---

## 📈 Dashboard Preview
<img width="1393" height="779" alt="image" src="https://github.com/user-attachments/assets/95817fa4-ad4f-4d8b-9dcf-bd62ee0a2cc3" />

---

## 🧩 Future Improvements
- Add time-series data if historical datasets become available  
- Integrate with external demographic data (e.g., age or gender distribution)  
- Publish an interactive Power BI report online via Power BI Service  

---

## 🧾 License
This project is for **educational and analytical purposes** only.  
Original dataset © Kaggle contributor [Shuvo Kumar Basak](https://www.kaggle.com/datasets/shuvokumarbasak4004).

---

### 👨🏽‍💻 Author
**Aristo Ayako**  
Data Analyst  
📧 [ayakoaristo9@gmail.com]

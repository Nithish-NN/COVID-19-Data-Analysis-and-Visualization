# COVID-19 Tracker: Exploratory Data Analysis and Power BI Dashboard  

![GitHub last commit](https://img.shields.io/github/last-commit/[your-username]/[your-repo-name]?style=flat-square)  
![GitHub repo size](https://img.shields.io/github/repo-size/[your-username]/[your-repo-name]?style=flat-square)  
![GitHub license](https://img.shields.io/github/license/[your-username]/[your-repo-name]?style=flat-square)  

## Project Overview  

This project focuses on **Exploratory Data Analysis (EDA)** and **Power BI dashboard development** for COVID-19 data in India. The dataset contains daily records of **confirmed cases, recoveries, and deaths** across various states and union territories from January 2020 to September 2021.  

### Key Objectives:  
- **Data Cleaning & Processing**: Handling missing values, formatting dates, and calculating cumulative confirmed cases.  
- **EDA using Python**: Generating trends, identifying patterns, and visualizing insights using **Pandas, Matplotlib, and Seaborn**.  
- **Power BI Dashboard**: Creating an **interactive** visualization to explore trends and regional impacts.  
- **Documentation**: Writing reports summarizing key findings from EDA and the dashboard.  

---

## Dataset Description  

- **File Used**: `cleaned_covid_data.csv`  
- **Columns**:  
  - `Sno`: Serial number (unique identifier).  
  - `State/UnionTerritory`: Name of the state or union territory.  
  - `ConfirmedIndianNational`: Confirmed cases among Indian nationals.  
  - `ConfirmedForeignNational`: Confirmed cases among foreign nationals.  
  - `Cured`: Cumulative number of recovered cases.  
  - `Deaths`: Cumulative number of deaths.  
  - `Confirmed`: Daily new confirmed cases.  
  - `Datetime`: Date and time of the record.  
  - `Cumulative_Confirmed`: Computed total confirmed cases per state (added during preprocessing). 

---

## Power BI Dashboard Features  

### **KPIs**  
✔ **Total Confirmed Cases**: 3M  
✔ **Total Recovered Cases**: 6M  
✔ **Total Deaths**: 134K  
✔ **Mortality Rate**: 4.38%  

### **Visualizations**  
📌 **Time Series Plot**: Trends of confirmed, recovered, and death cases over time.  
📌 **Bar Chart**: Top 10 states by total recovered cases.  
📌 **Slicers**: Filter by **date** and **state/UT**.  

### **Interactive Features**  
🔹 **State-wise filtering**: View trends for selected states.  
🔹 **Date-based filtering**: Analyze case surges over time.  

---

## Key Findings  

### **1️⃣ COVID-19 Trends**  
📌 Recovery rates increased significantly after the **second wave (Apr-May 2021)**.  
📌 Mortality rate remained stable at **4.38%**, but total deaths surged during peak waves.  

### **2️⃣ Top 10 Affected States (By Recoveries)**  
1. **[State 1]**: [Value]  
2. **[State 2]**: [Value]  
3. **[State 3]**: [Value]  
4. **[State 4]**: [Value]  
5. **[State 5]**: [Value]  
6. **[State 6]**: [Value]  
7. **[State 7]**: [Value]  
8. **[State 8]**: [Value]  
9. **[State 9]**: [Value]  
10. **[State 10]**: [Value]  
 

### **3️⃣ Data Limitations**  
⚠ The dataset's total confirmed cases (3M) **underrepresents actual cases** (India reported 34M by Sep 2021).  
⚠ Possible **data gaps or underreporting** in `Confirmed` column.  

---

## How to Use the Power BI Dashboard  

### **Requirements**  
📌 Install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)**.  

### **Steps to Open and Explore the Dashboard**  
1️⃣ **Download** `COVID19_Dashboard.pbix` from this repository.  
2️⃣ **Open Power BI Desktop** and load the `.pbix` file.  
3️⃣ **Explore the Dashboard**:  
   - Use **slicers** to filter data by date or state.  
   - Click on a **bar chart** segment to filter the rest of the visuals.  
   - Hover over data points for exact values.  

---

## Project Files  

```
COVID-Tracker-Project/
│
├── COVID19_Dashboard.pbix        # Power BI dashboard
├── cleaned_covid_india_for_powerbi.csv  # Cleaned dataset
├── EDA_Report.pdf                # Exploratory Data Analysis report
├── Key_Insights.pdf              # Summary of key findings
├── COVID19_EDA.ipynb             # Jupyter notebook with Python code
├── cumulative_trends_over_time_corrected.png  # Time series plot
├── top_states_confirmed_corrected.png         # Top 10 states bar chart
├── README.md                     # Project documentation
└── LICENSE (optional)             # License file
```


## Contact  

For queries or collaboration, reach out to:  
📧 nithish.nuthalapat@gmail.com
🔗 [GitHub Profile]  



```markdown
# Google Data Analytics Capstone: Cyclistic Case Study

## 📘 Project Overview
This project is part of the **Google Data Analytics Professional Certificate (Capstone Project)**.  
The objective is to analyze the **Cyclistic bike-share data** to understand how casual riders and annual members use Cyclistic bikes differently, and to provide data-driven recommendations for converting casual riders into annual members.

---

## 🧩 Case Study Background
Cyclistic, a fictional bike-share company in Chicago, wants to increase its number of annual memberships.  
To achieve this goal, the marketing team needs insights into **user behavior differences** between:
- **Casual riders** (single-ride or day-pass users)
- **Annual members**

---

## 📊 Data Source
The data used in this analysis is provided by **Motivate International Inc.** and made publicly available under this [license](https://divvy-tripdata.s3.amazonaws.com/index.html).

- Dataset: **Divvy/Cyclistic trip data (2022–2023)**
- Format: `.csv` monthly ride data
- Personal identifiable information (PII) has been removed.

---

## 🧠 Tools Used
- **Python (Jupyter Notebook)**
  - pandas
  - numpy
  - matplotlib / seaborn
  - datetime
- **Spreadsheet (Excel/Google Sheets)** for data inspection
- **Tableau / Power BI (optional)** for visualization

---

## 🔍 Analysis Steps
1. **Data Cleaning**
   - Removed missing values and duplicates
   - Filtered invalid ride durations or station data
2. **Data Transformation**
   - Extracted weekday, month, and ride length
   - Categorized users as *member* or *casual*
3. **Exploratory Data Analysis (EDA)**
   - Compared average ride times and ride counts
   - Identified popular stations and usage trends
4. **Visualization**
   - Created graphs for ride duration, frequency, and user type behavior
5. **Insights & Recommendations**
   - Highlighted key behavioral differences
   - Suggested marketing strategies to increase membership conversion

---

## 💡 Key Findings
- **Casual riders** prefer weekends and longer rides for leisure.
- **Members** ride more frequently, especially during weekdays.
- **Targeted promotions** for casual riders could encourage membership upgrades.

---

## 📁 File Structure
```

GoogleCaseStudy_Cyclistic.ipynb   # Main analysis notebook
README.md                         # Project overview and documentation

````

---

## 🚀 How to Run the Notebook
1. Clone or download this repository.
2. Open the notebook in **Jupyter Notebook** or **Google Colab**.
3. Install dependencies if needed:
   ```bash
   pip install pandas numpy matplotlib seaborn
````

4. Run all cells to view the full analysis and visualizations.

---

## ✍️ Author

**Gouthaman**
*Google Data Analytics Professional Certificate – Capstone Project*

---

## 📜 License

This project uses the public **Divvy/Cyclistic data** provided under this [license agreement](https://divvy-tripdata.s3.amazonaws.com/index.html).

---

```

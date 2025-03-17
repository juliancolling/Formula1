
# Formula 1 Data Analytics Project from (1999-2024) : Insights from 25 Years of Racing 

## Overview 

This project is a **comprehensive analysis of Formula 1 race data from 1999 to 2024**, utilising **Python for data processing, exploratory data analysis (EDA) and Tableau for visualisation**. The goal is to investigate trends in **driver performance, constructor dominance and circuit influence on race outcomes**. 

This project is managed using a structured approach with **GitHub Kanban boards and repositories** to track progress, version control and project evolution. 

## Dataset Content 

The Formula 1 dataset provides historical race data, covering essential aspects of the sport, including: 

- **Race Results:** Positions, points and fastest lap times. 
- **Driver Information:** Names, nationalities and career statistics.  
- **Constructor Data:** Team performance trends over the years.
- **Circuits:** Locations, track names and number of hosted races. 
### **Ideas for Analysis:** 
- **Trends in race frequency** – *How has the number of races per season evolved over time?*   
- **Driver success rates** – *Who are the most dominant drivers based on points accumulated?* 
- **Constructor dominance** – *Which teams have led the championship standings in different F1 eras?*    
- **Circuit influence on performance** – *Which tracks have been historically significant in determining championship outcomes?* 

This dataset allows for deep exploration of Formula 1’s evolution, enabling insights into competition trends, driver consistency, and team performance across different decades. 

## Hypothesis & Business Goals  
### **Hypothesis:**  
*“Certain circuits play a major role in determining race outcomes, and constructor dominance shifts over time. By analysing performance trends, we can identify key factors influencing Formula 1 championships.”* 
### **Business Goals:** 
1. **Determine the most influential circuits** in race outcomes and championship results.  
2. **Analyse driver performance trends** over 25 years, identifying the most dominant competitors.  
3. **Track constructor trends** to understand how teams like Ferrari, Mercedes and Red Bull evolved over time. 
4. **Provide interactive insights through a structured Tableau dashboard**.  
5. **Plan future development**, including predictive modeling and live data integration.  

## Project Plan  
### **High-Level Steps Taken for the Analysis**  
The analysis followed a structured process:  

1. **Data Acquisition** – Obtained publicly available Formula 1 race data.  
2. **Data Cleaning and Processing** – Handled missing values, normalied numerical data and formatted dates.  
3. **Exploratory Data Analysis (EDA)** – Used various visualisation techniques to extract trends in race results, driver performance and constructor dominance.  
4. **Dashboard Development** – Created an interactive Tableau dashboard to provide insights.  
5. **Documentation and Reporting** – Documented findings, key insights and future development plans. 
### **Data Management Approach** 

- **Collection:** Gathered structured datasets containing race, driver, constructor and circuit data. 
- **Processing:** Cleaned and formatted data using **Python (Pandas, NumPy)** to ensure accuracy and consistency.  
- **Analysis:** Applied statistical methods and visualisation techniques to uncover trends.  
- **Interpretation:** Key findings were summarised and visualised in Tableau to provide an interactive experience. 
### **Research Methodologies Used**

- **Descriptive Analysis:** To explore historical trends in F1 race results. 
- **Comparative Analysis:** To evaluate team and driver performance across different time periods.  
- **Geospatial Analysis:** To map circuit locations and analyse global race distribution. 
- **Visualisation-Driven Insights:** Used Tableau for intuitive and interactive storytelling, making data-driven insights accessible to both technical and non-technical users.  

## Data Collection and Processing 
### **ETL (Extract, Transform, Load) Approach:**  

- **Extract:** Data collected from publicly available Formula 1 sources. 
- **Transform:** Handle missing values, normalise numerical data, and format date fields. 
- **Load:** Store structured data for **Jupyter Notebook analysis & Tableau visualisation**.  


## Exploratory Data Analysis (EDA)  
 
EDA was conducted to extract meaningful insights from the dataset before visualisation and dashboard creation. The following analyses were performed:

1. **Number of Races Per Year**

* A bar plot was used to calculate the number of races held each year over time. This visualisation helps illustrate the expansion of the Formula 1 calendar and how the sport has evolved, reflecting changes in scheduling, the addition of new circuits and shifts in race distribution across different seasons. By analysing this trend, we can better understand how the increasing number of races has impacted teams, drivers and the overall competitive landscape of F1.  

2. **Top 10 Most Successful Drivers** 

* A bar plot was used to calculate the total points accumulated by drivers over time, establishing the most successful drivers. This visualisation provides insights into driver consistency, performance longevity and how various eras of racing have influenced point accumulation. By analysing total points rather than just wins, we gain a broader perspective on which drivers have demonstrated sustained excellence across multiple seasons. 

3. **Constructor Performance Over Time** 

* A line plot was used to analyse constructor dominance over time by tracking the number of race wins for each team across different seasons. This visualisation helps in understanding how certain teams, such as Ferrari, Mercedes, and Red Bull have maintained periods of success, while others have fluctuated in performance. The line plot effectively showcases championship trends, revealing patterns of dominance, competitive shifts and the impact of rule changes on team success. 

4. **Most Popular Circuits by Number of Races** 

* A pie plot was initially used to visualise the proportion of races hosted by each circuit, providing a quick comparison of circuit popularity. However, to better analyse trends, a bar plot was later utilised to show the exact number of races hosted by each circuit over time. This visualisation highlights which tracks have consistently been part of the F1 calendar and how circuit usage has evolved, offering insights into the impact of historical and modern venues on race outcomes. 

### **Key Findings:**  

* **Race frequency has increased**, requiring better endurance from drivers and teams. 
* **Silverstone, Monza and Spa-Francorchamps are among the most frequently used circuits**.  
* **Mercedes, Ferrari and Red Bull have dominated constructor championships**. 
* **Driver consistency is key**, as multi-season champions often succeed at specific circuits. 

## Dashboard & Visualisations 

### **Tableau Dashboard Overview** 

#### **Dashboard Layout:** 

* **Left Side:** **Geographical Map of Circuits** 
![Map](<Screenshots/Screenshot Circuit map.png>)
* **Top Right:** **Driver Performance Trends**  
* **Bottom Right:** **Constructor Performance Over Time** 
* **Interactive Filters:** Year, Circuit, Driver and Constructor

## Screenshots 

Screenshots of the dashboard and the (EDA) plot graphs can be found in the **screenshots folder** of the repository 

### **Summary of Key Charts:** 

1. **Plot Graphs:** A visual understanding of the merged data set. 
2. **Driver Performance Chart:** Identifies the most successful drivers in terms of wins. 
3. **Constructor Trends:** Examines which teams have dominated over time.  
4. **Circuit Map:** Visualises the global impact of race locations. 

## Future Development 

1. **Machine Learning for Race Predictions** 
Implement predictive models to forecast **race outcomes based on driver performance, track history, and team strategies**. 

2. **Live Data Integration** 
Utilise **F1 APIs** to integrate real-time race data. 

## Technology Framework 

* **Main Data Analysis Libraries (Pandas, NumPy, Matplotlib, Seaborn)** Data processing and visualisation. 
* **GitHub (Kanban & Repo)** Project management and version control.  
* **Tableau** Interactive dashboard creation. 
* **Draw.io** Used to design the wireframe for the dashboard. 

## Ethical considerations 
* **Data Privacy:** No confidential data used; all data is publicly sourced. 
* **Fairness & Transparency:** Results are **unbiased and reproducible**. 
* **Compliance:** Ensures **adherence to open data governance best practices**.  


## Project Development Roadmap 
* **Version Control:** Maintained using **GitHub commits and project board**. 
* **Challenges Faced:** Handling large datasets, ensuring Tableau responsiveness. 
* **Next Steps:** Expanding **ML models for predictions** and integrating **real-time race updates**. 

## Deployment & Accessibility

* **Tableau Dashboard:** [https://public.tableau.com/app/profile/julian.colling/viz/F1_25YearsofRacing/F1_25YearsofRacing]
* **Jupyter Notebook:** [[Notebook](jupyter_notebooks/F1_Analysis.ipynb)]
* **GitHub Repository:** [Formula1 Project](https://github.com/juliancolling/Formula1) 
Install required dependencies: `pip install -r requirements.txt`
* **GitHub Project Board:** [https://github.com/users/juliancolling/projects/4]

### Credits & Acknowledgments

* **Data Sources:** Kaggle F1 dataset, [https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020?select=constructors.csv]
* **Tools Used:** Python, Tableau, GitHub, Draw.io 
* **Project Contributors:** Special thanks to **mentors at Code Institute, peers, and Paul Golder** for feedback and insights.


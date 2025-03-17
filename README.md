
# Formula 1 Data Analytics Project from (1999-2024) : Insights from 25 Years of Racing 

## Overview 

This project is a**comprehensive analysis of Formula 1 race data from 1999 to 2024**, utilising **Python for data processing, exploratory data analysis (EDA) and Tableau for visualisation**. The goal is to investigate trends in **driver performance, constructor dominance and circuit influence on race outcomes**. 

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
*“Certain circuits play a major role in determining race outcomes, and constructor dominance shifts over time. By analyzing performance trends, we can identify key factors influencing Formula 1 championships.”* 
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
2. **Data Cleaning & Processing** – Handled missing values, normalied numerical data and formatted dates.  
3. **Exploratory Data Analysis (EDA)** – Used various visualisation techniques to extract trends in race results, driver performance and constructor dominance.  
4. **Dashboard Development** – Created an interactive Tableau dashboard to provide insights.  
5. **Documentation & Reporting** – Documented findings, key insights and future development plans. 
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

## Data Collection & Processing 
### **ETL (Extract, Transform, Load) Approach:**  

- **Extract:** Data collected from publicly available Formula 1 sources. 
- **Transform:** Handle missing values, normalise numerical data, and format date fields. 
- **Load:** Store structured data for **Jupyter Notebook analysis & Tableau visualisation**.  


## Exploratory Data Analysis (EDA)  
 
EDA was conducted to extract meaningful insights from the dataset before visualisation and dashboard creation. The following analyses were performed:

1. **Number of Races Per Year**

* A bar plot was used to calculate the number of races held each year over time. This visualisation helps illustrate the expansion of the Formula 1 calendar and how the sport has evolved, reflecting changes in scheduling, the addition of new circuits and shifts in race distribution across different seasons. By analysing this trend, we can better understand how the increasing number of races has impacted teams, drivers and the overall competitive landscape of F1.  

2. **Top 10 Most Successful Drivers** 

*A bar plot was used to calculate the total points accumulated by drivers over time, establishing the most successful drivers. This visualisation provides insights into driver consistency, performance longevity and how various eras of racing have influenced point accumulation. By analysing total points rather than just wins, we gain a broader perspective on which drivers have demonstrated sustained excellence across multiple seasons. 

3. **Constructor Performance Over Time** 

*A line plot was used to analyse constructor dominance over time by tracking the number of race wins for each team across different seasons. This visualisation helps in understanding how certain teams, such as Ferrari, Mercedes, and Red Bull have maintained periods of success, while others have fluctuated in performance. The line plot effectively showcases championship trends, revealing patterns of dominance, competitive shifts and the impact of rule changes on team success. 

4. **Most Popular Circuits by Number of Races** 

*A pie plot was initially used to visualise the proportion of races hosted by each circuit, providing a quick comparison of circuit popularity. However, to better analyse trends, a bar plot was later utilised to show the exact number of races hosted by each circuit over time. This visualisation highlights which tracks have consistently been part of the F1 calendar and how circuit usage has evolved, offering insights into the impact of historical and modern venues on race outcomes. 

### **Key Findings:**  

* **Race frequency has increased**, requiring better endurance from drivers and teams. 
* **Silverstone, Monza and Spa-Francorchamps are among the most frequently used circuits**.  
* **Mercedes, Ferrari and Red Bull have dominated constructor championships**. 
* **Driver consistency is key**, as multi-season champions often succeed at specific circuits. 

## Dashboard & Visualisations 

### **Tableau Dashboard Overview** 

#### **Dashboard Layout:** 

* **Left Side:** **Geographical Map of Circuits** 
* **Top Right:** **Driver Performance Trends** 
* **Bottom Right:** **Constructor Performance Over Time**
* **Interactive Filters:** Year, Circuit, Driver and Constructor

#### **Screenshots:** 

Screenshots of the dashboard can be found in the **screenshots folder** of the repository
![alt text](<Screenshots/Screenshot Circuit map.png>)









## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.

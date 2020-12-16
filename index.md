## Welcome Jesse's Page!  

This is my GitHub page for my final project in DATS 6401 - Visualization of Complex Data at The George Washington University. 

My final project (Analysis of Chronic Health Indicators) analyzes chronic health indicator data, detailed below. 

### DATS 6401 - Final Project: Analyzing Chronic Health Indicators

Project introduction: Chronic health indicators are measurements taken by the Centers for Disease Control (CDC), the Council of State and Territorial Epidemiologists (CSTE), and the National Association of Chronic Disease Directors (NACDD) that indicate prevalence of a certain chronic diseases, as well as the prevalence of their risk factors. According to the CDC, There are over 124 indicators for 18 topic groups: alcohol; arthritis; asthma; cancer; cardiovascular disease; chronic kidney disease; chronic obstructive pulmonary disease; diabetes; immunization; nutrition, physical activity, and weight status; oral health; tobacco; overarching conditions; and new topic areas that include disability, mental health, older adults, reproductive health, and school health. This project analyzes the prevalence of chronic diseases using their corresponding chronic disease indicators in the United States. The chronic indicators that this project is focused on are pertaining to the asthma, diabetes, chronic kidney disease, obesity, tobacco, alcohol, and cardiovascular disease topic groups.

Project Relevance: Chronic diseases have a substantial impact on one’s wellbeing, but also are high-risk factors for other diseases, such as SARS-CoV-2 (COVID-19). According to the CDC, risk for hospitalization compared to people without these conditions is significantly increased if you have Asthma (1.5x), Hypertension (3x), Obesity (3x), Diabetes (3x), Chronic Kidney Disease: (3x), Severe Obesity (4.5x), two conditions (4.5x), three or more conditions (5x). 

Project Purpose and methodology: The purpose of this project is to analyze the trends in chronic health indicator data using data visualizations. For each chronic health indicator, the three states with the highest prevalence and three states with the lowest prevalence of each chronic health indicator were selected for the most recent year in the dataset. The chronic health data for these six states were then analyzed and compared using data visualizations. The chronic health indicators that were chosen are: Current asthma prevalence among adults aged >=19 years, Prevalence of diagnosed diabetes among adults aged >=18 years, Prevalence of chronic kidney disease among adults aged >=18 years, Overweight or obesity among adults aged >=18 years, Current smoking among adults aged >=18 years, Heavy drinking among adults aged >= 18 years, Mortality from total cardiovascular diseases.

Project Acknowledgements: CDC (Dataset Provider), Dr. Nima Zahadat (Course Instructor)


**Details of the project:**
- Datasets used: "Chronic Health Indicators" via [CDC](https://catalog.data.gov/dataset/u-s-chronic-disease-indicators-cdi) 

- Time Period of data for Chronic Health Indicators: (Asthma: 2011-2018; Diabetes: 2011-2018; Chronic Kidney Disease: 2011-2018; Obesity: 2011-2018; Tobacco: 2011-2018; Alcohol: 2011-2018; Cardiovascular diseases: 2011-2017).

-States Selected to be analyzed based on 2018 data:
1. Asthma High Prevalence States (); Asthma Low Prevalence States


- Time period: 2010-2017

- Specific datasets analyzed: 
1. Estimated number of Annual AIDS- Related deaths globally (For all countries in the dataset)
2. Total Estimated Number of Children Living with HIV-AIDS
3. Annual New HIV Infections in Children
4. Annual New HIV Infections in Children as a rate per 1000 uninfected children
5. Healthcare spending per capita in USD

The different datasets were created using python in Juypter Notebook. You can access the plots and figures via [Zenodo](https://zenodo.org/record/4266957)

# Conclusions

1. For states with high prevalence of a chronic health indicator, they have a much higher net change over time compared to the states with low prevalence of the same chronic health indicator: (asthma: 1.43%; diabetes 2.97%; chronic kidney disease: 1.6%; obesity 4.93%; alcohol: 1.76%; tobacco -4.43%).

2. For states with low prevalence of a chronic health indicator, they generally have a very constant prevalence rate with little change: (asthma: 0.2%; diabetes 0.87%; chronic kidney disease: 0.23%; obesity 2.63%; alcohol: 0.23%; tobacco -3.6%).

3. All chronic health indicators for both high prevalence and low prevalence states increased over time, except for tobacco which decreased on average 4.43% to 23.77% in high prevalence states and 3.6% to 10.73% for low prevalence states.  

4. Total deaths from cardiovascular diseases also differed significantly between the high prevalence and low prevalence chronic health indicator states: The average total deaths from cardiovascular  diseases for high prevalence states (317.43) compared to that of low prevalence states (249.03).


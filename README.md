# Better-Health-using-500-Cities-data
<img alt="500cities" src="https://user-images.githubusercontent.com/50805611/68406736-4d0e0f80-0150-11ea-91f3-6478648a7418.PNG">

## Introduction:
Physical health is the state of being free from illness or injury. It can cover a wide range of areas including healthy diet, healthy weight, dental health, personal hygiene and sleep. Physical health is vital for overall well-being. Chronic illness like cancer, diabetes, asthma, arthritis cannot be cured but can be managed. Putting into practice the old saying 'prevention is better than cure' – modelled physical health not being good for more than 14 days to identify the most significant contributors. 
The data used for the analysis is “500 Cities: Local Data for Better Health” project from the Robert Wood Johnson Foundation. Link: https://www.cdc.gov/500cities/ Three types of health-related data that are tracked in the project
1.	Health Outcomes 
Arthritis, asthma, high blood pressure, high cholesterol, cancer, diabetes, kidney disease, pulmonary disease stroke, mental health not good for >14 days, physical health not good for >14 days, all teeth lost
2.	Prevention 
Current lack of health insurance, visits to doctor within past year, visits to dentist, taking medicine for BP, cholesterol screening, mammography, pap smear, fecal occult blood test, up to date on preventative services for men (or women)
3.	Unhealthy Behaviors 
Binge drinking, smoking, no leisure time physical activity, obesity, sleeping less than 7 hours

For the analysis, all the variables from Prevention and Unhealthy Behaviors are considered as independent variables. Three new variables are feature engineered from the existing variables. One of them is the combined variable for “up to date on preventative services for men (or women)” as “up to date on preventative services”. The others are Unhealthy behavior score and Young Prevention Score calculated based on unhealthy behaviors and prevention categories based of age above 18.

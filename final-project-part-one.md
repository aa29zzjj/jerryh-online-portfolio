| [home page](https://aa29zzjj.github.io/jerryh-online-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |



# Topic: The Shrinking Population of Pennsylvania


I have been in the US for 6 years, and I have been in Pennsylvania for 5 years, which concludes my whole college & master life.
Although urban centers in Pennsylvania like Pittsburgh and Philadelphia continue to develop, many towns across the state are shrinking - in population, jobs, and services.
This makes me want to focus on this topic to see why there are more people is leaving from Pennsylvania to other states. Through a combination of data visualization and storytelling, I will present this project by relative data that will highlight:


1. What are the top 5 towns in Pennsylvania that are shrinking the fastest

2. What key factors (e.g. job loss, aging population, lack of amenities) correlate with the decline

3. What life looks like in these “invisible cities” today

The purpose of this topic is to raise awareness about these communities often lost in big-picture state or national statistics. I would like to let the people who live in Pennsylvania to understand: What is the key factor that makes a shrinking population, and how can we attract more people to decide to stay in Pennsylvania?

## Initial sketches
1. Bar chart to every year's total population, every bar chart is combined to every town in Pennsylvania.
An example sketch is shown below (Made by [colab](https://colab.research.google.com/)):
![image](https://github.com/user-attachments/assets/107a3d17-34b7-451e-ad8d-0fa867924582)

Note: These are the initial sketches. Not the actual sketch.

2. A line graph that shows the average annual salary in each Pennsylvania town.
An example sketch is shown below (Made by [colab](https://colab.research.google.com/)):
![image](https://github.com/user-attachments/assets/4f686d75-7d56-4d09-81d6-8cd1d15d8ee6)

Note: These are the initial sketches. Not the actual sketch.

3.  Horizontal bar chart forthe  unemployment rate for each Pennsylvania town
An example sketch is shown below (Made by [colab](https://colab.research.google.com/)):
![image](https://github.com/user-attachments/assets/0504fa6c-8218-4a82-b88a-599250d49a62)
Note: These are the initial sketches. Not the actual sketch.

4. A bar chart graphic for percentage Enrollment change in Pennsylvania
An example sketch is shown below (Made by [colab](https://colab.research.google.com/)):
![image](https://github.com/user-attachments/assets/2c7e1707-7229-4dfd-8a03-d1b9f6973f3b)
Note: These are the initial sketches. Not the actual sketch.

5. A bar chart graphic for the safety score in Pennsylvania town
An example sketch is shown below (Made by [colab](https://colab.research.google.com/)):
![image](https://github.com/user-attachments/assets/70554cd8-328e-41ab-b082-db4d8009400c)
Note: These are the initial sketches. Not the actual sketch.

# The data
I use these data sources to:
1. Find out which are the top 5 shrinking towns in PA
2. What is the main factor that causes the population to shrink in PA?
3. What can be the improvement for increasing PA's population?

Use the source from the Pennsylvania State Data Center to find the shrinking city.
The report shows several values that refer to population increase/decrease rate.
From the map table, I will use chatGPT to estimate the rate for each city to estimate the population increase/decrease rate.
Source: [Pennsylvania State Data Center](chrome-extension://bdfcnmeidppjeaggnmidamkiddifkdib/viewer.html?file=https://pasdc.hbg.psu.edu/sites/default/files/resources/2020-municipal-population-estimates-May_2021.pdf?utm_source=chatgpt.com)
Available Data Appearance:
![image](https://github.com/user-attachments/assets/9614bfcc-9fe4-46d0-998d-8654357262bc)


Use the United States Census to find the total population in each Pennsylvania town, and type the citizen for each year to analyze the main living population and number of shrinking population.
Source: [United States Census](https://data.census.gov/)

Data used:
1. ACS Demographic and Housing Estimates
Available Data Appearance:
In the data table, we can check the sex, age, and any other details that relate to town citizen.
![image](https://github.com/user-attachments/assets/5ca7eca4-3f05-425f-962a-911e907b53c3)

2. Selected Housing Characteristics
To see how many units of housing for each town Homeowner vacancy rate and any other usable data to check the density for each town
![image](https://github.com/user-attachments/assets/3a2af74c-d65a-45d3-adf4-4d2dc28f1275)

Use the Pennsylvania Department of Education to find out the enrollment rate for each town.
Source: [Pennsylvania Department of Education](https://www.pa.gov/agencies/education.html)

It provides data reports for enrollment from each school. Can calculate the enrollment rate by the data from the United States Census
![image](https://github.com/user-attachments/assets/70ffb6a4-bcec-482a-82f5-1edd67cb75e2)

Use the Bureau of Labor Statistics to get the unemployment rate for each city in PA.
Source: [Bureau of Labor Statistics](https://download.bls.gov/pub/time.series/la/)
To get the PA's average unemployment rate for each year to check if unemployment is the factor that shrinks the population
year: the year of data
period: the month of data. i.e., M01 = January
value: unemployment rate. i.e., 8.1 = 8.1%

![image](https://github.com/user-attachments/assets/d455be80-d7bf-4f11-b562-fec7411be42e)


Use the Uniform Crime Report System to calculate the safety score in each PA town.
Source: [Uniform Crime Report System](https://www.ucr.pa.gov/PAUCRSPUBLIC/Home/Index)

Get the clearance rate to check the safety score of PA's city/town
![image](https://github.com/user-attachments/assets/fd66dacb-44da-493d-bfa6-f24101799ff5)


# Method and medium
I will use Shorthand for the storytelling platform, combined with: 
1. Tableau & Flourish (generate map table if necessary) to initialize the table format
2. Using [colab](https://colab.research.google.com/) to make the graphic design more specific.
3. upload to Github profile

Finally, a polished Shorthand page with embedded, interactive charts and visual storytelling will be completed
## References
Data source: 
[Pennsylvania State Data Center](chrome-extension://bdfcnmeidppjeaggnmidamkiddifkdib/viewer.html?file=https://pasdc.hbg.psu.edu/sites/default/files/resources/2020-municipal-population-estimates-May_2021.pdf?utm_source=chatgpt.com)
[United States Census](https://data.census.gov/)
[Pennsylvania Department of Education](https://www.pa.gov/agencies/education.html)
[Bureau of Labor Statistics](https://download.bls.gov/pub/time.series/la/)
[Uniform Crime Report System](https://www.ucr.pa.gov/PAUCRSPUBLIC/Home/Index)

## AI acknowledgements
I use ChatGPT to find the available data source, deciding the best graph for presenting to viewers.
